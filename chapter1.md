# 机器人开箱测评之Turtlebot3-waffle

> 本次我们鱼乐机器人为大家带来一款开售不久的ROS经典款机器人turtlebot家族的最新产品Turtlebot3-waffle的开箱与详细的测评。一直以来turtlebot都以ROS社区的官方低成本机器人硬件而自居，然而他们的新品Turtlebot3-waffle款真正上手使用的效果又是如何呢？让我们一起来看看吧。

## 有些东西需要先普及一下

2007年11月7日，ROS开源社区成立，也是在这一天，ROS项目的第一条代码贡献被上传到SourceForge上。

三年后，Willow Garage公司的两位员工 Melonee Wise 和 Tully Foote 在 2010年的11月发布了第一代Turtlebot机器人，作为ROS项目同步学习的硬件平台。

2012年，Willow Garage公司发布了第一款更新产品Turtlebot2，机器人采用Yujin Kobuki的移动底盘，支持自定义搭建上层的应用软硬件结构，包括机器人视觉导航、机械臂控制，激光雷达SLAM等。

2017年，更加轻量型，DIY性更强的第三代机器人Turtlebot3面世。发布伊始，各大销售平台一度出现断货的现象，尽管每一位ROS机器人从业者都知道第三代机器人发布了，但是知道它具体是什么样的人很少。

![](/assets/turtlebot_history.gif)

直到不久前，Turtlebot3的两个型号的机器人陆续进入各大平台，因此我也有幸买到一套（两种型号各一台）上手体验一把，话不多说直接进入开箱。

## 开箱

看到这货的第一眼给我的感觉就像是买了个玩具，包装盒不大，30公分见方，外壳上印着和网上一样的产品图案。

![](/assets/0.jpg)

仔细端详一番，越看越像是买了一台乐高的积木，把一个个的小零件搭起来。

打开箱子，果然一步步的印证了我的第一感觉。盒子里面放着几个小的塑料袋，袋子里装着不同型号的螺钉、螺母、螺柱、塑料盘、塑料按钮、塑料支撑柱、两块小型的电路板、一个USB HUB以及几根USB连接线或者电源线。

![](/assets/1.jpg)

两种螺钉，短一点的螺钉用于拼接waffle的支撑板，原理就像是瓷砖上的图案一样，在固定的位置留有螺钉安装孔。两块一对，八块一层。

![](/assets/2.jpg)![](/assets/3.jpg)

然后在周围的安装孔上拧上螺柱，第一层与第二层之间使用短款螺柱，空间用于安装电机和电池，电机的高度刚好是短款螺柱的长度。安装电机时正好能够卡在一二层之间，上下各用长款细螺钉穿过小孔固定住电机。

![](/assets/4.jpg)Turtlebot3的两款机器人采用的都是前驱式结构，电机主动轮安装在机器人的前端，后端的从动轮采用的是万向钢球。

采用这种结构的好处在于机器人运动过程中收到从动轮的约束力会很小，从而运动控制更加精确。

安装时务必记住1号电机在左，2号电机在右。

![](/assets/5.jpg)![](/assets/6.jpg)

机器人的轮子十分简单，采用的是齿轮式的轮子骨架结构，然后外面套一层类似于汽车橡胶轮胎外胎样式的车胎，以增大摩擦力的同时又不会因为齿轮结构而运动得上下颠簸。

![](/assets/7.jpg)![](/assets/8.jpg)![](/assets/9.jpg)

然后是安装第一个电路板，也是机器人的运动控制板，板上印有OpenCR的字样。电路板是OpenHardware社区开源的电路板之一，因而它的电路图、原理图都能在网上找到。

| 最大限速度 | 0.22 m/s |
| :--- | :--- |
| 最大角速度 | 2.84 rad/s \(162.72 deg/s\) |
| 最大负载 | 15kg |
| 尺寸 \(长 x 款 x 高\) | 138mm x 178mm x 192mm |
| 重量 \(+ SBC + Battery + Sensors\) | 1kg |
| 最大爬坡高度 | 10 mm or lower  |
| 标准使用时间 | 2h 30m |
| 标准充电时间 |  2h 30m  |
| 处理器 | 32-bit ARM Cortex®-M7 with FPU \(216 MHz, 462 DMIPS\) |
| IMU | Gyroscope 3 Axis Accelerometer 3 Axis Magnetometer 3 Axis |
| 电源连接线 |  3.3V / 800mA 5V / 4A 12V / 1A |
| 扩展引脚 | GPIO 18 pins Arduino 32 pin |
| 外接接口 |  UART x3, CAN x1, SPI x1, I2C x1, ADC x5, 5pin OLLO x4 |
| 可编程LED | User LED x 4 |
| 状态LED灯 | Board status LED x 1 Arduino LED x 1 Power LED x 1 |
| 按钮和开关 |  Push buttons x 2, Reset button x 1, Dip switch x 2 |
| 电池 | Lithium polymer 11.1V 1800mAh / 19.98Wh 5C |

![](/assets/10.jpg)![](/assets/11.jpg)![](/assets/12.jpg)![](/assets/13.jpg)![](/assets/14.jpg)![](/assets/15.jpg)![](/assets/16.jpg)![](/assets/17.jpg)

![](/assets/17.jpg)

## ![](/assets/17.jpg)![](/assets/18.jpg)![](/assets/19.jpg)![](/assets/20.jpg)![](/assets/21.jpg)![](/assets/22.jpg)![](/assets/23.jpg)整体评价



