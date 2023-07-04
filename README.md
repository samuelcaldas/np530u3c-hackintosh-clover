# np530u3c Hackintosh Clover

This repository contains the files and instructions to install macOS Mojave on a Samsung NP530U3C-A02RU laptop using Clover bootloader.

## Features

- Everything works, including audio, wifi, bluetooth, graphics, battery, trackpad, keyboard, etc.
- AppleBacklightInjector.kext for brightness control
- EFI folder with Clover configuration and kexts

## Installation

- Follow the guide from [tonymacx86](https://www.tonymacx86.com/threads/samsung-np530u3c-a02ru-el-capitan-works-everything.201650) to create a bootable USB installer and install macOS Mojave on the laptop
- Copy the EFI folder from this repository to the EFI partition of the USB installer and the laptop's SSD
- Copy the AppleBacklightInjector.kext to /Library/Extensions on the laptop's SSD and rebuild the kext cache
- Enjoy your hackintosh!

## Credits

- Thanks to [samuelcaldas](https://github.com/samuelcaldas) for creating this repository and sharing his files
- Thanks to [RehabMan](https://github.com/RehabMan) for his guides and kexts
- Thanks to [tonymacx86](https://www.tonymacx86.com) community for their support and resources
