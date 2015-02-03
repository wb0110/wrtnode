# WRTnode参数

![pins](http://wiki.wrtnode.com/images/e/ec/Pr1.jpg)

## 硬件参数

* About 40mm*50mm
* MTK MT7620N 580MHz MIPS CPU (MIPS24KEc)
* 512Mbit DDR2 ram
* 128Mbit SPI Flash rom
* 300Mbit Wi-Fi 2T2R 802.11n 2.4 GHz
* 23GPIOs
* JTAG
* SPI
* UART Lite
* USB2.0

OpenWrt on Linux kernel 3.10.44（当前版本，随OpenWrt.org trunk版本更新）

microUSB供电 5v

常规电流 30-150ma

## 软件环境

* Based on OpenWrt BARRIER BREAKER (Bleeding Edge, r41508)
* rt2860v2 Wi-Fi driver hacked by lintel
* Customized uboot hacked by manfeel
* WRTnode aplci up-link Wi-Fi configuration (aps/vw/nr/ia)
* Luci Wi-Fi wpa patch for rt2860v2
* Local dns add i.wrtno.de & wrtnode.lan besides openwrt.lan to WRTnode which * the default ip is 192.168.8.1
* WRTnode additional feature (all source opened github.com/WRTnode):
    * Opencv 2.4.8
    * Native gcc-mipsel on mt7620 and bin-utils
    * Porting linino (Arduino yun) source to WRTnode
    * Shine: fast fixed-point mp3 encoding
    * And some WRTnode demo apps:
        * opencv application demo
        * mechanical control demo
        * RESTful front-end demo and some other thing


WRTnode固件、SDK和交叉编译工具链使用OpenWrt trunk版本，由OpenWrt.org官方专为WRTnode维护和支持。

同时，WRTnode可使用市面上所有使用MT7620方案路由器固件及相关SDK和交叉编译工具链。
