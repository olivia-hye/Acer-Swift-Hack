# OpenCore 0.9.6 - Acer Swift X - Ryzen 7 5800U

## Made for archive and educational purposes

[![BIOS](https://img.shields.io/badge/BIOS-1.07-important.svg)]([https://www.dell.com/support/home/en-us/product-support/product/inspiron-13-5370-laptop/drivers](https://www.acer.com/us-en/support/product-support/SFX14-41G/downloads))
[![OpenCore 
Version](https://img.shields.io/badge/OpenCore-0.9.6-cyan?style=default&logo=osano&logoColor=0298e1&color=3f4451
)](https://github.com/acidanthera/OpenCorePkg/releases/latest)
[![macOS 
Sonoma](https://img.shields.io/badge/macOS-14.2.1%20(23C71)-white.svg?logo=apple)](https://www.apple.com/macos/sonoma/)



## Specs

| Component      | Brand                                     |
|----------------|-------------------------------------------|
| **CPU**        | `AMD Ryzen 7 5800U @ 1.9 GHz`             |
| **iGPU**       | `AMD Radeon Vega 8`                       |
| **Storage**    | `Western Digital SN750 Black NVMe 512GB`  |
| **Audio Code** | `Realtek ALC255`                          |
| **WiFi Card**  | `Mediatek MT7921`                         |
| **OS**         | `macOS Sonoma 14.2.1 (23C71)`             |
| **BIOS**       | `v1.07`                                   |

## Supported versions

| Version 	| Supported 	|
|---	|---	|
| macOS High Sierra 10.13.x 	| :heavy_exclamation_mark: No iGPU Support	|
| macOS Mojave 10.14.x 	| :heavy_exclamation_mark: No iGPU Support 	|
| macOS Catalina 10.15.x 	| :white_check_mark: 	|
| macOS Big Sur 11.x 	| :white_check_mark: 	|
| macOS Monterey 12.x 	| :white_check_mark: 	|
| macOS Ventura 13.x 	| :white_check_mark: 	|
| macOS Sonoma 14.x 	| :white_check_mark: 	|


### Working/Not working:

###### Click on the arrow icons to expand the spoilers
<details>
<summary>iGPU</summary>
  
- [x] Backlight support
- [x] HDMI1.4b Output (1920x1080@120Hz)
- [x] Type-C to HDMI Output
- [x] H264 & HEVC
- [ ] VP9 & AV1
</details>

<details>
<summary>Audio</summary>
  
- [x] Internal Speakers
- [x] Internal Microphone
- [x] Combojack Headphones
- [ ] Combojack Microphone
- [x] HDMI Audio Output
- [x] Type-C to HDMI Audio Output
</details>

<details>
<summary>USB</summary>
  
- [x] All USB ports working and mapped
- [x] Webcam (USB based)
</details>

<details>
<summary>Keyboard</summary>
  
- [x] Keyboard (PS2 based)
- [x] F3 & F4 brightness keys
- [x] Print Screen key
- [x] Multimedia control sound keys
</details>

<details>
<summary>Trackpad</summary>
  
- [x] I2C Touchpad with gestures
- [x] Force Touch
</details>


<details>
<summary>Misc</summary>
  
- [ ] Sleep/Wake
- [ ] Fingerprint
- [x] SATA/NVMe PCIe Gen3x4 on M.2 slot
- [x] Sensors CPU, iGPU, Battery, NVMe, Fans
- [x] Native ACPI Battery 8-bit support
- [x] Native NVRAM support
- [x] Recovery (macOS) boot from OpenCore
- [x] Windows 10/Linux boot from OpenCore
- [x] macOS Continuity Camera
</details>

