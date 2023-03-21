# printer-know-how

## 引擎（Engine）

## 硬件





## 控制（Controller）



## 打印控制语言（Printer  Control Language）
- PJL

​       PJL是Printer Control Language的缩写。最初由HP公司推出，用于更改打印机纸盒、尺寸等设置。



## 协议（Protocol）



- LPD

  LPD是The Line Printer Daemon的缩写。最初于二十世纪八十年代在Berkeley Unix中引入的。LPD运行在端口515/tcp上，可以使用lpr命令访问。LPRng是类UNIX操作系统下的一个流行的LPD应用。

- [IPP](./ipp/ipp-firstpage.md)

  IPP是Internet Printing Protocol的缩写，于1999-2005年之间发布的一套标准，应用于互联网打印、移动打印，云打印，也适用于3D打印。

- [IPP Everywhere](./ipp/IPP-Everywhere.md)

​     IPP Everywhere是于2013年公开，它允许个人电脑和移动设备发现打印机，将文件打印到网络打印机或USB打印机，而无需使用厂家的驱动软件。该协议成为了免驱打印的通用标准。

- SNMP

​    SNMP 全称为Simple Network Management Protocol，是简单网络管理协议，由互联网工程任务组（IETF：Internet Engineering Task Force ）定义的一套网络管理协议。该协议用于获取打印机设备状态，如查看是否卡纸、是否没粉等，服务器也可以主动接受打印机发送的SNMP信息。



## Software

- [OpenPrinting](https://openprinting.github.io/)
    - OpenPrinting develops IPP-based printing technology for Linux®/Unix® operating systems
    - Most modern printers work using OpenPrinting software without additional drivers or software.

- [LPRng](http://www.lprng.com/)
    - The LPRng software is an enhanced, extended, and portable implementation of the Berkeley LPR print spooler functionality. 
- LPRngTool
    - LPRngTool is a Graphical User Interface for the monitoring and configuration of the LPRng printing system. 

## Security of Printer

