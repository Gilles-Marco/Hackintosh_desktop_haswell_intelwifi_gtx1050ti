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