<h1 align="center">☀️ Run-Any-Windows-On-Chromebook</h1>

<p align="center">
  <img src="https://img.shields.io/github/stars/yourusername/Run-Any-Windows-On-Chromebook?style=social">
  <img src="https://img.shields.io/github/forks/yourusername/Run-Any-Windows-On-Chromebook?style=social">
  <img src="https://img.shields.io/github/license/yourusername/Run-Any-Windows-On-Chromebook">
</p>

---

## 📌 Description  
🌟 Run **any version of Windows** (from 1.0 to 10) on your Chromebook using Linux development mode.  
💡 Great for retro computing fans, developers, or anyone curious about Windows history and compatibility.  

---

## 🚀 Features  
✔️ **Multiple Windows Versions** – Boot Windows 1.0, 3.1, XP, Vista, 7, 8, and 10.  
✔️ **ISO & QCOW2 Support** – Install from ISO files or use ready-to-run disk images.  
✔️ **Optimized QEMU Setup** – Smooth mouse integration, fullscreen scaling, and customizable RAM/CPU profiles.  
✔️ **Automation Ready** – Create aliases and launchers for one-command VM startup.  

---

## 🦾 Installation  

### 1. Enable Linux Development  
- Go to **Settings → Developers → Linux development environment** and turn it on.
 
```bash
### 2. Update Linux container
sudo apt update && sudo apt upgrade -y

### 3. Downloading Qemu Kvm
sudo apt install qemu-kvm libvirt-daemon-system virt-manager -y

