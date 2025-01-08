# OpenCore EFI for Axioo HYPE 7 AMD

My documentation for dual booting Windows 11 with macOS Sequoia on [Axioo HYPE 7 with AMD Ryzen™ 7-5700U](https://www.axiooworld.com/hype7-amd)

## Devices Specifications

- **Processor:** AMD Ryzen 7-5700U
- **Graphic:** AMD Radeon RX Vega 8
- **RAM:** 16GB (8x2) DDR4-3200MHz
- **Storage:** 512GB M.2 NVMe PCIe Gen 3x4
- **Drive Model:** SDVPNV2310512TMSB5HK
- **Wi-Fi & Bluetooth:** Realtek RTL8822CE (Not Supported)
- **Ethernet:** None
- **Audio:** Conexant SN6140 (Not Supported?)
- **Touchpad:** I2C Interface
- **Keyboard:** Standard PS/2 Keyboard
- **USB:** AMD Chipset 3.1
- **Boot Mode:** UEFI
- **Bootloader:** [OpenCore 1.0.3](https://github.com/acidanthera/OpenCorePkg)
- **Mac Version:** [macOS Sequoia 15](https://dortania.github.io/OpenCore-Legacy-Patcher/SEQUOIA-DROP.html)

[See more using 'Hardware Sniffer'](SPECS.md)

### What is working?

### What is not working?

**Unsupported devices:**

- **Wi-Fi & Bluetooth:** Realtek 8822CE Wireless LAN 802.11ac PCI-E NIC
- **Sound:** Senary Audio (Speakers)

### Notes

Use at your own risk. I take no responsiblity if your rig explodes. Create unique SMBios values for your rig. Don't copy ones shown in the config.plist

## Prerequisite

- **USB Drive**
  - Minimum 32GB for install Sequoia
  - You can use a 16GB USB drive, but it's not enough to install Sequoia, you can use Sonoma or something older
- **Image File**
  - [Sequoia 15](https://etechbox.com/download/macos-sequoia-installer/) (16.76 GB)
  - [Sonoma 14.4.1](https://etechbox.com/download/macos-sonoma-hackintosh/) (14.90 GB)
- **Tools**
  - plist editor, you can use [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) or [ProperTree](https://github.com/corpnewt/ProperTree)
- **Update all drivers on your device to the latest version**
  - Go to this [link](https://www.axiooworld.com/driver), then enter your part number.

## Getting Started

First step, clone this repo:

```bash
$ git clone https://github.com/achmaddaniel24/ryzentosh.git ryzentosh
$ cd ryzentosh
```

### Create USB Installer

### Create new partition for macOS

## Credits

## Support

If you like my work, you can [buy me a coffee](https://www.buymeacoffee.com/kudanil) and share your thoughts 🎉 ☕
