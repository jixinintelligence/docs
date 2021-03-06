================
WiFi图像模组
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
XR-50A WiFi 模组主要是为了满足图像采集、语音播放和识别以及无线传输应用而开发的一款专用型的产品，该模组核心处理器 XR872 在较小尺寸封装中集成了运行频率高达 384MHz 的 ARMCortex-M4F MCU；集成高性能 WLAN 系统，包含 Wi-Fi MAC/ BB/RF/PA/LNA 单元；集成高采样率和极低噪声的音频子系统；集成高分辨率图像采集子系统，支持硬件 JPEG 图像编码；集成先进的电源管理单元，支持超低功耗，具有多种睡眠模式和快速唤醒机制；集成硬件加密引擎，支持AES/DES/3DES/SHA/MD5/CRC 等多种加密方式； 集成丰富的外设接口，如 I2S，SDIO，CSI，UART 等。
XR-50A WiFi 模组支持标准的 IEEE802.11 b/g/n 协议，支持 RTOS，支持完整的 TCP/IP协议栈。用户也可以使用该模组为现有的设备添加联网功能，也可以构建独立的网络控制器。在搭载应用并作为设备中唯一的应用处理器时，能够直接从外接闪存中启动。内置的高速缓冲存储器有利于提高系统性能，并减少内存需求。

:特性:
- IEEE 802.11b/g/n, 1x1 SISO 2.4GHz
- 内置ARM Cortex-M4F的32 位微型 MCU，主频高达384MHZ
- 内置416KB的SRAM，160KB的ROM和4M的PSRAM
- 内置1024 bits的efuse
- 支持DVP接口摄像头，最大支持1920*1088分辨率，板载闪光灯
- 支持UART/GPIO/PWM/CSI/MIC/Line-in/Speaker接口
- 支持AES/DES/3DES/SHA/MD5/CRC加密引擎
- 支持 STA/AP/ STA+AP 工作模式
- 支持Smart Config/AirKiss（微信）一键配网
- 支持串口本地升级和远程固件升级（FOTA）
- 通用AT指令可快速上手
- 支持二次开发，集成了Windows、Linux开发环境
- 集成音频子系统（Audio Subsystem），包括1个带有左右声道语音输入的数字麦克风控制器，1个24位音频数模（DAC）通道，支持8KHz至192KHz的采样率，1个用于麦克风输入的24位音频模数（ADC）通道，支持8KHz至48KHz的采样率，1个用于线路输入的24位音频数字（ADC）通道，支持8KHz至48KHz的采样率
- 集成视频子系统（Video Subsystem），支持JPEG、YUV编码模式，在离线编码模式下支持nv12输入格式，支持可配置的图片分辨率，最低图片分辨率：32x32，最大图片分辨率：1920x1088

----------------
XR-50A
----------------

`XR-50A模组规格书V1.1 <../_images/XR-50A模组规格书v1.1.pdf>`_ 

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
XR50A_CAM开发板简介
--------------------------

`XR50A_CAM开发板用户指南V1.0.pdf <../_images/XR50A-CAM开发板用户指南V1.0.pdf>`_ 

XR50A-CAM是一款基于XR-50A WiFi模组开发的无线图像采集产品，其可作为图像采集开发板使用或者独立产品使用。开发板硬件部分包含Camera接口、复位按键、TF卡座、电源指示灯、闪光灯、XR-50A WiFi模组等。XR50A-CAM开发板为图像采集及无线传输应用提供便利，具有很强的专用性。同时产品支持一路麦克风接口和扬声器接口，可同时做音频的采集及输出。

--------------------------
XR50A_CAM图像编码模式
--------------------------

XR50A_CAM支持 online 及 offline 模式编码，在online模式， CSI 每接收到 16 行数据就自动进行 JPEG 编码，当前帧图像接收完，编码也随即完成。该模式 CSI 不会将接收的原始图像数据保存起来，只输出 JPEG 编码后的数据。编码数据输出的方式又有：整帧模式和分块模式。在offline模式下， CSI 接收到的数据会先存到内存中，待一帧完整数据全部存储完成后，由软件启动 JPEG 编码。所以此时 JPEG 不是实时处理，可以对任何已经保存好的 YUV420 图像数据进行编码。

----------------------------------
XR50A_CAM开发板实物图
----------------------------------

.. image:: /images/XR50A-CAM正面.jpg
   :width: 313
   :height: 417
.. image:: /images/XR50A-CAM反面.jpg
   :width: 313
   :height: 417



文档下载
================

____

:download:`XR50A_CAM开发板原理图V1.0.pdf </images/XR50A_CAM开发板原理图V1.0.pdf>` 

:download:`XR50A_CAM开发板用户指南V1.0.pdf </images/XR50A-CAM开发板用户指南V1.0.pdf>` 

:download:`快速入门V1.1.pdf </images/快速入门V1.1.pdf>` 

:download:`XR-50B开发板用户指南V1.0.pdf </images/XR-50B开发板用户指南V1.0.pdf>` 

:download:`XR-50B模组规格书V1.2.pdf </images/XR-50B模组规格书V1.2.pdf>` 


相关链接
================

____

`官方网站 <http://www.aimachip.com>`_ 

`淘宝店铺 <https://shop379208868.taobao.com/?spm=a21ar.c-design.smart.5.46dfbdc5sKA2D8>`_ 




