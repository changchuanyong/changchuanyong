<div align="center">

# Chuanyong Chang / 常传勇

### Robotics · ROS2 · Embedded Systems · Computer Vision

硕士研究生 · 哈尔滨理工大学 · 机械工程
研究方向：力觉-视觉协同引导的机器人操作与装配

[![GitHub](https://img.shields.io/badge/GitHub-changchuanyong-181717?logo=github)](https://github.com/changchuanyong)
[![Email](https://img.shields.io/badge/Email-1984715306%40qq.com-D14836?logo=gmail&logoColor=white)](mailto:1984715306@qq.com)

</div>

---

## About Me

主要从事机器人系统从底层控制到上层部署的完整实现，涵盖嵌入式控制、ROS2 通信与仿真、视觉定位、运动控制和系统联调。

当前研究方向面向机器人操作与装配任务的 **力觉-视觉协同控制**，重点关注目标检测、位姿估计、接触状态感知与执行力控制。

---

## Focus Areas

- 机器人系统集成：ROS2、Linux、仿真、传感与执行器联动
- 嵌入式控制：STM32、FreeRTOS、电机控制、CAN / UART / RS485 通信
- 计算机视觉：OpenCV、YOLOv8、PnP 位姿估计、ROI 后处理、边缘检测
- 移动机器人：AMR 底盘、导航测试、上下位机通信、自定义协议

---

## Tech Stack

**Languages** `C` `C++` `Python`

**Robotics & Embedded** `ROS2` `STM32` `FreeRTOS` `Linux` `CAN` `UART` `RS485`

**Vision & Algorithms** `OpenCV` `YOLOv8` `PnP` `IPPE` `Pose Estimation` `Image Processing`

**Tools** `Git` `CMake` `VS Code` `Keil` `STM32CubeMX` `Ubuntu`

---

## Featured Projects

### [Robot EV Charging](https://github.com/changchuanyong/robot-ev-charging)

电动汽车充电口视觉检测与位姿估计。YOLO 充电口检测 → 自适应 ROI 后处理 → Canny/Hybrid 边缘提取 → 孔位轮廓筛选与布局先验 → PnP 位姿求解。

<img src="https://raw.githubusercontent.com/changchuanyong/robot-ev-charging/main/docs/assets/readme/roi_detection.jpg" width="400" alt="ROI detection"/>

79 张样张评估：29 OK / 49 Warn / 1 Fail，中位数重投影 17.0 px，9 孔全检出率 71%。

### [ROS2 Mobile Robot](https://github.com/changchuanyong/ros2-mobile-robot)

基于 ROS2 Jazzy 的移动机器人仿真与可视化项目。URDF / Xacro 模型、Gazebo 世界、激光雷达、IMU、差速驱动、RVIZ 可视化、SLAM Toolbox 2D 建图、FAST-LIO 3D 建图、Navigation2 自主导航。

### 仓储物流 AMR 小车系统

基于树莓派 4B + STM32F407 构建上下位机架构，完成 ROS2 功能部署、CAN 通信、自定义协议设计、状态监测、底盘联调与导航测试。

### ROBOCON 机器人底盘电控系统

基于 STM32F4 + FreeRTOS 搭建实时控制架构，实现多电机协同控制、PID 闭环调节、传感器融合与复杂动作执行控制。

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=changchuanyong&show_icons=true&hide_border=true&theme=default)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=changchuanyong&layout=compact&hide_border=true&theme=default)

</div>

---

## Contact

- GitHub: [changchuanyong](https://github.com/changchuanyong)
- Email: [1984715306@qq.com](mailto:1984715306@qq.com)
