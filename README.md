7.26更新内容
1.更新7.26版本itlwm以及itlwmx驱动，提升网卡速度,请根据自身需求加载使用
2.更新部分efi驱动文件为7.26最新编译版
3.替换fakesmc为vituralsmc


本EFI可正常引导win10
OpenCore Hackintosh for Dell G3 3579
根据https://github.com/tonyleelyy/OpenCore-Hackintosh-Dell-G3-3579/releases/tag/v3.1
的项目修改得到，目前测试可以正常启动macOS10.15.x以及最新的macOS Big Sur Beta版本，暂未发现异常，如有异常欢迎上报samwhiteup@gmail.com

本 OpenCore 黑苹果项目适配 i5-8300H，GTX1050Ti，没有USB Type-C版本的Dell G3 3579

硬件配置

|   配件   |             规格              | 工作状态 |
| :------: | :---------------------------: | :------: |
|   模组   |         Dell G3 3579          |    ✅     |
|  处理器  | Intel Core i5-8300H @ 2.30Ghz |    ✅     |
|   内存   |    8GB KINGSTONDDR4 2666Mhz   |    ✅     |
　　　　　　　　8GB SAMSUNG DDR4 2666MHZ
| 固态硬盘 |   HP SSD EX950 512GB    |    ✅     |
| 机械硬盘 |         WD10SPZX 1TB          |    ✅     |
| 核芯显卡 |    Intel UHD Graphics 630    |    ✅     |
| 独立显卡 |  NVIDIA GeForce GTX 1050TI 4G   |    X     |
|   声卡   |        Realtek ALC236         |    ✅     |
| 有线网卡 |        Realtek RTL8111        |    ✅     |
| 无线网卡 |     Inte WIFI 6 AX200    |  ✅  |

感谢@tonyleelyy提供的基本EFI，@Pyhpanyuahng提供的基本修改思路，@Z大github:https://github.com/zxystd/itlwm提供的Intel无线网卡驱动项目
戴尔G3黑苹果交流群：1028961766
黑苹果无线网卡交流群：701278330

黑苹果技术门户网站：blog.daliansky.net
Imacos.top

最后，祝大家都能如愿以偿吃上Big Sur


