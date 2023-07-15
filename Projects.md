---
layout: page
title: Projects
---

# 实习: 深圳一清创新 系统集成组 嵌入式软件实习生
- **时间:** 2022.6 - 2023.7
- **夸父等多个车型电器升级和底盘适配工作**
  1. 深度参与车载 SSU、VCU、TBox 的 FreeRTOS 功能开发、硬件测试、上车测试和维护工作，实现了 NTP 时间同步、UDS 诊断升级等功能
  2. 参与多个车型的 IMU、编码器、GNSS 等传感器调试、电器调试、整车测试、结构安装等工作
  3. 排查 SSU 和雷达时间不同步问题，编写 python 脚本自动测试，解决了 PWM 输出不稳定的问题
  4. 参与 CAN, SPI 通讯等 ROS 节点的测试和维护工作；参与车辆运动测试工作
- **ACU 域控制器项目**
  1. 深度参与无人车域控制器 MCU 的架构设计、通信协议设计、应用功能开发、台架测试与上车测试，实现了 SPI-CAN 中转通信、多模式切换、控制数据转发等功能
  2. 协助域控制器电路调试、信号测试等工作；用 WaveDrom 绘制上电时序图等
- **无人车 FOTA 项目**
  1. 基于 NodeRED、JavaScript 等设计无人车 FOTA 云平台，实现了远程固件增删、设备升级管理、升级状态反馈等功能
  2. 基于 UDS、CAN、UART、MQTT 等协议，开发 TBox、VCU 和 SSU 的 App 和 Bootloader 程序，最终实现了无人车嵌入式设备的 FOTA
- **传感器替代升级项目**
  1. 调研和汇总了多个品牌的 IMU 参数；组织 IMU 研讨会；推进某 IMU 上车替代测试工作；测量IMU 数据链路延时

  <div style="display: inline-block;">
    <div class="csdn-card" style="float: left; margin-right: 20px;">
      <img src="../img/b10_FOTA.gif" alt="Image 3" style="width: auto;height: 300px;">
    </div>
  </div>


# TI 杯电子设计竞赛：智能送药小车
- **时间:** 2021.11.7-10
- **简介:** 两台可以识别数字、循迹、协同配送的送药小车。
- **工作:** 队长
  - 四天三夜内设计总体任务方案
  - 用rt1064实现彩色视觉感知、色彩空间转换、轨迹提取和定位、车身规划控制和多车通信协作等，完成赛题任务
  - 设计整车结构、固定件，安排组员进行组装
- **获奖:** **国赛一等奖** 2021 年 TI 杯全国大学生电子设计竞赛
- [视频](https://www.bilibili.com/video/BV13L411K7ex/?vd_source=9b67f8488b53e45de247e5881ac151bf) [项目](https://github.com/ouzhoucheng/T-I-C-U-P)

  <div style="display: inline-block;">
    <div class="csdn-card" style="float: left; margin-right: 20px;">
      <img src="../img/b9_Tricycles.jpg" alt="Image 3" style="width: auto;height: 300px;">
    </div>
    <div class="csdn-card" style="float: right;">
      <iframe src="https://player.bilibili.com/player.html?bvid=BV13L411K7ex&page=1" scrolling="no" width="400" height="240" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
    </div>
  </div>


# 16届全国大学生智能汽车竞赛：智能视觉组
- **日期:** 2021.1-2021.8
- **简介:** 能以 2.8m/s 通过十字、弯道等道路元素，可停车识别数字、水果、动物和二维码并作出相应的机动的智能赛车
- **工作:** 队长
  1. 设计任务方案，跟进整体进度，采购元器件
  2. 用 rt1064 实现通信、灰度视觉感知、道路提取和定位、规划控制和特殊机动等功能
  3. 绘制主控驱动一体化pcb和供电pcb，焊接调试
  4. 用Solidworks画固定件，3D打印，设计整车结构，组装整车
- **奖项:** **国赛一等奖** 16届全国大学生智能汽车竞赛
- [video](https://www.bilibili.com/video/BV1tL4y1T7xn/) [code](https://github.com/ouzhoucheng/S-M-A-R-T-C-A-R)

  <img src="../img/b8_SmartCar.jpg" alt="Image 2" style="width: auto;height: 300px;">

  <div style="display: inline-block;">
    <div class="csdn-card" style="float: left; margin-right: 20px;">
      <iframe src="https://player.bilibili.com/player.html?bvid=BV1tL4y1T7xn&page=1" scrolling="no" width="400" height="240" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
    </div>
    <div class="csdn-card" style="float: right;">
      <iframe src="https://player.bilibili.com/player.html?bvid=BV1tL4y1T7xn&page=4" scrolling="no" width="400" height="240" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
    </div>
  </div>

# TI 杯电子设计竞赛：无接触温度测量与身份识别装置
- **日期:** 2020.10.4-7
- **简介:** 可测量人体体温和物温并警告，可录入与识别被测人身份，检测是否佩戴口罩的智能设备
- **工作:** 
  1. 用stm32读取温度传感器并显示
  2. 用树莓派训练和识别人脸
  3. 设计系统机械结构，供电布局，将系统组装成高大上的样子
- **奖项:** **天津市二等奖** 2020年TI杯电子设计竞赛
- [项目](https://github.com/ouzhoucheng/open-cv-face-recognition)

  <img src="../img/b7_FaceRecognitionDevice.jpg" alt="Image 1" style="width: auto;height: 300px;">



# 其他项目

- [光润心灵 (C4D动画)](https://www.bilibili.com/video/BV1ZP4y1A7qP)

  <img src="../img/projects/Color.gif" alt="Image 18" style="width: auto;height: 300px;">

- [八卦阵 (51仿真)](https://blog.csdn.net/weixin_46143152/article/details/113789422)
  
  <img src="../img/projects/8gua.gif" alt="Image 11" style="width: auto;height: 300px;">

- [蓝牙遥控平衡小车 (stm32)](https://blog.csdn.net/weixin_46143152/article/details/113787033)
  
  <img src="../img/projects/balance_car.gif" alt="Image 12" style="width: auto;height: 300px;">

- [红外测温枪 (stm32)](https://blog.csdn.net/weixin_46143152/article/details/113787146)
  
  <img src="../img/projects/temp_gun.jpg" alt="Image 13" style="width: auto;height: 300px;">

- [转速测量仪 (stm32)](https://blog.csdn.net/weixin_46143152/article/details/113917650)
  
  <img src="../img/projects/tachometer.jpg" alt="Image 14" style="width: auto;height: 300px;">

- [FPGA时钟 (FPGA,Verilog)](https://blog.csdn.net/weixin_46143152/article/details/122648005)
  
  <img src="../img/projects/Clock.gif" alt="Image 17" style="width: auto;height: 300px;">

- [OCR数字识别 (labview)](https://blog.csdn.net/weixin_46143152/article/details/122691991)
  
  <img src="../img/projects/ocr.png" alt="Image 15" style="width: auto;height: 300px;">

- [工程光学实验平台 (matlab)](https://blog.csdn.net/weixin_46143152/article/details/122694389)
  
  <img src="../img/projects/optics.gif" alt="Image 16" style="width: auto;height: 300px;">
