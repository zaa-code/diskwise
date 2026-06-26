# DiskWise 🚀
### Smart Disk Space Analyzer & Clean Up Tool for Windows

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(x64)-blue?style=for-the-badge&logo=windows)](https://github.com/zaa-code/diskwise)
[![Framework](https://img.shields.io/badge/Powered%20By-Tauri%20%26%20Rust-orange?style=for-the-badge&logo=rust)](https://tauri.app/)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Offline%20%2F%20Local-success?style=for-the-badge)](https://github.com/zaa-code/diskwise)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://github.com/zaa-code/diskwise/blob/main/LICENSE)

**DiskWise** is a modern Windows desktop application designed to analyze storage drive allocations and safely clean up system junk files. Powered by **Rust** on the backend for high-speed file walking, and **Tauri + Next.js** on the frontend to deliver a beautiful, responsive, and highly interactive dashboard interface.

---

## ✨ Key Features

### 🔍 1. Deep Storage Drive Analysis
* Scan physical storage drives (SSD, HDD, USB drives) in milliseconds.
* Map used vs. free storage spaces using intuitive, interactive visual charts.
* Automatically detect partition file system formats (NTFS, FAT32, exFAT).

### 📁 2. Interactive Folder Explorer (Hierarchical Tree Map)
* Drill down through directory hierarchies sorted dynamically by folder sizes.
* Filter files inside folders by category (Images, Videos, Documents, Executables, etc.).
* Execute inline file manipulations such as bulk renaming or secure deletions directly from the UI.

### 👯 3. Smart Duplicate Finder
* Detect duplicate files on your system using fast size comparison and cryptographic **MD5** hash verification.
* Group duplicate files so you can safely purge redundant clones and reclaim storage space.

### 🗑️ 4. One-Click Safe System Cleanup
* Safely sweep temporary files, cache folders, and Windows Recycle Bin logs.
* The cleanup engine is strictly locked to official Windows OS temp roots to guarantee safety and protect personal user files from deletion.

### 🔔 5. Low Disk Space Windows Alerts
* Automatically sends native Windows toast alerts when a drive's remaining capacity falls below a custom threshold (e.g. less than 10%).

---

## 🚀 Why Choose DiskWise?

* **Native Rust Speed:** The file walking engine is written entirely in multi-threaded Rust, traversing millions of files in seconds without lagging or freezing the desktop window.
* **100% Secure & Private:** DiskWise runs entirely local. Your directory names, file structures, and data paths never leave your machine and are never synced to the cloud.
* **Modern Premium UI:** Features a sleek dark-mode dashboard with interactive charts, smooth micro-animations, and clean navigation—lightyears ahead of standard system utilities.

---

## 💾 Installation Guide (Windows)

To install DiskWise, you do not need to install any programming runtimes (like Node.js or Rust). Simply download the standalone setup package:

1. Open the official **[GitHub Releases](https://github.com/zaa-code/diskwise/releases)** page.
2. Download the latest installer asset:
   `diskwise_0.1.2_x64-setup-new.exe` (or another newer version setup).
3. Run the downloaded `.exe` installer.
4. Review the **Welcome Wizard** and **License Agreement** (the installer features a custom premium Dark Theme).
5. Click **Install** and wait for the wizard to finish.
6. Launch DiskWise from your Desktop shortcut or Windows Start Menu!

---

## 🔄 Automatic OTA Update System

DiskWise features an integrated background update check:
* Head over to **Settings > Software Update** inside the application.
* Click **Check for Updates**.
* The application will contact the release server. If a new version is found, it will automatically download the installer, apply the update, and restart, preserving your preferences.

---

## ✉️ Support & Inquiry
Have feature suggestions, found a bug, or need help? Contact us:
* 📧 **Official Support:** [support@zaaa.qzz.io](mailto:support@zaaa.qzz.io)
* 🐙 **GitHub Issues:** [zaa-code/diskwise/issues](https://github.com/zaa-code/diskwise/issues)
