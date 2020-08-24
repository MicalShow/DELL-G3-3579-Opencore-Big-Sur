注意：8.24日更新，本人电脑硬件有变更，请参阅更新的硬件配置一栏。

8.24更新内容

1.修复声卡无法发声的BUG

2.更新所有驱动为正式版

3.更新触摸板为GPIO驱动模式

4.精简GUI和驱动，效率更高

注意：此版本移除了对英特尔无线网卡的WiFi和蓝牙支持，需要请自行添加，本人不再为英特尔网卡提供任何技术支持，如遇问题自行查找相关材料解决，不再处理任何有关英特尔无线网卡的问题！

对于部分SM961无法安装Big Sur的问题，目前无解，请替换硬盘食用，本人同样不会对SM961硬盘无法安装BigSur之类的问题提供任何解答！

敬告：出EFI的目的是减少大家在黑苹果路上所走的弯路，并不是提供给某些伸手党偷懒用的。大家的配件可能并不相同，难免会出现某些不同的硬件工作不正常的事，如果发现自己的硬件与作者不同，请自行解决，而不是自己什么也不做，只会要求作者处理。

7.31更新内容

1.修复了在使用Intel AC9462,Intel AC9560网卡的机器上找不到蓝牙设备的问题。

2.成功驱动触摸板，使用轮询模式工作，后期会升级为GPIO中断工作模式，敬请期待。

3.移除了Opencore GUI和BGM，工作更加高效。

7.27更新内容
1.解决了因驱动造成的安装盘禁行的问题
2.修复了无法从10.15.x OTA升级BigSur的BUG

7.26更新内容
1.更新7.26版本itlwm以及itlwmx驱动，提升网卡速度,请根据自身需求加载使用
2.更新部分efi驱动文件为7.26最新编译版


本EFI可正常引导win10

BigSur安装需重新启动数次，如您遇到安装程序在剩余时间还有几分钟时突然重启请不要慌张，重启后继续选择MacOS安装磁盘继续安装即可，整个安装过程计算机可能需要重新启动数次

OpenCore Hackintosh for Dell G3 3579
根据@tonyleelyy https://github.com/tonyleelyy/OpenCore-Hackintosh-Dell-G3-3579/releases/tag/v3.1
的项目修改得到，目前测试可以正常启动macOS10.15.x以及最新的macOS Big Sur Beta版本，暂未发现异常，如有异常欢迎上报samwhiteup@gmail.com

本 OpenCore 黑苹果项目适配 i5-8300H，GTX1050Ti，没有USB Type-C版本的Dell G3 3579

硬件配置

|   配件   |             规格              | 工作状态 |
| :------: | :---------------------------: | :------: |
|   模组   |         Dell G3 3579          |    ✅     |
|  处理器  | Intel Core i5-8300H @ 2.30Ghz |    ✅     |
|   内存   |    8GB KINGSTON DDR4 2666Mhz   |    ✅     |
|   内存   |    8GB SAMSUNG DDR4 2666Mhz   |    ✅     |
| 固态硬盘 |   HP SSD EX950 512GB    |    ✅     |
| 机械硬盘 |         WD10SPZX 1TB          |    ✅     |
| 核芯显卡 |    Intel UHD Graphics 630    |    ✅     |
| 独立显卡 |  NVIDIA GeForce GTX 1050TI 4G   |    ❌     |
|   声卡   |        Realtek ALC236         |    ✅     |
| 有线网卡 |        Realtek RTL8111        |    ✅     |
| 无线网卡 |     Broadcom 934224PCIEBT2    |  ✅  |

感谢每位指导此项目的朋友

- @CerteKim https://github.com/CerteKim/Dell-G3-3579-3779-Hackintosh-OpenCore 没有CK的首创就不会有接下来Tony和我的项目

- @tonyleelyy https://github.com/tonyleelyy/OpenCore-Hackintosh-Dell-G3-3579/releases/tag/v3.1 提供的基本EFI

- @Pyhpanyuahng提供的基本修改思路


- @zxystd https://github.com/zxystd/itlwm 提供的Intel无线网卡驱动项目


戴尔G3黑苹果交流群：1028961766


黑苹果无线网卡交流群：701278330


最后，祝大家都能如愿以偿吃上Big Sur


