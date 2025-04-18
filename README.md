# Dell-inspiron-13-7370-Hackintosh
This is a fork of the repository [qiqco/Dell-inspiron-13-7370-Hackintosh](https://github.com/qiqco/Dell-inspiron-13-7370-Hackintosh) by [qiqco](https://github.com/qiqco).

## The original maintainers repository lists the Dell Inspiron 7370 system as follows:

Part | Name
------------ | -------------
CPU | i5-8250U
Model | 06KDFD
RAM | 8GB（2400MHz）
Drive | SN750（500GB）
Graphics | UHD620 ([Intel UHD 620](https://www.intel.com/content/www/us/en/support/products/126789/graphics/processor-graphics/intel-uhd-graphics-family/intel-uhd-graphics-620.html))
Sound | Realtek ALC295
Ethernet | Intel AX200

## Changes in this fork

Originally the Dell Inspiron 7370 came with a different WiFi adapter: Intel AC 7265.
This fork of the original repository updates the following kexts for better compatibility so the AC 7265 works as well.

Item | Kext | Source
------------ | ------------- | -------------
Trackpad | VoodooPS2Controller.kext | https://github.com/acidanthera/VoodooPS2
WiFi | AirportItlwm.kext | https://github.com/OpenIntelWireless/itlwm

## How to use

Follow the instructions at https://dortania.github.io/OpenCore-Install-Guide/installer-guide/linux-install.html#downloading-macos to download the matching __Ventura__ image through macrecovery.py and place the image together with this repo on a USB drive (formatted to FAT32).
