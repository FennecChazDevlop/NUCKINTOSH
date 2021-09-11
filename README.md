
# Nuckintosh 8th generation ( Model Nuc8I3BEH ) 

### INDEX

>---
>
> ####  > - [Introduction](https://github.com/FennecChazDevlop/NUCKINTOSH#nuckintosh-8th-generation--model-nuc8i3beh-)
> ####  > - [Ebay Link's](https://github.com/FennecChazDevlop/NUCKINTOSH#you-can-buy-one-in-here)
> ####  > - [Getting Started](https://github.com/FennecChazDevlop/NUCKINTOSH#getting-started)
> ####  > - [Prepare Machine ( BIOS UPDATE ) ](https://github.com/FennecChazDevlop/NUCKINTOSH#prepare-machine--bios-update-)
> ####  > - [Prepare Machine ( BIOS Configuration )](https://github.com/FennecChazDevlop/NUCKINTOSH#prepare-machine--bios-configuration-)
> ####  > - [Prepare USB](https://github.com/FennecChazDevlop/NUCKINTOSH#prepare-usb)
> ####  > - [Installation](https://github.com/FennecChazDevlop/NUCKINTOSH#installation)
> ####  > - [Post-Install](https://github.com/FennecChazDevlop/NUCKINTOSH#post-install)
> ####  > - [Fix iservices and icloud](https://github.com/FennecChazDevlop/NUCKINTOSH#fix-iservices-and-icloud)
> ####  > - [Credits](https://github.com/FennecChazDevlop/NUCKINTOSH#-dortaniaguide---fix-iservices--)
>
>---


# Nuckintosh 8th generation ( Model Nuc8I3BEH ) 
> ### *Compatible with MacOS Catalina, Big sur, Monterey*
## Also works with Nuc8IXBEX i3 / i5 / i7 
### Reference Image
>---

