## MacOS version

Tested on High Sierra 10.13.6

Nvidia drivers for GTX 10XX series are only available on High Sierra see https://dortania.github.io/OpenCore-Install-Guide/macos-limits.html#gpu-support

## Devices

| Specifications | Details |
|:---|:---|
| CPU | Intel Core i5-4460 |
| Memory | DDR3 16 GB |
| SATA SSD | Samsung 1TB + Crucial 500 GB |
| Discrete Graphics | GTX 1050 Ti |
| Ethernet | Intel i218V2 |
| Wireless/Bluetooth Card | Intel AC8260 |

## Nvidia drivers

https://www.insanelymac.com/forum/topic/324195-nvidia-web-driver-updates-for-macos-high-sierra-update-nov-13-2020/

Take the one compatible with High Sierra 10.13.6 (17G14042)

## Wifi configuration

Intel wifi's driver itlwm is recognized as an ethernet interface so no wifi icon will be displayed by default.

For the first connection you will need to configure itwm/Info.plist with your wifi SSID and password in the WiFiConfig section.

It will then automatically connect to wifi.

To have the wifi icon in the menu bar you have to install Heliport.

# Tools

## MountEFI

To mount post-install the macOS' EFI partition to copy the EFI directory's repo into, to be able to boot without the USB stick.

## Heliport

To install post-install to have a wifi icon displayed in the menu bar

# Installation guide

See opencore installation guide https://dortania.github.io/OpenCore-Install-Guide/

This repo cover the following steps :
- Addind the base opencore files
- Gathering files
- Getting started with ACPI
- config.plist Setup

Getting the MacOS Base Image, USB Creation, Installation, Troubleshooting and Post-Install are up to you.

Feel free to double check my work with the OpenCore installation guide listed above, I provide no guarantee and this software can potentially cause hardware damage or data loss. I deny all responsibilities, do it at your own risk.

This repo may also be out of date and may not use the best pratice available when you do the installation.

# Credit

See OpenCore credits https://dortania.github.io/OpenCore-Install-Guide/misc/credit.html

Credits to https://github.com/OpenIntelWireless for the intel wifi driver

# License

Software under CC BY-NC-SA 4.0 license distributed as is and providing no guarantee, use at your own risk.

See also https://dortania.github.io/OpenCore-Install-Guide/LICENSE.html

