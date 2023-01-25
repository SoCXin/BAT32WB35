# [BAT32WB35](https://doc.soc.xin/BAT32WB35)

* [Cmsemicon](https://www.mcu.com.cn): [Cortex-M0](https://github.com/SoCXin/Cortex)
* [L1R2](https://github.com/SoCXin/Level): 48 MHz

## [简介](https://github.com/SoCXin/BAT32WB35/wiki)

[BAT32WB35](https://www.mcu.com.cn/Products/247.html) 是中微半导体针对无线连接产品线推出的第一颗BLE 5.0 SoC产品，被广泛应用于智能家居、物联网、便携医疗、个护健康、人机接口等典型无线产品领域。

基于M0+内核的高性价比的BLE 5.0 SoC芯片，片上集成了BLE 5.0 RF收发器，支持2Mbsp速率，最大发射功率5dBm，灵敏度-94dBm；主频64MHz，64KB Flash，内置8KB SRAM，1KB Data Flash；集成多种模拟外设如12bit ADC、PWM、比较器，硬件RTC，并支持多种通讯接口； 可工作在1.8V至3.6V，-40℃至85℃，提供QFN40封装。

### 关键参数

* 48 MHz Cortex-M0+
* 8KB SRAM + 64KB Flash + 1KB DATA FLASH
* 集成片上BLE 5.0 收发器
    * 传输速率2Msps
    * 接收灵敏度：-94dBm @1Mbps mode
    * 发射功率：-20dBm - +5dBm
* 1路模拟比较器
* 内置高精度12-bit高速ADC@1.42Msps
* 3通道多功能串行通讯单元
    * 2个UART
    * 1个I2C接口
    * 1个SPI接口
* 异常存储空间访问报错
* 支持硬件CRC校验
* 支持重要SFR保护，防止误操作
* 128位唯一ID号
* 工作电压：1.8V-3.6V @48MHz
* 工作温度：-40℃ - 85℃
* 封装类型：QFN40,多达24个通用GPIO

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin/BAT32WB35)

[BAT32WB35](https://github.com/SoCXin/BAT32WB35)系列目前官方给出的参考资料较少，还没有相关的例程提供。

[Cmsemicon](https://www.mcu.com.cn)目前发布的产品主要应用领域是电气控制，类似[MindMotion](https://www.mindmotion.com.cn/)，主打低端市场，相应的替代型号较多，[BAT32WB35](https://www.mcu.com.cn/Products/247.html)的配置和定位也接近[MM32W073](https://github.com/SoCXin/MM32W073)

## [www.SoC.xin](http://www.SoC.Xin)
