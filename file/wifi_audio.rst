================
WiFi语音模组
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

XR-50A WiFi模组是由深圳市机芯智能有限公司开发的，该模块核心处理器XR872在较小尺寸封装中集成了运行频率高达384MHz的ARM Cortex-M4F CPU驱动，满足最小内存实现、减少pin数和低功耗的需求。XR872是一款高度集成的低功耗Wi-Fi微控制器SoC，支持 RTOS，集成 WiFi MAC/ BB/RF/PA/LNA，高性能和高度集成的MCU，使软件能够执行更复杂的任务，支持AES/DES/3DES/SHA/MD5/CRC等硬件加密引擎，使数据传输更安全、更快。采用XRADIOTECH的MPDTM技术设计的新型数字RF发射机可提供更高的输出功率并保持更高的效率，保持芯片对天线适配不敏感，但在不同的VSWR下始终具有良好的EVM。它还包括许多外设，包括UART，TWI，SPI，DMIC，音频编解码器，PWM，CIR（T / R），CSI，SDIO和辅助ADC。

:特性:
- IEEE 802.11b/g/n, 1x1 SISO 2.4GHz
- 内置ARM Cortex-M4F的32 位微型 MCU，主频高达384MHZ，支持 RTOS
- 内置1024 bits的efuse
- 支持外置 Flash 和eXecute In Place(XIP) 模式
- 8路共享的通用DMA通道
- 内置8路12位分辨率和10位有效SAR型A / D转换器，其中7路普通通道，1路VBAT电压检测通道
- 集成 Wi-Fi MAC/ BB/RF/PA/LNA
- 支持WEP, WPA/WPA2, WPS2.0
- 支持UART/GPIO/ADC/PWM/IIC/I2S接口
- 支持AES/DES/3DES/SHA/MD5/CRC加密引擎
- 支持 STA/AP 工作模式
- 支持安卓、IOS的Smart Config（APP）/AirKiss（微信） 一键配网
- 支持串口本地升级和远程固件升级（FOTA）
- 通用AT指令可快速上手
- 支持二次开发，集成了Windows、Linux开发环境
- 集成音频子系统（Audio Subsystem），包括1个带有左右声道语音输入的数字麦克风控制器，1个24位音频数模 （DAC）通道，支持8KHz至192KHz的采样率，1个用于麦克风输入的24位音频模数（ADC）通道，支持8KHz至48KHz的采样率，1个用于线路输入的24位音频
- 集成视频子系统（Video Subsystem），支持JPEG、CSI编码模式，在离线编码模式下支持nv12输入格式，支持可配置的图片分辨率，最低图片分辨率：32x32，最大图片分辨率：1920x1088


----------------
选型表
----------------

.. image:: /images/872.png
   :width: 520
   :height: 340

----------------
XR-50A
----------------

`XR-50A模组规格书V1.3 <../_images/XR-50A模组规格书v1.1.pdf>`_ 

.. image:: /images/XR-50A-1.png 
   :width: 284
   :height: 367
.. image:: /images/XR-50A-2.png
   :width: 284
   :height: 367


开发板
================
____

--------------------------
XR-50A_EVB_AUDIO开发板简介
--------------------------

`XR-50A_EVB_AUDIO开发板用户指南V1.2.pdf <../_images/XR-50A开发板用户指南V1.2.pdf>`_

XR-50A_EVB_AUDIO是一款基于XR-50A WiFi模组的音频开发板，拥有强大的MCU处理器，
内部集成了音视频子系统，外设资源丰富，有1路line-in通道，可通过AEC算法实现降噪、
回声消除等功能。XR-50A_EVB_AUDIO硬件部分包含麦克风、功能按键、LED 灯、电源、
WiFi 模块、音频接口、Camera接口等。


----------------------------------
XR-50A_EVB_AUDIO开发板实物图
----------------------------------

.. image:: /images/XR-201-EVB-AUDIO.png
   :width: 742
   :height: 534


文档下载
================
____

:download:`XR-50A_EVB_AUDIO V1.0开发板原理图.pdf </images/XR-201_EVB_AUDIO V1.0开发板原理图.pdf>` 

:download:`XR-50A_EVB_AUDIO开发板用户指南V1.2.pdf </images/XR-50A开发板用户指南V1.2.pdf>` 

:download:`快速入门V1.1.pdf </images/快速入门V1.1.pdf>` 


演示文件
================
____

:download:`xiaoniu_50A_flash_player_noiot_v1.1.img </images/xiaoniu_50A_flash_player_noiot_v1.1.img>` 

:download:`xiaoniu_50B_flash_player_noiot_v1.1.img </images/xiaoniu_50B_flash_player_noiot_v1.1.img>` 


相关链接
================
____

`官方网站 <http://www.aimachip.com>`_ 

`淘宝店铺 <https://shop379208868.taobao.com/?spm=a21ar.c-design.smart.5.46dfbdc5sKA2D8>`_ 



