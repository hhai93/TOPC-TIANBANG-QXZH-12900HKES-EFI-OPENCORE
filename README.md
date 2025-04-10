# TOPC-TIANBANG-QXZH-12900HKES-EFI-OPENCORE

![GitHub](https://img.shields.io/badge/license-MIT-blue.svg) ![GitHub last commit](https://img.shields.io/github/last-commit/hhai93/TOPC-TIANBANG-QXZH-12900HKES-EFI-OPENCORE)[![OpenCore Version](https://img.shields.io/badge/OpenCore-1.0.3-brightgreen.svg)](https://github.com/acidanthera/OpenCorePkg)

A prebuilt OpenCore EFI configuration tailored for the **TOPC/TIANBANG QXZH** motherboard with Intel 12900HK-ES, designed to run macOS seamlessly.

---

![IMG_0473](https://github.com/user-attachments/assets/874e316e-53c2-4ac0-b477-059a1a867967)  

---

## System Specifications

| Component         | Details                             |
|-------------------|-------------------------------------|
| **Motherboard**   | TOPC/TIANBANG QXZH (Intel 12900HK-ES MODT) |
| **GPU**           | Sapphire Pulse RX 6600             |
| **RAM**           | Corsair 2x16GB @ 2133MHz           |
| **Wi-Fi**         | Intel AX201 (requires OpenCore Legacy Patcher) |
| **Bootloader**    | OpenCore 1.0.3                     |
| **macOS Version** | Sequoia 15.1.1                     |

---

## Features
- Fully functional OpenCore EFI for macOS installation and booting.

---

## Installation Notes
1. Download the EFI folder from this repository.
2. Mount your EFI partition and replace the existing EFI folder with this one.
3. **Important**: Generate and replace the following unique identifiers:
   - Serial Number
   - MLB
   - UUID
   - ROM
4. Boot into macOS and enjoy!

> **Tip**: Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to generate your own system-specific identifiers.

## Prerequisites
- A compatible USB drive for creating the macOS installer.
- Basic knowledge of OpenCore and macOS Hackintosh setup.
- OpenCore Legacy Patcher for Wi-Fi functionality (if using Intel AX201).
