## 概述

USBCAN-UC12是一款双通道USBCAN设备，内置USB2.0全速接口和双通道CAN总线。
PC通过USBCAN-UC12可以连接到两个不同的CAN网络，完成数据采集、设备控制等功能。

与市面上其他USBCAN产品相比，USBCAN-UC12体积非常小巧，在内置了双通道CAN前提下
体积仅仅相当于一个普通U盘，同时接线采用2.54排针和杜邦插头，省去拧线的麻烦，
内置120欧终端电阻，避免了丢失外接终端电阻的尴尬。

软件方面USBCAN-UC12完全兼容CANTest通用测试软件，无需替换DLL。功能上可完全
替换ZLG经典型号USBCAN-II，性能更强、功耗更低、价格更实惠，降低了用户的学习
成本和使用成本。

对于熟悉命令行的高级用户，USBCAN-UC12同样提供了基于命令行的VCOMCAN固件，
该固件基于虚拟串口，无需PC端的专用驱动和应用程序。

## 资源汇总

- [用户手册PDF版本](DOC/USBCAN-UC12用户手册_v20.8.4.pdf)
- [命令手册PDF版本](DOC/VCOMCAN_CmdRef_v20.8.4.pdf)
- [命令手册在线阅读](DOC/VCOMCAN_CmdRef.md)
- [速度测试文档PDF版本](DOC/USBCAN-UC12速度测试_v20.8.10.pdf)
- [固件更新日志](FW/ReleaseNotes.md)
- [固件下载目录](FW)

## 主要特性

- 小巧便携，仅优盘大小，重量不足8克。
- 双通道CAN接口，兼容ZLG USBCAN-II。
- ARM Cortex M4架构相比8051架构更强大。
- 支持CANTest通用测试软件无需替换DLL。
- 支持虚拟串口UARTCAN模式。
- 支持Windows、Linux驱动。
- 杜邦线接线更方便无需到处寻找螺丝刀。
- 内置120欧终端电阻。
- 内置500mA自恢复保险丝。
- 内置双固件支持固件升级。
