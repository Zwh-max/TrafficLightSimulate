# TrafficLightSimulate
Java大作业-交通模拟程序
## 交通信号灯模拟
模拟实现十字路口的交通灯管理系统逻辑

1.随机生成按照各个路线行驶的车辆

2. 信号灯忽略黄灯，只考虑红灯和绿灯。

3. 应考虑左转车辆受信号灯控制，右转车辆不受信号灯控制。

4. 具体信号灯控制逻辑与现实生活中普通交通灯控制逻辑相同，不考虑特殊情况下的控制逻辑：
  
5. 南北车辆与东西车辆交替放行，同方向车辆等待应先放行直行车辆，后放行左转车辆。

6. 随机生成车辆时间间隔以及红绿灯交换时间间隔自定，可以设置。

## 系统的总体设计
RoadPanel的一部分、CarImage、 DrawImag以及MainFrame用于解决界面问题，RoadPanel的另一部分和Car解决算法问题。
