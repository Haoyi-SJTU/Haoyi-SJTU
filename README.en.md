<p align="right"><a href="./README.md"><kbd>　简体中文　↗　</kbd></a></p>

<img align="right" width="150" src="https://raw.githubusercontent.com/Haoyi-SJTU/Haoyi-SJTU/main/figure/figure.jpg" alt="Haoyi Song" />

# Haoyi Song

I am a PhD student at Shanghai Jiao Tong University, where I study how to improve the positioning accuracy of hyper-redundant robots. I am an IEEE Student Member and contributed to the university’s *Design and Manufacturing* (《设计与制造》) textbook.

[songhaoyi@sjtu.edu.cn](mailto:songhaoyi@sjtu.edu.cn) · Amateur radio callsign [BH4HIE](https://www.qrz.com/db/BH4HIE)

<br clear="all" />

[Education](#education) · [Research projects](#research-projects) · [Publications and patents](#publications-and-patents) · [GitHub](#github)

## Education

- <img width="24" src="https://vi.sjtu.edu.cn/img/base/Logo.png" alt="" /> **Shanghai Jiao Tong University** · PhD student  
  September 2020 – December 2026 (expected) · Shanghai  
  Institute of Robotics, School of Mechanical Engineering. Advised by [Prof. Xinjun Sheng](https://me.sjtu.edu.cn/teacher_directory1/shengxinjun.html).
- <img width="24" src="https://raw.githubusercontent.com/Haoyi-SJTU/Haoyi-SJTU/main/figure/seu.png" alt="" /> **Southeast University** · Bachelor’s degree  
  September 2016 – June 2020 · Nanjing  
  School of Mechanical Engineering.

## Research projects

<table>
  <thead>
    <tr><th>Project and preview</th><th>Method and resources</th></tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top"><strong>Learning to compensate for robot motion errors</strong><br><em>Ongoing</em></td>
      <td valign="top">A deep residual network learns the difference between the motion predicted by a kinematic model and the measured motion of a hyper-redundant robot. The controller uses this estimate to compensate for motion errors.<br><br>
        <strong>Tools</strong> · ONNX, Python, MATLAB, Qt<br>
        <a href="https://github.com/Haoyi-SJTU/cdhm_controller"><code>CDHM</code></a>
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>End-effector localization in confined spaces</strong><br><br>
        <img width="230" src="https://raw.githubusercontent.com/Haoyi-SJTU/Haoyi-SJTU/main/figure/LVI_hrr.png" alt="Visual–inertial localization for a hyper-redundant robot" />
      </td>
      <td valign="top">Visual–inertial odometry and depth estimates from monocular images track the position of a hyper-redundant robot’s end effector in confined spaces.<br><br>
        <strong>Tools</strong> · IMU, cameras, C++, ROS, OpenCV, PCL, Gurobi<br>
        <a href="https://ieeexplore.ieee.org/document/10619992">Paper</a> · <a href="https://www.youtube.com/watch?v=FsOk0mO07QY">Video</a> · <a href="https://github.com/Haoyi-SJTU/lvi"><code>lvi</code></a>
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>Disturbance resistance in hyper-redundant robots</strong><br><br>
        <img width="230" src="https://raw.githubusercontent.com/Haoyi-SJTU/Haoyi-SJTU/main/figure/dis.png" alt="Disturbance analysis for a hyper-redundant robot" />
      </td>
      <td valign="top">A disturbance hyper-ellipsoid derived from the robot’s kinematics quantifies its sensitivity to disturbances.<br><br>
        <strong>Tools</strong> · C++, MATLAB, Gurobi, CoppeliaSim, MuJoCo<br>
        <a href="https://doi.org/10.1007/s12555-026-00144-0">Paper</a> · <a href="https://youtu.be/LZfitKhQ1Bw">Video</a> · <a href="https://github.com/Haoyi-SJTU/DHE"><code>DHE</code></a>
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>Train coupler recognition outdoors</strong><br><br>
        <img width="230" src="https://raw.githubusercontent.com/Haoyi-SJTU/Haoyi-SJTU/main/figure/1111111.png" alt="Train coupler recognition project" />
      </td>
      <td valign="top">An improved genetic algorithm fits a cylinder to structured-light camera data to identify a train coupler in a complex outdoor scene.<br><br>
        <strong>Tools</strong> · Structured-light camera, C++, Python, PCL, Open3D<br>
        <a href="https://ieeexplore.ieee.org/document/9665109">Paper</a> · <a href="https://www.bilibili.com/video/BV1ZRtRz3E1A/">Video</a> · <a href="https://github.com/Haoyi-SJTU/jaka_zu12_description"><code>jaka_zu12_description</code></a>
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>Cooperative transport with mobile manipulators</strong><br><br>
        <img width="230" src="https://raw.githubusercontent.com/Haoyi-SJTU/Haoyi-SJTU/main/figure/123.png" alt="Cooperative transport with multiple mobile manipulators" />
      </td>
      <td valign="top">A ROS communication framework collects and shares data from multiple sensor types across robots, giving mobile manipulators the perception data they need to transport a load together.<br><br>
        <strong>Tools</strong> · C++, ROS<br>
        <a href="https://www.cambridge.org/core/journals/robotica/article/abs/novel-semicoupled-hierarchical-motion-planning-framework-for-cooperative-transportation-of-multiple-mobile-manipulators/25FA5B8B64030267388C0161E9E9CD03">Paper</a> · <a href="https://www.youtube.com/watch?v=Y8ZrnspIuBg">Video</a> · <a href="https://github.com/Haoyi-SJTU/jaka_velocity"><code>jaka_velocity</code></a> · <a href="https://github.com/Haoyi-SJTU/apriltag"><code>apriltag_modified</code></a>
      </td>
    </tr>
    <tr>
      <td valign="top"><strong>Hand–arm coordination for grasping</strong><br><br>
        <img width="230" src="https://raw.githubusercontent.com/Haoyi-SJTU/Haoyi-SJTU/main/figure/111.png" alt="Grasping with a robotic hand and arm" />
      </td>
      <td valign="top">An external RGB-D camera locates objects for a six-axis robot arm fitted with a humanoid hand. The system was developed for JAKA demonstrations.<br><br>
        <strong>Tools</strong> · C++, ROS, OpenCV, YOLOv5<br>
        <a href="https://youtu.be/w6cCVBafOrc">Video</a> · <a href="https://github.com/Haoyi-SJTU/jaka_show"><code>jaka_show</code></a> · <a href="https://github.com/Haoyi-SJTU/jaka_description"><code>jaka_description</code></a>
      </td>
    </tr>
  </tbody>
</table>

## Publications and patents

### Papers

1. **H. Song**, J. Deng, W. Guo and X. Sheng. [Visual–Inertial Fusion With Depth Measuring for Hyper-Redundant Robot’s End Under Constrained Environment](https://ieeexplore.ieee.org/document/10619992). *IEEE Transactions on Instrumentation and Measurement* (TIM) · IEEE International Instrumentation and Measurement Technology Conference (I2MTC 2025).
2. **H. Song**, Z. Zhu, Z. Peng, W. Guo, C. Liu, Y. Li and X. Sheng. [Disturbance Hyper-ellipsoid: A Metric for Evaluating Disturbance Resistance of Hyper-redundant Robots](https://doi.org/10.1007/s12555-026-00144-0). *International Journal of Control, Automation, and Systems*, 24, 2408–2421 (2026).
3. **H. Song**, W. Guo, C. Liu and X. Sheng. A Physics-Informed World Model for Cable-Length Residual Prediction in Cable-Driven Robots. *2026 IEEE International Conference on Robotics and Biomimetics* (ROBIO).
4. **H. Song**, Z. Chai, X. Sheng, Z. Xiong and X. Zhu. [Cylinder Fitting of Coupler Using an Improved Genetic Algorithm](https://ieeexplore.ieee.org/document/9665109). *IEEE International Conference on Mechatronics and Machine Vision in Practice* (M2VIP 2021).
5. H. Zhang, **H. Song**, W. Liu, Z. Xiong and X. Zhu. [A Novel Semi-Coupled Hierarchical Motion Planning Framework for Cooperative Transportation of Multiple Mobile Manipulators](https://www.cambridge.org/core/journals/robotica/article/abs/novel-semicoupled-hierarchical-motion-planning-framework-for-cooperative-transportation-of-multiple-mobile-manipulators/25FA5B8B64030267388C0161E9E9CD03). *Robotica*.
6. **H. Song**, J. Shi, C. Liu, W. Guo and X. Sheng. Physics-Informed Learning for Cable Residual Compensation in Cable-Driven Robots. *IEEE Robotics and Automation Letters* (under review).

### Granted patents

1. [Steering adjustment mechanism for a carbon-free vehicle](https://patents.google.com/patent/CN110102068B/en) · `ZL201910398073.3` · **H. Song**, Y. Ding, Y. Wang and H. Luo.
2. [Ball screw with a self-locking mechanism](https://patents.google.com/patent/CN110388430B/en) · `ZL201910699568.X` · **H. Song** and R. Qian.
3. [Quick-mount sensor mechanism for a hyper-redundant snake-like manipulator](https://patents.google.com/patent/CN116277154B/en) · `ZL202310301008.0` · X. Sheng, **H. Song** and W. Guo.
4. [Industrial camera gimbal with protection against dust and machining chips](https://patents.google.com/patent/CN114995027B/en) · `ZL202210752423.3` · T. Zhou, Z. Xiong, M. Tao, **H. Song**, L. Zhang, Y. Mei and Y. Yang.

## GitHub

<p align="center">
  <img width="300" src="https://raw.githubusercontent.com/Haoyi-SJTU/Haoyi-SJTU/main/figure/about.png" alt="Illustration from Haoyi Song’s GitHub profile" />
</p>

<p align="center">
  <a href="https://github.com/Haoyi-SJTU?tab=repositories">All repositories</a> ·
  <a href="https://github.com/Haoyi-SJTU?tab=repositories&amp;language=c%2B%2B">C++</a> ·
  <a href="https://github.com/Haoyi-SJTU?tab=repositories&amp;language=matlab">MATLAB</a> ·
  <a href="https://github.com/Haoyi-SJTU?tab=repositories&amp;language=python">Python</a>
</p>

---

<p align="center"><em>越过高山，越过平原，跨过奔腾的黄河长江</em></p>
