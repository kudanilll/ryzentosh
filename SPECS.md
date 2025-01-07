# System Specification Overview

## Table of Contents

1. [Motherboard](#motherboard)
2. [CPU](#cpu)
3. [GPU](#gpu)
4. [Monitor](#monitor)
5. [Network](#network)
6. [Sound](#sound)
7. [USB Controllers](#usb-controllers)
8. [Input Devices](#input-devices)
9. [Storage Controllers](#storage-controllers)
10. [Bluetooth](#bluetooth)
11. [System Devices](#system-devices)

---

## Motherboard

- **Name:** AXIOO MYBOOK HYPE 7 AMD
- **Chipset:** AMD
- **Platform:** Laptop

---

## CPU

- **Manufacturer:** AMD
- **Processor Name:** AMD Ryzen 7 5700U
- **Codename:** Lucienne
- **Core Count:** 08
- **CPU Count:** 01
- **SIMD Features:** SSE, SSE2, SSE3, SSSE3, SSE4.1, SSE4.2, SSE4a, AVX, AVX2

---

## GPU

### AMD Radeon(TM) Graphics

- **Manufacturer:** AMD
- **Codename:** Lucienne
- **Device ID:** 1002-164C
- **Device Type:** Integrated GPU
- **Subsystem ID:** 80151E50
- **PCI Path:** PciRoot(0x0)/Pci(0x8,0x1)/Pci(0x0,0x0)
- **ACPI Path:** \\_SB.PCI0.GP17.VGA_
- **Resizable BAR:** Disabled

---

## Monitor

### HSD0001

- **Connector Type:** Internal
- **Resolution:** 1920x1080
- **Connected GPU:** AMD Radeon(TM) Graphics

---

## Network

### Realtek 8822CE Wireless LAN 802.11ac PCI-E NIC

- **Bus Type:** PCI
- **Device ID:** 10EC-C822
- **Subsystem ID:** C82210EC
- **PCI Path:** PciRoot(0x0)/Pci(0x2,0x3)/Pci(0x0,0x0)
- **ACPI Path:** \\\_SB.PCI0.GPP5.DEV0

### Remote NDIS based Internet Sharing Device #2

- **Bus Type:** USB
- **Device ID:** 2717-FF88

---

## Sound

### Senary Audio

- **Bus Type:** HDAUDIO
- **Device ID:** 14F1-1F87
- **Subsystem ID:** 14F10393
- **Audio Endpoints:** Speakers
- **Controller Device ID:** 1022-15E3

### AMD High Definition Audio Device

- **Bus Type:** HDAUDIO
- **Device ID:** 1002-AA01
- **Subsystem ID:** 00AA0100
- **Controller Device ID:** 1002-1637

### 2.0 Camera

- **Bus Type:** USB
- **Device ID:** 2EF4-4944
- **Audio Endpoints:** Microphone

---

## USB Controllers

### AMD USB 3.10 eXtensible Host Controller - 1.10 (Microsoft)

- **Bus Type:** PCI
- **Device ID:** 1022-1639
- **Subsystem ID:** 16391022
- **PCI Path:** PciRoot(0x0)/Pci(0x8,0x1)/Pci(0x0,0x3)
- **ACPI Path:** \\\_SB.PCI0.GP17.XHC0

### AMD USB 3.10 eXtensible Host Controller - 1.10 (Microsoft)\_#1

- **Bus Type:** PCI
- **Device ID:** 1022-1639
- **Subsystem ID:** 16391022
- **PCI Path:** PciRoot(0x0)/Pci(0x8,0x1)/Pci(0x0,0x4)
- **ACPI Path:** \\\_SB.PCI0.GP17.XHC1

---

## Input Devices

### HID-compliant touch pad

- **Bus Type:** ACPI
- **Device:** PNP0C50
- **Device Type:** I2C HID Device

### Standard PS/2 Keyboard

- **Bus Type:** ACPI
- **Device:** MSFT0001
- **Device Type:** PS/2

---

## Storage Controllers

### NVMe SSD Controller MAP1202 (DRAM-less)

- **Bus Type:** PCI
- **Device ID:** 1E4B-1202
- **Subsystem ID:** 12021E4B
- **PCI Path:** PciRoot(0x0)/Pci(0x2,0x1)/Pci(0x0,0x0)

---

## Bluetooth

### Realtek Bluetooth Adapter

- **Bus Type:** USB
- **Device ID:** 0BDA-C822

---

## System Devices

### Microsoft ACPI-Compliant Embedded Controller

- **Bus Type:** ACPI
- **Device:** PNP0C09
- **ACPI Path:** \\_SB.PCI0.SBRG.EC0_

### System CMOS/Real Time Clock

- **Bus Type:** ACPI
- **Device:** PNP0B00
- **ACPI Path:** \\\_SB.PCI0.SBRG.RTC0

### Volume Manager

- **Bus Type:** ROOT
- **Device:** VOLMGR

### High Precision Event Timer

- **Bus Type:** ACPI
- **Device:** PNP0103
- **ACPI Path:** \\\_SB.HPET

### PCI Standard Host CPU Bridge

- **Bus Type:** PCI
- **Device ID:** 1022-144D
- **Subsystem ID:** 00000000
- **PCI Path:** PciRoot(0x0)/Pci(0x18,0x5)
- **ACPI Path:** \\\_SB.PCI0.P185

### Microsoft Basic Display Driver

- **Bus Type:** ROOT
- **Device:** BASICDISPLAY

### ACPI Sleep Button

- **Bus Type:** ACPI
- **Device:** PNP0C0E
- **ACPI Path:** \\\_SB.SLPB

### AMD Link Controller Emulation

- **Bus Type:** ROOT
- **Device:** AMDXE

### Microsoft Hypervisor Service

- **Bus Type:** ROOT
- **Device:** HVSERVICE

### AMD GPIO Controller

- **Bus Type:** ACPI
- **Device:** AMDI0030
- **ACPI Path:** \\\_SB.GPIO

### PCI Standard Host CPU Bridge #1

- **Bus Type:** PCI
- **Device ID:** 1022-1449
- **Subsystem ID:** 00000000
- **PCI Path:** PciRoot(0x0)/Pci(0x18,0x1)
- **ACPI Path:** \\\_SB.PCI0.P181

### ACPI Processor Container Device

- **Bus Type:** ACPI
- **Device:** ACPI0010
- **ACPI Path:** \\\_SB.PLTF

### PCI Standard Host CPU Bridge #2

- **Bus Type:** PCI
- **Device ID:** 1022-144A
- **Subsystem ID:** 00000000
- **PCI Path:** PciRoot(0x0)/Pci(0x18,0x2)
- **ACPI Path:** \\\_SB.PCI0.P182

### Microsoft Hyper-V Virtualization Infrastructure Driver

- **Bus Type:** ROOT
- **Device:** VID

### Composite Bus Enumerator

- **Bus Type:** ROOT
- **Device:** COMPOSITEBUS

### Microsoft Virtual Drive Enumerator

- **Bus Type:** ROOT
- **Device:** VDRVROOT

### PCI Standard Host CPU Bridge #3

- **Bus Type:** PCI
- **Device ID:** 1022-1630
- **Subsystem ID:** 16301022
- **PCI Path:** PciRoot(0x0)/Pci(0x0,0x0)
- **ACPI Path:** \\\_SB.PCI0.D003

### ACPI Lid

- **Bus Type:** ACPI
- **Device:** PNP0C0D
- **ACPI Path:** \\\_SB.LID0

### PCI Standard Host CPU Bridge #4

- **Bus Type:** PCI
- **Device ID:** 1022-144F
- **Subsystem ID:** 00000000
- **PCI Path:** PciRoot(0x0)/Pci(0x18,0x7)
- **ACPI Path:** \\\_SB.PCI0.P187

### Programmable Interrupt Controller

- **Bus Type:** ACPI
- **Device:** PNP0000
- **ACPI Path:** \\_SB.PCI0.SBRG.PIC_

### AMD Audio CoProcessor

- **Bus Type:** PCI
- **Device ID:** 1022-15E2
- **Subsystem ID:** 15E21022
- **PCI Path:** PciRoot(0x0)/Pci(0x8,0x1)/Pci(0x0,0x5)
- **ACPI Path:** \\_SB.PCI0.GP17.ACP_

### UMBus Root Bus Enumerator

- **Bus Type:** ROOT
- **Device:** UMBUS

### Charge Arbitration Driver

- **Bus Type:** ROOT
- **Device:** CAD

### PCI Standard ISA Bridge

- **Bus Type:** PCI
- **Device ID:** 1022-790E
- **Subsystem ID:** 790E1022
- **PCI Path:** PciRoot(0x0)/Pci(0x14,0x3)
- **ACPI Path:** \\\_SB.PCI0.SBRG

### High Definition Audio Bus

- **Bus Type:** PCI
- **Device ID:** 1002-1637
- **Subsystem ID:** 16371002
- **PCI Path:** PciRoot(0x0)/Pci(0x8,0x1)/Pci(0x0,0x1)
- **ACPI Path:** \\\_SB.PCI0.GP17.HDAU

### PCI Standard Host CPU Bridge #5

- **Bus Type:** PCI
- **Device ID:** 1022-144C
- **Subsystem ID:** 00000000
- **PCI Path:** PciRoot(0x0)/Pci(0x18,0x4)
- **ACPI Path:** \\\_SB.PCI0.P184

### System Board

- **Bus Type:** ACPI
- **Device:** PNP0C01
- **ACPI Path:** \\\_SB.PCI0.AMDN

### Microsoft Windows Management Interface for ACPI

- **Bus Type:** ACPI
- **Device:** PNP0C14
- **ACPI Path:** \\_SB.AOD_

### PCI Express Root Complex

- **Bus Type:** ACPI
- **Device:** PNP0A08
- **ACPI Path:** \\\_SB.PCI0

### PCI Standard Host CPU Bridge #6

- **Bus Type:** PCI
- **Device ID:** 1022-1448
- **Subsystem ID:** 00000000
- **PCI Path:** PciRoot(0x0)/Pci(0x18,0x0)
- **ACPI Path:** \\\_SB.PCI0.P180

### High Definition Audio Controller

- **Bus Type:** PCI
- **Device ID:** 1022-15E3
- **Subsystem ID:** 039314F1
- **PCI Path:** PciRoot(0x0)/Pci(0x8,0x1)/Pci(0x0,0x6)
- **ACPI Path:** \\\_SB.PCI0.GP17.AZAL

### Microsoft ACPI-Compliant System

- **Bus Type:** ACPI_HAL
- **Device:** PNP0C08

### Microsoft Basic Render Driver

- **Bus Type:** ROOT
- **Device:** BASICRENDER

### Microsoft UEFI-Compliant System

- **Bus Type:** ACPI_HAL
- **Device:** UEFI

### ACPI Fixed Feature Button

- **Bus Type:** ACPI
- **Device:** FIXEDBUTTON

### Motherboard Resources

- **Bus Type:** ACPI
- **Device:** PNP0C02
- **ACPI Path:** \\\_SB.PCI0.IOMA

### Motherboard Resources #1

- **Bus Type:** ACPI
- **Device:** PNP0C02
- **ACPI Path:** \\\_SB.AWR0

### System Timer

- **Bus Type:** ACPI
- **Device:** PNP0100
- **ACPI Path:** \\_SB.PCI0.SBRG.TMR_

### Microsoft Windows Management Interface for ACPI #1

- **Bus Type:** ACPI
- **Device:** PNP0C14
- **ACPI Path:** \\\_SB.WMIB

### PCI Standard Host CPU Bridge #7

- **Bus Type:** PCI
- **Device ID:** 1022-144E
- **Subsystem ID:** 00000000
- **PCI Path:** PciRoot(0x0)/Pci(0x18,0x6)
- **ACPI Path:** \\\_SB.PCI0.P186

### ACPI Power Button

- **Bus Type:** ACPI
- **Device:** PNP0C0C
- **ACPI Path:** \\\_SB.PWRB

### PCI Standard Host CPU Bridge #8

- **Bus Type:** PCI
- **Device ID:** 1022-1632
- **Subsystem ID:** 00000000
- **PCI Path:** PciRoot(0x0)/Pci(0x1,0x0)
- **ACPI Path:** \\\_SB.PCI0.P010

### PCI Standard Host CPU Bridge #9

- **Bus Type:** PCI
- **Device ID:** 1022-1632
- **Subsystem ID:** 00000000
- **PCI Path:** PciRoot(0x0)/Pci(0x2,0x0)
- **ACPI Path:** \\\_SB.PCI0.P020

### PCI Standard Host CPU Bridge #10

- **Bus Type:** PCI
- **Device ID:** 1022-1632
- **Subsystem ID:** 00000000
- **PCI Path:** PciRoot(0x0)/Pci(0x8,0x0)
- **ACPI Path:** \\\_SB.PCI0.P080

### AMD Crash Defender

- **Bus Type:** ROOT
- **Device:** AMDLOG

### NDIS Virtual Network Adapter Enumerator

- **Bus Type:** ROOT
- **Device:** NDISVIRTUALBUS

### AMD I2C Controller

- **Bus Type:** ACPI
- **Device:** AMDI0010
- **ACPI Path:** \\\_SB.I2CD

### PCI Express Root Port

- **Bus Type:** PCI
- **Device ID:** 1022-1635
- **Subsystem ID:** 16351022
- **PCI Path:** PciRoot(0x0)/Pci(0x8,0x1)
- **ACPI Path:** \\\_SB.PCI0.GP17

### PCI Standard Host CPU Bridge #11

- **Bus Type:** PCI
- **Device ID:** 1022-144B
- **Subsystem ID:** 00000000
- **PCI Path:** PciRoot(0x0)/Pci(0x18,0x3)
- **ACPI Path:** \\\_SB.PCI0.P183

### Motherboard Resources #2

- **Bus Type:** ACPI
- **Device:** PNP0C02
- **ACPI Path:** \\\_SB.PCI0.S900

### System Speaker

- **Bus Type:** ACPI
- **Device:** PNP0800
- **ACPI Path:** \\\_SB.PCI0.SBRG.SPKR

### Microsoft System Management BIOS Driver

- **Bus Type:** ROOT
- **Device:** MSSMBIOS

### Microsoft Windows Management Interface for ACPI #2

- **Bus Type:** ACPI
- **Device:** PNP0C14
- **ACPI Path:** \\\_SB.AMW0

### Motherboard Resources #3

- **Bus Type:** ACPI
- **Device:** PNP0C02
- **ACPI Path:** \\\_SB.PCI0.GP17.APSP

### PCI Express Root Port #1

- **Bus Type:** PCI
- **Device ID:** 1022-1634
- **Subsystem ID:** 14531022
- **PCI Path:** PciRoot(0x0)/Pci(0x2,0x1)
- **ACPI Path:** \\\_SB.PCI0.GPP3

### PCI Express Root Port #2

- **Bus Type:** PCI
- **Device ID:** 1022-1634
- **Subsystem ID:** 14531022
- **PCI Path:** PciRoot(0x0)/Pci(0x2,0x3)
- **ACPI Path:** \\\_SB.PCI0.GPP5

### AMD SMBus

- **Bus Type:** PCI
- **Device ID:** 1022-790B
- **Subsystem ID:** 790B1022
- **PCI Path:** PciRoot(0x0)/Pci(0x14,0x0)
- **ACPI Path:** \\\_SB.PCI0.D021

### Plug and Play Software Device Enumerator

- **Bus Type:** ROOT
- **Device:** SYSTEM

### Remote Desktop Device Redirector Bus

- **Bus Type:** ROOT
- **Device:** RDPBUS

### Direct Memory Access Controller

- **Bus Type:** ACPI
- **Device:** PNP0200
- **ACPI Path:** \\\_SB.PCI0.SBRG.DMAD
