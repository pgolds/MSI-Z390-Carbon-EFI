# MSI MPG Z390 Gaming PRO Carbon + i7-9700K

> Support MacOS 10.15.5 Catalina
>
> OpenCore 0.5.9

### 硬件信息

|   CPU    |                      Intel i7-9700K                       |
| :------: | :-------------------------------------------------------: |
|   主板   |              MSI MPG Z390 Gaming PRO Carbon               |
|  内存条  |               Kingston DDR4 3200MHz 8GB * 2               |
|   硬盘   |                    TOSHIBA Q200 240GB                     |
|   显卡   | Intel UHD 630 + igame GeForce RTX 2070 Vulcan X OC (无解) |
| 有线网卡 |                       Intel® I219-V                       |
| 板载声卡 |                     Realtek® ALC1220P                     |
|  显示器  |    AOC U2790PC 27英寸 4K + ThinkVision X27q 27英寸 2K     |

### BIOS设置

> BIOS版本: [7B17v17](https://www.msi.com/Motherboard/support/MPG-Z390-GAMING-PRO-CARBON)

* VT-D -> disabled
* CFG Lock -> disabled
* Windows 10 WHQL -> disabled
* XHCI Hand-off -> enabled
* 设置第一显卡 -> IGD
* 共享显存 -> 64M
* 多显示器 -> enabled
* ErP ready -> enabled

### SMBIOS机型修改

> 修改**PlatformInfo-Generic**里参数
>
> [SMBIOS生成教程](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#platforminfo)
>
> 机型选择: **iMac19,1**

### 参考链接

[OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
