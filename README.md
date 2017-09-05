# README #

包含所有代码和设计图

### 目录说明 ###

* 设计图 : 包含3D模型 和 autocad零件图
* Mac App : 上位机程序，解析SVG，控制下位机
* Arduino App : 下位机，控制刀刀头移动


### module.cpp ###

* Motor 控制每一个轴的电机
* Laser 控制激光通断
* Joystick 接收摇杆的信号，手动控制电机移动





* 上位机下位机通信采用JDY-80蓝牙模块，Bluetooth 4.0, 无需配对，上位机查找到设备后，直接发送指令
* A4988驱动步进电机
* 考虑到功率不大，只需要S8550三极管 控制激光头和散热风扇通断。



### 计划实现 ###
* 解析SVG，画直线和折线（优先）
* 圆、椭圆
* 位图(128级别灰度)



### 脑子进水 ###
* 焊板子翻过来后针脚记错了，烧了两个A4988驱动
* 把激光头和散热风扇两根电源绑在一起，为了测试分别是哪根，直接接到12V电源上，第一个测试的是风扇，转。又把激光头也接上试试，烧了.
* 不知道为什么...arduino板子烧了，还好用的是便宜的山寨板，不知道和这个有没有关系，明天把开关从三极管改成继电器试试吧
* 
* 
* 
