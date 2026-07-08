# 📱 Light Kernel for POCO M4 5G (light)

A clean, stable, and completely unmodified custom kernel built straight from the official source code for the POCO M4 5G (`light`). This repository aims to provide a pure stock experience with maximum stability and zero modifications.

## 💻 Supported Devices
* **POCO M4 5G** (light / thunder)
* **Redmi Note 11R** (light)
* **Redmi 11 Prime 5G** (light)

## ✨ Features
* **100% Stock and Unmodified source base.**
* Built from the official Xiaomi repository branch: `light-u-oss`.
* No system modifications, no forced root, absolute stability.
* Compiled using standard GCC toolchains.

## 📥 Installation (Fastboot)

### Prerequisites
* An unlocked bootloader.
* Android platform tools (`fastboot`) installed on your PC.

### Steps
1. Download the compiled `boot.img` from the [Releases](https://github.com/yadavmandeep8899-wq/light-kernel/releases) or Actions artifacts.
2. Reboot your device into Fastboot mode (Power + Volume Down).
3. Connect your phone to the PC via USB.
4. Open your terminal/cmd and flash the image using:
   ```bash
   fastboot flash boot boot.img
   fastboot reboot
​Base Source: MiCode/Xiaomi_Kernel_OpenSource
​Maintained by: **Mandeep Yadav**
