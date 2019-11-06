﻿# [STM32H750](https://github.com/sochub/STM32H750)
[![sites](SoC/SoC.png)](http://www.qitas.cn) 

#### [Vendor](https://github.com/sochub/Vendor) ：[ST](https://github.com/sochub/ST)
#### [Cortex](https://github.com/sochub/Cortex) ：[Cortex M7](https://github.com/sochub/CM7)（2.14 DMIPS/MHz）
#### [Level](https://github.com/sochub/Level)：2020 CoreMark | 856 DMIPS @ 400 MHz

## [描述](https://github.com/sochub/STM32H750/wiki) 

[STM32H750](https://github.com/sochub/STM32H750)是[STM32H7](https://www.st.com/zh/microcontrollers-microprocessors/stm32h7-series.html)系列中的高性价比产品，参考售价2.69美金，通过降低内部FLASH的配置，获得超高的性价比。

400 MHz CPU主频下从Flash 执行程序，利用其 L1 缓存实现了零等待执行。DSP 指令集和双精度 FPU 扩大了其应用范围。得益于 L1 缓存（16 KB + 16 KB 的指令缓存和数据缓存），即使使用外部存储器也不会带来性能损失。

2 个专用音频 PLL、3 个全双工 I²S 接口、1 个支持时分多路复用 (TDM) 模式的新串行音频接口 (SAI) 和 1 个 DFSDM（用于 Sigma-Delta 调制器或 MEMS 麦克风的数字滤波器）。

多达 35 个通信接口（除了 4 个 UART 之外，还有 4 个运行速度达到 12.5 Mb/s 的 USART 接口、1 个低功耗 UART、6 个 100 Mb/s 的 SPI 接口，4 个带有新型可选数字滤波功能的 1 MHz I²C 接口、2 个 FD-CAN、2 个 SDIO、带片上 PHY 的 USB 2.0 全速设备/主机/OTG 控制器和 1 个 USB2.0 高速/全速设备/主机/OTG 控制器、片上全速 PHY 和 ULPI、以太网 MAC、SPDIF-IN、HDMI-CEC、摄像头接口、单线协议接口和 MDIO 从接口。

2 个 12 位 DAC、3 个达到 16 位最大分辨率 (3.6 Msample/s) 的快速 ADC 以及 22 个 16 位和 32 位定时器（16 位高分辨率定时器的运行频率高达 400 MHz）。利用带有 32 位并行接口的灵活存储控制器可轻松扩展存储器容量，支持 Compact Flash、SRAM、PSRAM、NOR、NAND 和 SDRAM 存储器，或利用双模 Quad-SPI 从外部串行 Flash 执行代码。

128 KB Flash 和采用分散架构的 1 MB SRAM：用于在最低功耗模式下保存数据的 192 KB TCM RAM（包括 64 KB 的 ITCM RAM 和 128 KB 的 DTCM RAM，用于时间关键型程序和数据）、512 KB、288 KB 和 64 KB 的用户 SRAM 以及 4 KB 的备份域 SRAM，此系列采用BGA 和 LQFP 规范的 LQFP100、UFBGA176 和 TFBGA240引脚封装。

[![sites](SoC/STM32H750.png)](https://www.st.com/zh/microcontrollers-microprocessors/stm32h7-series.html) 

[![sites](SoC/stm32h750.jpg)](https://www.st.com/en/microcontrollers-microprocessors/stm32h750vb.html) 

[![sites](SoC/STM32HP.jpg)](https://www.st.com/zh/microcontrollers-microprocessors/stm32h750-value-line.html) 

### 关键特性（核心买点）

* 400 MHz CPU
* 35个通信接口
* PCIe 1.1 Root Complex

### [收录资源](https://github.com/sochub/STM32F405)

* [文档](docs/)
* [资源](src/)
    * [freeRTOS](src/freeRTOS/)

### [关联资源](https://github.com/sochub)

* [编译工具](https://github.com/sochub/arm-none-eabi)

### [选择建议](https://github.com/sochub)

[STM32H750](https://github.com/sochub/STM32H750)最为高性价产品，在向下覆盖的情况下十分具有应用价值，携带的大量外设极大降低了相应成本，而该系列的3款产品差异只体现在封装和普通IO上面。

- 对标产品 [RT1052](https://github.com/sochub/RT1052),[RT1062](https://github.com/sochub/RT1062)
- 同系列集成FLASH版本 [STM32H743](https://github.com/sochub/STM32H743)  

##  [SoC资源平台](http://www.qitas.cn)  
