---
date: 2016-04-19 14:46
status: public
title: PocketCar
---

#PocketCar短途代步工具
[img1实物展示]()
概述：笔记本大小，重心控制，3-4kg，四轮代步。
<iframe height=498 width=510 src="http://player.youku.com/embed/XMTUxNjYxMDQ0NA==" frameborder=0 allowfullscreen></iframe>
采用STM32作为主控芯片，MPU6050惯导单元（V0.1采用一个，接下来会探索多个MPU进行拟合）辅助控制。
采用控制方式是分时控制，2ms控制一次电机，输出PWM波；周期200ms，其中MPU更新占，超声波测量占，数据发送给上位机占周期的

上位机功能

下位机传感器的选型，测量，建模：

GitOS地址：
该项目代码不开源，但是能展示一些思路以及框架。如下：
