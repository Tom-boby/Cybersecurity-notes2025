# Cybersecurity Notes 2025

Welcome to the **Cybersecurity Notes 2025** repository by [Vaishnavu C V](https://github.com/vaishnavucv). This repository contains structured notes, guides, and resources to support your journey through ethical hacking, penetration testing, and advanced cybersecurity topics.

---

## 🔧 How to Download and Install VirtualBox

1. Visit the official VirtualBox website: [https://www.virtualbox.org](https://www.virtualbox.org).
2. Navigate to the **Downloads** section and select your host OS (Windows, macOS, or Linux).
3. Download the latest stable version of VirtualBox installer.
4. Run the installer and follow the on-screen instructions to complete the installation.
5. (Optional but recommended) Install the VirtualBox Extension Pack for added USB, RDP, and network features.

---

## 🐱‍💻 How to Download Kali Linux and Open in VirtualBox

1. Go to the official Kali Linux downloads page: [https://www.kali.org/get-kali/](https://www.kali.org/get-kali/).
2. Download the **Kali Linux VirtualBox Image (.ova)** under "Virtual Machines".
3. Open VirtualBox > File > Import Appliance > Browse and select the `.ova` file.
4. Click **Next**, review the settings, then click **Import**.
5. Once imported, select the VM and click **Start** to boot Kali Linux.

---

## 🚀 What to Do in Kali Linux After First Boot

1. **Update the system**:
   ```bash
   sudo apt update && sudo apt full-upgrade -y
   ```
2. **Create a new non-root user** (for best practice):
   ```bash
   sudo adduser yourusername
   sudo usermod -aG sudo yourusername
   ```
3. **Install essential tools**:
   ```bash
   sudo apt install git curl unzip net-tools -y
   ```

---

> 📁 Explore the notes, follow the structured learning path, and stay ahead in cybersecurity.

### 📌 Author
**Vaishnavu C V** – Principal Cybersecurity Engineer | Ethical Hacker | Mentor

🔗 [GitHub](https://github.com/vaishnavucv) | 🧠 [Cyber Range Projects](https://github.com/vaishnavucv?tab=repositories)

---

### ⭐ Don't forget to star this repository if you find it useful!

> "Train hard. Hack smart. Stay ethical."

---
