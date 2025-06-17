# 🛡️ Linux Security Hardening Script for CyberPatriot

This Bash script is designed to **secure and harden a Linux system** in preparation for CyberPatriot competitions. It automates essential security tasks, ensuring the system aligns with cybersecurity best practices.

---

## 🔍 Overview

This script performs the following key actions:

### ✅ Prerequisite Check
- Ensures the script is run with **root privileges** to allow system-level changes.

### 📝 Logging
- Logs all operations to `/var/log/security_script.log` for transparency and auditing.

### ⚠️ Error Handling
- Handles errors gracefully and provides clear feedback to the user.

### 🔐 Security Configurations
- Enforces a **minimum password length** of 8 characters.
- Disables **null passwords** to prevent weak account setups.

### 🔥 Firewall Setup
- Enables and configures **UFW (Uncomplicated Firewall)** for basic network protection.

### 🖥️ Remote Access
- Installs **X2GO**, a secure remote desktop access service.

### 🛑 Service Management
- Stops and disables the **Nginx** service to reduce unnecessary exposure.

### ⬆️ System Updates
- Sets up **daily update checks** to keep the system up to date with security patches.

### 🔒 SSH Security
- **Disables root login** over SSH to reduce the risk of unauthorized access.

---

## ⚙️ Script Features

- Modular and extensible design for future enhancements.
- Backs up configuration files before changes.
- Detailed logging for **auditing and troubleshooting**.

---

## -----------------
## End Of Overview
## -----------------

