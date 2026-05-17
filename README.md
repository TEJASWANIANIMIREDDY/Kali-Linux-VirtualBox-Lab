# Kali Linux Virtual Machine Setup Using VirtualBox

![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Virtualization](https://img.shields.io/badge/Tool-VirtualBox-orange)
![OS](https://img.shields.io/badge/OS-Kali%20Linux-purple)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# Overview

This project documents the setup of Kali Linux on a Windows system using Oracle VirtualBox.

A prebuilt Kali Linux VirtualBox image was used instead of manually installing Kali Linux using an ISO file. This helped simplify the setup process and create a beginner cybersecurity practice lab.

---

# Tools Used

- Oracle VirtualBox
- Kali Linux Virtual Machine
- Windows 10/11 (64-bit)
- 7-Zip / WinRAR

---

# System Requirements

| Component | Recommended |
|------------|-------------|
| RAM | 4 GB or more |
| CPU | Dual Core |
| Storage | 25 GB free space |
| Operating System | Windows 10/11 64-bit |

---

# Installation Steps

## Step 1: Install VirtualBox

1. Open browser
2. Search for VirtualBox
3. Visit official Oracle VirtualBox website
4. Download Windows Hosts version
5. Install VirtualBox

---

## Step 2: Download Kali Linux Virtual Machine

1. Visit Kali Linux official website
2. Open Downloads section
3. Select Virtual Machines
4. Download VirtualBox image

---

## Step 3: Extract Downloaded File

1. Locate downloaded `.7z` or `.zip` file
2. Use 7-Zip or WinRAR
3. Extract files into a separate folder

Example:

```text
D:\KaliLinux\
```

---

## Step 4: Import Kali Linux into VirtualBox

1. Open VirtualBox
2. Click Machine → Add
3. Select the `.vbox` file
4. Import virtual machine successfully

---

## Step 5: Configure Virtual Machine

- Allocated RAM
- Verified storage
- Configured processor settings
- Checked network adapter configuration

---

## Step 6: Start Kali Linux

1. Start the virtual machine
2. Wait for Kali Linux boot
3. Access Kali Linux desktop and terminal

---

# Screenshots

## VirtualBox Configuration

![VirtualBox Manager](images/virtualbox-manager.png)

## Kali Linux Desktop

![Kali Desktop](images/kali-desktop.png)

---

# Skills Learned

- Virtualization Basics
- Linux Environment Setup
- Virtual Machine Management
- Cybersecurity Lab Configuration
- Basic Networking Setup

---

# Future Improvements

- Learn Linux terminal commands
- Practice Nmap scanning
- Perform packet analysis using Wireshark
- Explore cybersecurity tools in Kali Linux

---

# Project Structure

```text
Kali-Linux-VirtualBox-Lab/
│
├── README.md
│
└── images/
    ├── virtualbox-manager.png
    └── kali-desktop.png
```

---

# Author

Tejaswani
