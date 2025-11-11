# T495S-Hackintosh
This repo contains my EFI made for the Lenovo T495S Sequoia 15.3.1 Hackintosh

<img width="324" height="514" alt="image" src="https://github.com/user-attachments/assets/09639efe-32bd-4855-84b4-680c46cefaaa" />

## Opencore version
Opencore V 1.0.5 by Acidanthera

## Kext list
| Kext | Version |
|--|--|
| AMDRyzenCPUPowerManagement.kext | 0.7.2 |
| AppleALC | 1.9.6 |
| AppleMCEReporterDisabler | NA |
| BrightnessKeys | 1.0.3 |
| ECEnabler | 1.0.6 |
| Forgedinvariant | 1.2.0 |
| IntelBluetoothFirmware | 2.4.0 |
| IntelBTPatcher | NA |
| Itlwm | 2.3.0 |
| Lilu | 1.7.1 |
| NootedRed | 1.0.0 nightly |
| NVMeFix | 1.1.3 |
| RealtekRTL8111 | 2.5.0 |
| SMCAMDProcessor | 0.7.2 |
| SMCBatteryManager | 1.3.7 |
| SMCRadeonSensors | 2.3.1 |
| USBToolBox | 1.2.0 |
| VirtualSMC | 1.3.7 |
| VoodooI2C | 2.9.1 |
| VoodooI2CELAN | NA |
| VoodooPS2Controller | 2.3.7 |

## SMBIOS Generation
SMBIOS is **not** already included in **config.plist** .
In order to generate one (alongside with the other parameters necessary) use the following tool: **GenSMBIOS** by CorpNewt, Torsten [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

## SSDT Generation
SSDTs have been generated using SSDTTime tool by CorpNewt, im-not-a-dev, Izhoang2801 [SSDTTime](https://github.com/corpnewt/SSDTTime)

## Drivers
Drivers refer to Dortania [guide](https://dortania.github.io/OpenCore-Install-Guide/ktext.html#firmware-drivers)

## What's working
* Touchpad - keyboard
* Audio
* Wifi
* Brightness leveling (using [BetterDisplay](https://github.com/waydabber/BetterDisplay) app)
* Trackball
* Touchpad keys
* USBs
* Webcam
* Microphone

## What's not working
* Bluetooth
* You tell me

> Use of macOS and all Apple software (including apps and services) constitutes full acceptance of and strict adherence to Apple Inc.'s current Terms of Service (ToS) and End-User License Agreements (EULA). The user is solely responsible for compliance.
