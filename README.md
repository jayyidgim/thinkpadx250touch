# Thinkpad x250 Touchscreen Big Sur OpenCore 0.6.7
EFI Hackintosh macOS Big Sur 11.2.1 Build 20D75 for Lenovo Thinkpad X250 Touchscreen

[![macOS](https://img.shields.io/badge/macOS-11.2.1-blue)](https://developer.apple.com/documentation/macos-release-notes)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.6.7-green)](https://github.com/acidanthera/OpenCorePkg)
[![ThinkPad](https://img.shields.io/badge/ThinkPad-X250-orange)](https://think.lenovo.com.cn/index.html)

**Disclaimer**
This repo is made for backup purpose of my laptop-Lenovo Thinkpad X250-20CL

## Lenovo Thinkpad X250-20CL Specifications
```
- Processor : Intel Core i5 5300U
- IGPU : Intel HD Graphics 5500
- RAM : 8GB DDR3 PC12800 (1600Mhz)
- Storage : 1x Team SSD 256GB
- Wifi : Intel 7265 + Bluetooth
- Audio : Realtek ALC292 (alcid = 32)
- Ethernet : Intel I218LM3 Gigabit Ethernet
- Touchpad : Synaptic PS2 Interface
- Touchscreen : Yes
- Boot Mode : UEFI GPT
- Screen Size : 12.5"
- Display Resolution : HD (1366 x 768)
- Bootloader : OpenCore r0.6.7
- OS Version : macOS Big Sur 11.2.1 Build 20D75
```

## Stats
- QE/CI Graphics Intel HD 5500
- CPU Power Management
- Restart, Sleep and Shutdown
- Internal Speaker, Internal Microphone
- Combo Jack noise fixed by using ALCPlugFix, with CodecCommander kext
- Touchpad, with multitouch
- Touchscreen, use it as screen-touchpad
- Brightness
- FN + Brightness Button Up / Down
- Battery Percentage
- Ethernet (Not tested yet)
- Wifi, witih AirportItlwm.kext sometimes buggy after wake from sleep
- Mini Display Out, working flawelessly XD
- Mini Display Audio, not tested
- All USB Port
- SDCard, not detect
