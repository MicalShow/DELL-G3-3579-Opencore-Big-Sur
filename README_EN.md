Note: Update on 8.24, my computer hardware has changed, please refer to the column of updated hardware configuration.

8.24 update content

1. Fix the bug that the sound card can't make sound

2. Update all drivers to the official version

3. Update the touchpad to GPIO drive mode

4. Streamlined GUI and driver, higher efficiency

Note: This version removes the WiFi and Bluetooth support for the Intel wireless network card. Please add it by yourself. I will no longer provide any technical support for the Intel network card. If there is a problem, I will find the relevant materials and solve it by myself. I will no longer deal with any Intel wireless network card The problem!

For some SM961 cannot install Big Sur problem, there is no solution at present, please replace the hard disk to eat. I also won't provide any answer to the problem of SM961 hard disk cannot install BigSur!

Tips: The purpose of EFI is to reduce the detours that everyone takes on the road to the black apple, and it is not provided for some people to be lazy. Everyone’s accessories may not be the same. It is inevitable that some different hardware will not work properly. If you find that your hardware is different from the author, please solve it by yourself, instead of doing nothing by yourself and just asking the author to deal with it.

7.31 update content

1. Fixed the problem that Bluetooth devices could not be found on machines using Intel AC9462, Intel AC9560 network card.

2. Successfully drive the touch panel and work in polling mode. It will be upgraded to GPIO interrupt mode later, so stay tuned.

3. Removed Opencore GUI and BGM, work more efficiently.

7.27 update content
1. Solve the problem that the installation disk is prohibited due to the driver
2. Fixed the bug that BigSur could not be upgraded from 10.15.x OTA

7.26 update content
1. Update the 7.26 version of itlwm and itlwmx drivers to improve the speed of the network card, please load and use according to your own needs
2. Update some efi driver files to the latest compiled version of 7.26


This EFI can boot win10 normally

The BigSur installation needs to be restarted several times. If you encounter the installation program restarting suddenly when there are a few minutes remaining, please don’t panic. After restarting, continue to select the MacOS installation disk to continue the installation. The computer may need to be restarted several times throughout the installation process.

OpenCore Hackintosh for Dell G3 3579
According to @tonyleelyy https://github.com/tonyleelyy/OpenCore-Hackintosh-Dell-G3-3579/releases/tag/v3.1
The project is modified, and the test can start macOS 10.15.x and the latest macOS Big Sur Beta version normally. No abnormality has been found. If there is any abnormality, please report it to samwhiteup@gmail.com

This OpenCore Black Apple project is compatible with i5-8300H, GTX1050Ti, Dell G3 3579 without USB Type-C version

Hardware Configuration

| Accessories | Specifications | Working Status |
| :------: | :---------------------------: | :------: |
| Module | Dell G3 3579 | ✅ |
| Processor | Intel Core i5-8300H @ 2.30Ghz | ✅ |
| RAM | 8GB KINGSTON DDR4 2666Mhz | ✅ |
| RAM | 8GB SAMSUNG DDR4 2666Mhz | ✅ |
| Solid State Drive | HP SSD EX950 512GB | ✅ |
| Mechanical Hard Drive | WD10SPZX 1TB | ✅ |
| HD Graphics | Intel UHD Graphics 630 | ✅ |
| Discrete Graphics | NVIDIA GeForce GTX 1050TI 4G | ❌ |
| Sound Card | Realtek ALC236 | ✅ |
| Wired LAN | Realtek RTL8111 | ✅ |
| Wireless LAN | Broadcom 934224PCIEBT2 | ✅ |

Thanks to everyone who guided this project

-@CerteKim https://github.com/CerteKim/Dell-G3-3579-3779-Hackintosh-OpenCore Without CK’s initiative, there would be no next Tony and my project

-@tonyleelyy https://github.com/tonyleelyy/OpenCore-Hackintosh-Dell-G3-3579/releases/tag/v3.1 provides basic EFI

-Basic modification ideas provided by @Pyhpanyuahng


-Intel wireless network card driver project provided by @zxystd https://github.com/zxystd/itlwm


Dell G3 Black Apple Exchange Group: 1028961766


Black Apple wireless network card exchange group: 701278330


Finally, I wish you all get Big Sur as you wish
