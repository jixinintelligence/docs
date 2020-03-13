================
WiFi模组
================
____



环境搭建
================
____


`环境搭建参考指南 <../_images/快速入门V1.1.pdf>`_ 



模组类型
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


开发板
================
____

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


文档下载
================
____

:download:`MICROWE开发板用户指南V1.3.pdf </images/MICROWE开发板用户指南V1.3.pdf>` 

:download:`XR-21A_规格书V1.4.pdf </images/XR-21A_规格书V1.4.pdf>` 

:download:`XR-22A_规格书V1.1.pdf </images/XR-22A_规格书V1.1.pdf>` 

:download:`快速入门V1.1.pdf </images/快速入门V1.1.pdf>` 


相关链接
================
____

`官方网站 <http://www.aimachip.com>`_ 

`淘宝店铺 <https://shop379208868.taobao.com/?spm=a21ar.c-design.smart.5.46dfbdc5sKA2D8>`_ 