>![nuc](https://cdn.shopify.com/s/files/1/0353/1181/2653/products/boxnuc8i7beh4_469185b3-ba64-4fe4-bd1d-24402bd1706f_300x300.png?v=1593091237)

>---
### You can buy one in ebay for a cheap price ( in my case, i bought one for only 275 USD with 8GB ram and SSD M.2 240GB, To be fair very great deal )
>---

>![nuc](https://m.media-amazon.com/images/S/aplus-media/vc/42f0b0c5-4d41-4690-b2e9-12d114e8a589._CR0,0,970,300_PT0_SX970__.jpg)

>---
### YOU CAN BUY ONE IN HERE:

>---


>#### [Ebay NUC8I3BEH](https://www.ebay.com/sch/i.html?_from=R40&_nkw=nuc8i3beh&_sacat=0&RAM%2520Size=8%2520GB&LH_BIN=1&rt=nc&Storage%2520Type=SSD%2520%2528Solid%2520State%2520Drive%2529&_dcat=179)
>#### [Ebay NUC8I5BEH](https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2334524.m570.l1313&_nkw=nuc8i5beh&_sacat=0&LH_TitleDesc=0&rt=nc&RAM%2520Size=8%2520GB&_odkw=nuc8i3beh&_osacat=0&LH_BIN=1&_dcat=179&Storage%2520Type=SSD%2520%2528Solid%2520State%2520Drive%2529)
>#### [Ebay NUC8I7BEH](https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2334524.m570.l1313&_nkw=nuc8i7beh&_sacat=0&LH_TitleDesc=0&_odkw=nuc8i5beh&_osacat=0&LH_BIN=1)


>---

# Getting Started
##  What will you Need
  >---
  
  > - Obviously a INTEL NUC
  > - Patience
  > - Around 1-2 hours
  > - Windows Based Machine
  > - Pendrive 2.0 with at least 16gb, not too old btw
  > - Basic CMD knowledge
  > - Installation EFI FOLDER, Post-Install EFI FOLDER, Both can be found in this repo ( Releases )
  
  >---
  
 ##  What contains the Post-Install EFI Folder
  >---
  
  > - Airportltlwm.kext
  > - AppleALC.kext
  > - IntelBluetoothFirmware.kext
  > - IntelBluetoothInjector.kext
  > - IntelMausi.Kext
  > - Lilu.kext
  > - Sinetek-rtsx.kext
  > - SMCProcessor.kext
  > - SMCSuperIO.kext
  > - USBports.kexts
  > - VirtualSMC.kext
  > - WhateverGreen.kext
  > - Custom SSDT For Intel Nuc's8IXBEX


  >---
  
##  What is working 
  >---
  
  - [X] Audio (HDMI and Headphone jack)
  - [X] Audio controls
  - [X] Bluetooth
  - [X] Ethernet
  - [X] Wifi
  - [X] USB 3.0
  - [X] USB Type C (ThunderVolt)
  - [X] UP To Quad Booting (Linux, Android(Home Center), Windows and macOS)
  - [X] microSD Card reader
  - [X] ICLOUD
  - [X] Facetime, Imessages, Iservices

   >---
 ##  UnTested / Not Working  
  >---
  
  - [ ] 4k Resolution *UNTESTED*
  - [ ] Type C to HDMI or DisplayPort *NotWorking*
  - [ ] 4+ usb Hub *Not Working*
  - [ ] 144hz Monitor *UNTESTED*
  >---
 
##  Finished Work be like 

  >---

  >![happy](https://i.ibb.co/qj6kQhT/Screenshot-at-Sep-10-13-35-04.png)

  >---


>---
>>---
>>>---
>>---
>---


# Prepare Machine ( BIOS UPDATE )
### 1.- First we need to update our Nuc's bios from XXXX ---> 0089.
To do that we need to download the bios updater from [Intel's Webpage](https://www.intel.la/content/www/xl/es/products/sku/126150/intel-nuc-kit-nuc8i3beh/downloads.html) and Download the first One as a windows executable (.exe / .msi)
>---

>![intel1](https://i.ibb.co/K9MPybz/Screenshot-at-Sep-10-13-55-03.png)

>---
>---

>![intel2](https://i.ibb.co/BPVvK2R/Screenshot-at-Sep-10-16-39-48.png)

>---

#### 2.- Double-click the *.msi file to run the Express BIOS update.
>---

>![nuc22](https://www.intel.com/content/dam/support/us/en/images/mini-pcs/5636_image2.jpg)

>---
#### 3.- DClick Restart and Install BIOS on the Welcome screen.
>---

>![nuc33](https://www.intel.com/content/dam/support/us/en/images/mini-pcs/5636_image3.jpg)

>---


>---
>>---
>>>---
>>---
>---


# Prepare Machine ( BIOS Configuration )

#### 1.- Reset default Settings
```
Home > Default Settings > Confirm > Yes
```
#### 2.- Follow the Next Configuration in Devices
```
Devices > USB > Port Device Charging Mode: off
Devices > USB > USB Legacy -> Disabled
```
#### 3.- Change Type C's Security Level in security section
```
Security > Thunderbolt Security Level: Legacy Mode
```
#### 4.- Disable Secure Boot and Network Boot in Boot section
```
Boot > Secure Boot > Disable
Boot > Boot Configuration > Network Boot: Disable
```
#### 5.- Disable Lan Boot in Power section
```
Power -> Wake on LAN from S4/S5: Stay Off
```


# Prepare USB

 ###  1.- Downlaod the Installation EFI From this repository 
  >---
  
  >#### [ Nuckintosh ](https://github.com/FennecChazDevlop/NUCKINTOSH/released)
  
  >---
 ###  2.- Download [ Rufus ](https://rufus.ie/en/) From his official site
 
  ![ Rufus ](https://i.ibb.co/QYJ254V/Screenshot-at-Sep-11-00-51-33.png)
 
 ###  3.- Format your USB Drive as Fat32 and set it as Non-Bootable
  >---
  
  >#### just like the next image
  ![ Rufus2 ](https://i.ibb.co/wWbJ8mB/rufus-file-system-and-volume-label.png)
  
  >---
 ###  4.- Copy the INSTALLATION EFI-FOLDER directly to the root of the USB DRIVE 
  >---
  
  >#### The Route Should be like this 
```
D:/EFI
```
  >---
 
 ###  5.- Load the MacOS System to your USB DRIVE
  >---
  
  >#### Create a Folder with this name 
```
com.apple.recovery.boot
```
  >#### Next Copy your Recovery System of MacOS .DMG and his .ChunkList 
  >to the 
```
com.apple.recovery.boot
```
  >Folder 

#### PD: You can get your MacOS .dmg and .chunklist from [ gibMacOS ](https://github.com/corpnewt/gibMacOS)

>---



# Installation

## The installation Process is easy
#### 1.- Shutdown Intel Nuc
#### 2.- Power ON and go to the Bios
#### 3.- Set USB Drive as Primary Bootable Device
#### You will get a boot screen Like this --->
![ OCL ](https://www.insanelymac.com/uploads/monthly_2020_11/OC_Boot.jpg.0c8516fcaba58ea528581dbd688dd8ca.jpg)
#### 4.- Load MacOS Recovery
#### 5.- Use Disk Utility to format your Mac OS dedicated Disk or Partition to APFS ( Reference IMAGE )  
![ OCL ](https://support.apple.com/library/content/dam/edam/applecare/images/en_US/macos/Mojave/macos-mojave-disk-utility-add-volume.jpg)
#### 6.- Then Install MacOS as an ordinary APPLE DEVICE 
![ OCL ](https://support.apple.com/library/content/dam/edam/applecare/images/en_US/macos/Big-Sur/macos-big-sur-recovery-reinstall-macos.jpg)



# Post-Install

## There's no much things to do, more than
#### > - Change the EFI FOLDER To the post install Version
#### > - Using [ OpenCoreConfigurator ](https://mackie100projects.altervista.org/opencore-configurator/) Open your SSD or HDD EFI Partition and Paste the Post-Install EFI Folder  
#### > - If you want you can use [ BarrierKVM ](https://github.com/maxiberta/barrier) to use your main pc Mouse and Keyboard with your NEW NUCKINTOSH :D

# Fix iservices and icloud

### [ Dortania ](https://dortania.github.io/OpenCore-Install-Guide/) Have a very nice explanatory of how to fix the Mac Services, and much better explained than me so the best option is use his guide 

## [ DortaniaGuide - Fix iservices  ](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#using-gensmbios)


>---
>
>
>>---
>
>>>---
>
>>---
>
>
>---


Credits to [ Dortania ](https://dortania.github.io/OpenCore-Install-Guide/) And his Awesome Guide, and this Awesome Comunnity !!! 
I hope this porly contribution helps someone <3
