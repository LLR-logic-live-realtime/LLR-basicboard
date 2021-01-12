# basicboard
basicboard for quicklogic EOC S3

## 内容介绍
本设计基于quicklogic EOS S3芯片，板载CH340下载器，可以通过USB-C接口进行MCU的编程，板上RGB三色LED等用于简单的调试，总计30个IO用于扩展使用。

### 主要功能特性：

基于quicklogic的FPGA EOS S3
通过CH340进行下载及UART配置/通信
板上一颗R、G、B三色LED，分别连接FPGA的三根专用于驱动LED的管脚，可以用于状态显示及数字逻辑实验
一个RESET按键，用于对系统进行复位
总计36根输入/输出可用于扩展
兼容arduino nano版型。
支持arduino编程。

### 特性
灵活的逻辑架构，拥有2400个逻辑单元，64kbits 存储器，8个FIFO控制器
超低功耗的先进工艺
