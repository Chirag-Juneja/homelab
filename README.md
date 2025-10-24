# 🏠 homelab

This repository contains the configuration files and automation scripts for my personal homelab setup. It serves as a centralized resource for managing various services and applications within my home network. The setup focuses on media management, file sharing, and network service automation.

---

## 🛠️ Requirements

Before using the scripts and configurations in this repository, ensure the following are installed on your system:

1. **Docker** – for containerized applications and services.
2. **Rsync** – for file synchronization and backup tasks.
3. **Samba** – to enable file sharing across devices on your network.
4. **Avahi** – for mDNS/Bonjour network discovery on Apple devices.

> Optional: For certain scripts, ensure you have appropriate permissions (sudo/root) to apply system-level configurations.

---

## 📂 Directory Structure

- **`automation/`** – Scripts for backup service and system tasks.  
- **`jellyfin/`** – Configuration files for setting up and managing the Jellyfin media server.  
- **`smb/`** – Samba configuration files for network file sharing.  

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/chirag-juneja/homelab.git
cd homelab

