# OpenCore EFI for Axioo HYPE 7 AMD

My documentation for dual booting Windows 11 with macOS Sequoia on [Axioo HYPE 7 with AMD Ryzen™ 7-5700U](https://www.axiooworld.com/hype7-amd)

![Screenshot](/screenshot.png?raw=true "Screenshot image")

## Devices Specifications

- **Processor:** AMD Ryzen 7-5700U (Lucienne)
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
- **Mac Version:** [macOS Sequoia 15.2](https://dortania.github.io/OpenCore-Legacy-Patcher/SEQUOIA-DROP.html)

See more using [Hardware Sniffer](SPECS.md)

### What is working?

- **WiFi:** (Tp-Link Archer T2UB Nano Bluetooth 4.2 Wireless Adapter AC600 usb Adapter)
- **Camera**
- **Microphone**
- **iGPU**
- **Sleep**

### What is not working?

**Unsupported devices:**

- **Wi-Fi & Bluetooth:** Realtek 8822CE Wireless LAN 802.11ac PCI-E NIC
- **Sound:** Senary Audio (Speakers)
- **VDA Decoder:** Failed
- **Card reader:** Unpatched

### Notes

- **Disclaimer:** Use this documentation at your own risk. I am not responsible for any damage or data loss.
- **SMBIOS Configuration:** Ensure you generate unique SMBIOS values for your system. Avoid copying the `config.plist` values directly.

## Prerequisite

- **USB Drive**
  - Minimum 32GB for install Sequoia
  - You can use a 16GB USB drive, but it's not enough to install Sequoia, you can use Sonoma or something older
- **Image File**
  - [Sequoia 15.2](https://etechbox.com/download/macos-sequoia-installer/) (16.76 GB)
  - [Sonoma 14.4.1](https://etechbox.com/download/macos-sonoma-hackintosh/) (14.90 GB)
- **Tools**
  - plist editor, you can use [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) or [ProperTree](https://github.com/corpnewt/ProperTree)
  - [USBToolBox](https://github.com/USBToolBox/tool/releases/tag/0.2) for generate UTBMap.kext
  - [Balena Etcher](https://etcher.balena.io/#download-etcher) for flash OS images to USB Drive
- **Update all drivers on your device to the latest version**
  - Go to this [link](https://www.axiooworld.com/driver), then enter your part number.

## Getting Started

First step, clone this repo:

```bash
$ git clone https://github.com/achmaddaniel24/ryzentosh.git ryzentosh
$ cd ryzentosh
```

### USB Mapping

### Generate SMBIOS

### Create USB Installer

### Create new partition for macOS

### Modify BIOS Settings

### Installing macOS

### Post-Intall

## Credits

Special thanks to:

- [Acidanthera](https://github.com/acidanthera/)
- [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [Everything Tech](https://www.youtube.com/@teema.everythingtech)
- All developers

## Support

If you like my work, you can [buy me a coffee](https://www.buymeacoffee.com/kudanil) and share your thoughts 🎉 ☕
