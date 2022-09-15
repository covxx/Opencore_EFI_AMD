# Opencore 0.8.4 EFI For Ryzen Hackintosh
This version of EFI allowed me to install Mac OS 12.6 with open core v0.8.4. This took a few days to get working and I highly recommend following [dortania's](https://dortania.github.io/OpenCore-Install-Guide/) guide completly before trying this folder. Mac OS is fully functional besides my bluetooth USB (Broadcom) not working. OS is stable, left on for 12+ hours with no error/crashes but YMMV. iServices,DRM, and HW acceleration are also working.

Note: Opencore debug is on while apple debug/verbose is off.

![opencorewow](https://i.ibb.co/VVqDjwX/SCR-20220915-iaw.jpg)

## Specifications

| OPENCORE VERSION 0.8.4 |
|------------------------|

| Component   | Model                            |
|-------------|----------------------------------|
| CPU         | Ryzen 5 3600x                    |
| GPU         | MSI RX580 Armor MK2 8GB OC       |
| Motherboard | AsRock Steel Legend B450M        |
| Bios Ver.   | Beta 4.31 - 06/06/2022           |
| SMBIOS Ver. | iMacPro1,1                       |
| Ethernet    | RealtekRTL8111                   |

## Performance
![geekbench](https://i.ibb.co/Ch8xMpH/GB-Scores-SS.png)


## Issues
- [ ] https://github.com/covxx/Opencore_EFI_Ryzen_iMP/issues/1 Bluetooth not working
- [X] - DRM 
- [x] - VGA Decorder
- [X] - HW Acceleration
- [x] - iServices (Fully Working)
- [x] - en0 shown as bulit in
- [x] - USB Ports Mapped 


## Resources
- [Dortania's Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [Opencore](https://github.com/acidanthera/OpenCorePkg)
- [HackinTool](https://github.com/headkaze/Hackintool)
- [ProperTree](https://github.com/corpnewt/ProperTree)
- [MountEFI](https://github.com/corpnewt/MountEFI)
- [USBMap](https://github.com/corpnewt/USBMap)
