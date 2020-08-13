# OpenCore Bootloader for ACER E5-573
macOS Catalina Guide for Intel 5th Gen Laptop

# Laptop Specs:

CPU: intel i5 5200U 2.2 Ghz
Graphics: intel HD 5500
Ram: 4 GB
Wifi: Qualcomm Atheros QCA9377


# EFI Version: 

OpenCore UEFI - 0.6.0


# Create Bootable:

1. Download macOS Catalina 10.15.3 Image from https://www.olarila.com/topic/6278-new-vanilla-olarila-images/
2. Flash image to USB Drive by balenaEtcher
3. Replace EFI Folder with the one in this repository.

# Install MacOS Catalina:

1. Follow the guide from Olarila website
2. In case of any error while installing, block all kext in Clover bootloader except Vodoo Keyboard and USB. You will need usb mouse for the installation.
3. You can block selected kext by pressing spacebar after selecting install select Catalina in Clover Bootloader
4. After installing the OS and setting up , you don't need to disable any kext.

# Post Installation:

1. Copy EFI Folder to the EFI partition in the HDD.
2. Install HorNDIS for USB Tethering / USB Wifi Adapter


# Whats woriking: 

1. USB 3.0 and 2.0
2. Trackpad (partially) 
3. Keyboard (All Fns like brightness, volume)
4. Bluetooth
5. Full Hardware Acceleration in Graphics
6. Ethernet
7. Audio

# Not Working:

1. Camera
2. Wifi
3. Battery Info


