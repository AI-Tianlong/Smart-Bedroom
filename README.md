# Smart-Bedroom
## 智能寝室模型部分部分[点击这里观看视频](https://www.bilibili.com/video/BV1Xv4y1X7sx/?spm_id_from=333.999.0.0)

该程序包括两部分：
* STM32F103ZET6作为主控，控制风扇、步进电机、灯
* 串口屏实现人机交互的UI界面，并通过串口传递命令（16进制字符）给STM32主控
* 手机端蓝牙串口(传输16进制字符给32完成对应的控制)
