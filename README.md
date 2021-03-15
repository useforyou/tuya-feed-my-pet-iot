# tuya-feed-my-pet-iot
This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.         For more information, please check Tuya Developer Website.

# 一、方案标题
阳台自动浇花器
  
# 二、方案应用
场景地点：自家阳台或者办公室花窗；
功能：过年或者放假期间，阳台或者办公室的盆栽面临无人照看的情况，自动浇花器可自动点滴或者远程控制浇水。
开发过程主要以下几步：了解涂鸦三明治开发的产品结构，主控板采用：ST Nucleo 开发板(STM32Nucleo-G071RB), 通信板：Wi-Fi 通信板（VWXR2）通信板/（ Wi-Fi MCU 通信板（WB3S）），设备：H桥直流电机驱动功能板，电源：直流供电电源板，
首先在涂鸦云平台注册并且创建产品；其次搭建Arduino IDE开发环境；主控板通过串口与通信板交互，AT命令设置连接涂鸦云平台；终端手机APP登录涂鸦平台管理产品的开发测试。
初步开发的预想效果为：手机APP设置直流电机开关，调控电机转速，定时自动开启。
# 三、开发计划3月30前完成.
1）3月20前准备物料
2）3月20-30日嵌入式开发、云开发
3）3月30日前整体调试。
