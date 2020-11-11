# Overview
This repo will help you install Mac OS X for Dell vostro 5471 machine with some modifications to get most benefit from the system  
here I will attache my EFI partition with continue updates (I hope😅)  
I was working with Hackintosh since OS X 10.8 Mountain Lion with many computers.\
i include the latest Kext until ( 11 / 11 / 2020 )

![Screen shot for my system](https://raw.githubusercontent.com/almodroid/Dell-vostro-5471-hackintosh/main/Screenshot2.png)
![Performance](https://raw.githubusercontent.com/almodroid/Dell-vostro-5471-hackintosh/main/Screenshot1.png)
## What is working :
 1. Full Graphics (with Disabling external Gpu)
 2. Cpu and Power mangment
 3. Audio
 4. USB mapping and functionality
 5. Type c
 6. Trackpad + keyboard (using voodoo ps2 and i2c with Xosi patch and ssdt) 
 7.  keyboard remapping with fix for brightness keys and prtscr (screenshot F13)
 8.  webcam 
 9. Bluetooth (using BrcmPatchRam) 
 10. Wifi (using aspm disable and AirPortBrcmFixup)
 11. HDMI audio and Edid scan and patch RGB using Hackintool app
 12. Battery and sensors
 13. Backlight

## What is not working 
None! until now

## Some details :

1. for Wifi and Bluetooth I purchased native apple Broadcom card ( Dw1820a )
from aliexpress for 7$.
   
   ![enter image description here](https://osxlatitude.com/uploads/monthly_2019_05/DW1820A_CN-08PKF4.jpg.2f57e855741f3797816a71423155cbde.jpg)
 
 one important thing you need to do is disable aspm using device section ( at opencore config.plist already did it)
 *no need to cover any pins or any kind of hardware fix **only software**.

I found somewhere that the original intel card for this device can be patched to work under Mac OS X ( not sure )

2. for USB and EC
 
**Credits:** 
Apple for the beautiful System.
[Acidanthera](https://github.com/acidanthera), [Rehabman](https://github.com/RehabMan) and [Daliansky](https://github.com/daliansky) for thier hard work . 

I hope it will be helpful .
Good luck and thank you 👍.
*Almodroid*
