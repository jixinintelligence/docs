================
WiFi模组
================
____



环境搭建
================
____


`环境搭建参考指南 <../_images/快速入门V1.1.pdf>`_ 



全志模组
================
____

----------------
模组简介
----------------

XR-21A、XR-22AWiFi模组是由深圳市机芯智能有限公司开发的，该模组核心处理器XR808在较
小尺寸封装中集成了ARM Cortex-M4F 的32 位微型控制器，支持从32KHz到160MHz的时钟速率，
满足最小内存实现、减少pin数和低功耗的需求。XR808是一款高度集成的低功耗Wi-Fi微控制
器SoC，支持 RTOS，集成 WiFi MAC/ BB/RF/PA/LNA，高性能和高度集成的MCU，使软件能够
执行更复杂的任务，支持AES/DES/3DES/SHA/MD5/CRC等硬件加密引擎，使数据传输更安全、更
快。XR808通过使用几种低功耗状态和从硬件到软件的快速唤醒时间，对低功耗操作进行了优
化。多个电源域和时钟可以分别关闭。应用子系统和WiFi子系统可以独立进入低功耗状态，
从而支持各种应用用例。

:特性:
- IEEE 802.11b/g/n, 1x1 SISO 2.4GHz
- 内置ARM Cortex-M4F的32 位微型 MCU，主频支持从32KHz到160MHz，支持 RTOS
- 内置256KB的SRAM和160KB的ROM
- 内置1024 bits的efuse
- 支持外置 Flash 和eXecute In Place(XIP) 模式
- 8路共享的通用DMA通道
- 内置6路12位分辨率和10位有效SAR型A / D转换器，其中5路普通通道，1路VBAT电压检测通道
- 集成 Wi-Fi MAC/ BB/RF/PA/LNA
- 支持WEP, WPA/WPA2, WPS2.0
- 支持UART/GPIO/ADC/PWM/IIC接口
- 采用SMD-16封装
- 支持多种休眠模式，深度睡眠电流低至4uA
- 支持AES/DES/3DES/SHA/MD5/CRC加密引擎
- 支持 STA/AP 工作模式
- 支持安卓、IOS的Smart Config（APP）/AirKiss（微信） 一键配网
- 支持串口本地升级和远程固件升级（FOTA）
- 通用AT指令可快速上手
- 支持二次开发，集成了Windows、Linux开发环境


----------------
选型表
----------------

.. image:: /images/808.png
   :width: 520
   :height: 320

----------------
XR-21A
----------------

`XR-21A_规格书V1.4 <../_images/XR-21A_规格书V1.4.pdf>`_ 

.. image:: /images/XR-21A-1.png 
.. image:: /images/XR-21A-2.png
   :width: 284
   :height: 367

----------------
XR-22A
----------------

`XR-22A_规格书V1.1 <../_images/XR-22A_规格书V1.1.pdf>`_

.. image:: /images/XR-22A-1.png
   :width: 284
   :height: 300
.. image:: /images/XR-22A-2.png
   :width: 284
   :height: 300


------------------
MICROWE开发板简介
------------------

`MICROWE开发板用户指南V1.3 <../_images/MICROWE开发板用户指南V1.3.pdf>`_

MICROWE是一款基于XR-21A WiFi模组的开发板，由机芯智能有限公司研发团队
研发的。该开发板主要为了方便用户快速了解使用XR808芯片而设计的。



-----------------------
MICROWE开发板实物图
-----------------------

.. image:: /images/MICROWE.png
   :width: 284
   :height: 467

-----------------------
全志文档下载
-----------------------


:download:`MICROWE开发板用户指南V1.3.pdf </images/MICROWE开发板用户指南V1.3.pdf>` 

:download:`XR-21A_规格书V1.4.pdf </images/XR-21A_规格书V1.4.pdf>` 

:download:`XR-22A_规格书V1.1.pdf </images/XR-22A_规格书V1.1.pdf>` 

:download:`快速入门V1.1.pdf </images/快速入门V1.1.pdf>` 




博流模组
================
____


----------------
BL-62A
----------------

----------------
BL-62B
----------------

