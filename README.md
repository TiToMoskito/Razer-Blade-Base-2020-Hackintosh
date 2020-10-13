<img align="right" src="https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced/blob/master/IMG/opencore_logo.png" alt="OpenCore" width="225">

# Hackintosh for Razer Blade Base 2020 15
![MODEL](https://img.shields.io/badge/MODEL-RZ09--0328x-green)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)


#### Developer: TiToMoskito
#### Don't forget to star this project if you like it! 
#### READ THE ENTIRE README.MD BEFORE YOU TAKE ANY ACTION.


## Disclaimer
* Note that by using any file or code in this repository you agree to this disclaimer.
* This project is issued under the [MIT License](https://opensource.org/licenses/MIT) provided as-is, can potentially brick your machine, and may break your warranty. I am not responsible for any damage that is caused by you using anything in this Repo.

## Update

##### Changelog
* [20201013] Initial upload

## Help Needed
* Thunderbolt is not working. I tested a eGPU.
* If anyone know anything about Titan Ridge Thunderbolt 3 on OpenCore feel free to open an issue! 

## System Information
| Part | Compatibility | Model | 
| --- | --- | --- |
| Machine | Functional | Razer Blade 15 Base 2020 RZ09-0328x |
| macOS | Functional | macOS 10.15.7 Catalina |
| BIOS | Functional | 1.03 |
| CPU | Functional | Intel® Core™ i7-10750H |
| RAM | Functional | Micron 16GB DDR4 2666GHz SODIMM |
| SSD | Functional | Sabrent 1TB Rocket NVMe M.2 SSD |
| iGPU | Functional | Intel® UHD Graphics 630 2048MB GT2 |
| Wi-Fi | Functional | Broadcom BCM94360CS2 802.11AC with NGFF Adapter |
| Bluetooth | Functional | Broadcom 20702 Bluetooth 4.0 |
| Webcam | Functional | Integrated 720P Camera |
| Trackpad | Functional | ELAN 0406 I2C HID |
| Microphone | Functional | Integrated Dual-Array Microphone |
| Internal Sound Card | Functional | Realtek ALC |
| Thunderbolt 3 Chipset | Unfunctional | Intel JHL7540 Titan Ridge 2C 2019 (15E8) |
| Thunderbolt 3 Controller | Unfunctional | Razer Core X |
| External GPU | Unfunctional | SAPPHIRE RX 5700 XT 8GB GDDR6|
| Discrete GPU | Disabled | NVIDIA RTX 2070 Max-Q 8GB GDDR6 |
  
### OpenCore
* Currently running: 0.6.2
* [The Vanilla Laptop Guide](https://1revenger1.gitbook.io/laptop-guide/): OpenCore laptop guide and documentation.

### BIOS
* I strongly recommend following the steps from [Razer Blade 15 Advanced (Mojave and Catalina)](https://github.com/stonevil/Razer_Blade_Advanced_early_2019_Hackintosh) to modify your BIOS.
* Note that using other people's BIOS is generally a really, really bad idea. It WILL possibly block your machine.

### Windows
##### Drivers
* Wifi + Bluetooth (BCM94360CS2): [Apple Bootcamp Wifi + Bluetooth Drivers](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v943602CS.1)
      
## Other Configurations:
| Owner | CPU | Model | Bootloader | Link |
| --- | --- | --- | --- | --- |
| stonevil | i7-8750H | RZ09-0288 | Clover | [Link](https://github.com/stonevil/Razer_Blade_Advanced_early_2019_Hackintosh)
| boyuanx | i7-9750H | RZ09-0301 | OpenCore | [Link](https://github.com/stonevil/Razer_Blade_Advanced_early_2019_Hackintosh/issues/23#issuecomment-629762916) |
| Errrneist | i7-9750H | RZ09-0301 | OpenCore | [Link](https://github.com/Errrneist/Hackintosh-Razer-Blade-RZ09-0301) |

## Contributors
* Note: There is no order in the ranking of names. 
* This list may not be complete! Feel free to let me know. Sorry for any inconvience.

| Name | Contributions |
| --- | --- |
| [Rehabman](https://github.com/RehabMan) | Many kernel extensions and guides. |
| [Acidanthera](https://github.com/acidanthera) | OpenCore, Lilu.kext, and WhateverGreen.kext. |
| [Jack Boyuan Xu](https://github.com/boyuanx) | OpenCore [solution](https://github.com/stonevil/Razer_Blade_Advanced_early_2019_Hackintosh/issues/23#issuecomment-629762916). |
| [Myroslav Rys](https://github.com/stonevil) | Clover portion and BIOS modification. |
| [Avery Black](https://github.com/1Revenger1) | OpenCore Laptop Guide |
| [Alex James](https://github.com/al3xtjames) | TbtForcePower.efi |