BL-62B
型号： BL-62B 
封装： SMD16 
尺寸： 16*24*3(±0.2)mm 
Flash容量： 芯片内置 2MB 
支持接口： UART/GPIO/ADC/DAC/PWM/ I2C/SDIO 
串口速率： 9600/19200/38400/115200/921600 bps ,最高5Mbps 
频谱范围： 2400 ~2483.5MHz       天线形式： 板载 PCB 天线 
BL-62B是一款基于 WiFi+BLE 单芯片SoC BL602 为主控的无线模组，它可以满足低功耗和高性能的 IOT 应用开发，BL602 集成了 2.4G Wi-Fi （802.11 b/g/n） 和BLE 5.0 的基带和 MAC 设计。其微控制器子系统包含一个低功耗的 32 位 RISCV CPU、高速缓存和存储器。具有先进的电源管理单元，支持多种低功耗模式，支持WiFi冷启动快联。蓝牙5.0可单独使用，支持SIG Mesh,也可用于WiFi配网。

`BL-62B模组规格书V1.2 <../_images/BL-62B模组规格书V1.2.pdf>`_



----------------
BL-63B
----------------


BL-63B
型号： BL-63B 
封装： DIP-11 
尺寸： 16*24*3(±0.2)mm 
Flash容量： 芯片内置 2MB 
支持接口： UART/GPIO/ADC/DAC/PWM/ I2C/SDIO 
串口速率： 9600/19200/38400/115200/921600 bps ,最高 5Mbps 
频谱范围： 2400 ~2483.5MHz       天线形式： 板载 PCB 天线 
BL-63B是一款基于 WiFi+BLE 单芯片SoC BL602 为主控的无线模组，兼容涂鸦TYWE2S，适合插座，开关，灯等IOT应用。BL602 集成了2.4G Wi-Fi （802.11 b/g/n） 和BLE 5.0 的基带和 MAC 设计。其微控制器子系统包含一个低功耗的 32 位 RISCV CPU、高速缓存和存储器。具有先进的电源管理单元，支持多种低功耗模式，支持WiFi冷启动快联。蓝牙5.0可单独使用，支持SIG Mesh,也可用于WiFi配网。

`BL-63B规格书V1.1 <../_images/BL-63B规格书V1.1.pdf>`_


----------------
BL-01S
----------------

----------------
BL-73B
----------------

BL-73B
型号： BL-73B
封装： SMD32 
尺寸： 29*19*3(±0.2)MM
IO数量： 14 
频谱范围： 2400 ~2483.5MHz 
接口：SPI /UART/GPIO/ADC/DAC/PWM/ I2C/SDIO/MIC/Speaker
Flash容量：2Mbyte+2Mbyte
语音功能：单驻极体麦克风， 3W音频功放，可支持高达150条语音识别命令
天线形式:  板载PCB天线（默认） / IPEX 天线座

BL-73B 是一款由 WiFi+BLE SoC芯片(BL602)和语音芯片组成的 WiFi+BLE+语音识别的双主控芯片模组，该模组在小体积内集成 2.4G Wi-Fi （802.11 b/g/n） 、BLE 5.0和语音识别播报功能，集成大容量RAM和Flash。支持平台快速自定义中英文语音指令，具有高精度语音识别能力。可以方便开发阿里飞燕，涂鸦等平台IOT和语音交互应用。

`BL-73B模组规格书V1.1 <../_images/BL-73B模组规格书V1.1.pdf>`_


-----------------------
博流文档下载
-----------------------

:download:`BL62B_EVB开发板用户指南V1.1 </_images/BL62B_EVB开发板用户指南V1.1.pdf>` 

:download:`BL-62B模组规格书V1.2 </_images/BL-62B模组规格书V1.2.pdf>` 

:download:`BL-63B规格书V1.1 </_images/BL-63B规格书V1.1.pdf>` 

:download:`BL-73B模组规格书V1.1 </_images/BL-73B模组规格书V1.1.pdf>` 

相关链接
================
____

`官方网站 <http://www.aimachip.com>`_ 

`淘宝店铺 <https://shop379208868.taobao.com/?spm=a21ar.c-design.smart.5.46dfbdc5sKA2D8>`_ 