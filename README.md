

<h2 style="display: inline-block; border-bottom: 2px solid #000;">

## Hi there! This is Haoyi Song <img align="right" width="220" src="https://github.com/Haoyi-SJTU/Haoyi-SJTU/blob/main/figure/figure.jpg" />



PhD student. _IEEE Student Member_. Authorship of the textbook for Design and Manufacturing course (《设计与制造》教材) of SJTU.

Email: [songhaoyi@sjtu.edu.cn](mailto:songhaoyi@sjtu.edu.cn)
&emsp;&emsp;&emsp;&emsp;
Callsign： [BH4HIE](https://www.qrz.com/db/BH4HIE)

## Education Experience

<img align="right" width="66" src="https://vi.sjtu.edu.cn/img/base/Logo.png" />

- `PhD` Institute of Robotics, School of Mechanical Engineering, Shanghai Jiao Tong University

     📌 09/2020 – Present  &emsp; 📍 Shanghai

  - Advisor: [Prof. Xiangyang Zhu](https://me.sjtu.edu.cn/teacher_directory1/zhuxiangyang.html) and [Prof. Xinjun Sheng](https://me.sjtu.edu.cn/teacher_directory1/shengxinjun.html)
  - Research: precision enhancement of hyper-redundant robots, including neural networks, multimodal perception, robotics.

<img align="right" width="66" src="https://github.com/Haoyi-SJTU/Haoyi-SJTU/blob/main/figure/seu.png" />

- `BA` School of Mechanical Engineering, Southeast University

     📌 09/2016 – 06/2020  &emsp; 📍 Nanjing

  - Major： Mechanical Engineering
  - Awards: National Scholarship, Outstanding Graduate

## Research Project

### Residual Learning for Robot Motion Error(ongoing)

 - Focus: Compensation for motion errors in hyper-redundant robots.
 - Tools: residual networks, onnx, Python, MATLAB, Qt.
 - Approach: Kinematic + data-driven modeling. A deep residual network for kinematic residuals.


### Precise Positioning of Hyper-redundant Robot End

<img align="right" width="400" src="https://github.com/Haoyi-SJTU/Haoyi-SJTU/blob/main/figure/LVI_hrr.png" />

  - Focus: Accurate positioning in constrained environments.
  - Tools: IMU, Cameras, C++, ROS, OpenCV, PCL, Gurobi.
  - Approach: Visual-inertial odometry (VIO) and a monocular image depth estimation method. Optimization-based backend to process multi-modal residuals.
  - Result: 4.5x improvement in accuracy compared to DM-VIO. 1 SCI journal paper published. 1 invention patent granted.
  - Paper: [Visual–Inertial Fusion With Depth Measuring for Hyper-Redundant Robot’s End Under Constrained Environment](https://ieeexplore.ieee.org/document/10619992)
  - Video: [Video Demonstration](https://www.youtube.com/embed/FsOk0mO07QY)
  - Open-source Project: [`lvi`](https://github.com/Haoyi-SJTU/lvi)

### Disturbance-Resistance Performance Analysis of Hyper-Redundant Robots

<img align="right" width="400" src="https://github.com/Haoyi-SJTU/Haoyi-SJTU/blob/main/figure/dis.png" />

  - Focus: Analysis of disturbance resistance using robot kinematics.
  - Tools: C++, MATLAB, Gurobi, CoppeliaSim.
  - Approach: Propose a disturbance hyper-ellipsoid metric to quantify the impact of disturbances on robot joints, based on robotic kinematics.
  - Result: Posture optimization for disturbance resistance. 1 SCI journal paper under submission.


### Coupler Target Recognition for Complex Environments

<img align="right" width="400" src="https://github.com/Haoyi-SJTU/Haoyi-SJTU/blob/main/figure/1111111.png" />

  - Focus: Train coupling recognition for complex outdoor environments.
  - Tools: Structured light camera, C++, Python, PCL, Open3D.
  - Approach: Interference eliminated by clustering, template matching, etc. Propose a genetic algorithm for matching the point cloud. Geometric features encoded as genetic genes. 
  - Results: success rate of 95%, deployed to production.
  - Paper: [Cylinder Fitting of Coupler Using an Improved Genetic Algorithm](https://ieeexplore.ieee.org/document/9665109)
  - Video: [Video Demonstration](https://www.bilibili.com/video/BV1ZRtRz3E1A/)
  - Open-source Project: [`jaka_zu12_description`](https://github.com/Haoyi-SJTU/jaka_zu12_description)

### Collaborative Handling by Multiple Mobile Manipulators

<img align="right" width="400" src="https://github.com/Haoyi-SJTU/Haoyi-SJTU/blob/main/figure/123.png" />

  - Focus: Multi-robot multi-modal sensor data collection and communication issues, providing perception data for multi-robot transportation.
  - Tools: C++, ROS.
  - Approach: Single-robot image and force data collection through the ROS multi-robot communication framework. 
  - Results: Effectiveness validated on multiple mobile manipulators. 
  - Paper: [A novel semi-coupled hierarchical motion planning framework for cooperative transportation of multiple mobile manipulators](https://www.cambridge.org/core/journals/robotica/article/abs/novel-semicoupled-hierarchical-motion-planning-framework-for-cooperative-transportation-of-multiple-mobile-manipulators/25FA5B8B64030267388C0161E9E9CD03?utm_campaign=shareaholic)
  - Video: [Video Demonstration](https://www.youtube.com/watch?v=Y8ZrnspIuBg)
  - Open-source Project: [`jaka_velocity`](https://github.com/Haoyi-SJTU/jaka_velocity) [`apriltag_modified`](https://github.com/Haoyi-SJTU/apriltag)


### Humanoid Robotic Hand–Arm Grasp Coordination

<img align="right" width="400" src="https://github.com/Haoyi-SJTU/Haoyi-SJTU/blob/main/figure/111.png" />

  - Focus: A 6-DOF robot combined with a humanoid robotic hand to grasp objects, utilizing an external-mounted RGBD camera to extract object coordinates. Aimed at the JAKA company's external demonstrations.
  - Tools: C++, ROS, OpenCV, YOLO v5.
  - Video: [Video Demonstration](https://youtu.be/w6cCVBafOrc)
  - Open-source Project: [`jaka_show`](https://github.com/Haoyi-SJTU/jaka_show)  [`jaka_description`](https://github.com/Haoyi-SJTU/jaka_description)


## Academic Achievements

### Papers:

1. **H. Song**, J. Deng, W. Guo and X. Sheng, "Visual–Inertial Fusion With Depth Measuring for Hyper-Redundant Robot’s End Under Constrained Environment," in *IEEE Transactions on Instrumentation and Measurement (TIM)* with *IEEE International Instrumentation and Measurement Technology Conference (IEEE I2MTC 2025)*
2. **H. Song**, Z. Zhu, Z. Peng, W. Guo, C. Liu and X. Sheng, "Perturbation Hyper-ellipsoid: An Evaluation Method for the Anti-perturbation Performance of Hyper-redundant Robot," (Under Revision)
3. **H. Song**, Z. Chai, X. Sheng, Z. Xiong and X. Zhu, "Cylinder Fitting of Coupler Using an Improved Genetic Algorithm," in *IEEE International Conference on Mechatronics and Machine Vision in Practice (IEEE M2VIP 2021)*
4. H. Zhang, **H. Song**, W. Liu, Z. Xiong, X. Zhu, "A Novel Semi-Coupled Hierarchical Motion Planning Framework for Cooperative Transportation of Multiple Mobile Manipulators," in *Robotica*

### Authorized Patents:

5. ZL201910398073.3 – "Non-carbon steering adjustment mechanism". **H. Song**, Y. Ding, Y. Wang.
6. ZL201910699568.X – "Ball screw with self-locking structure". **H. Song**, R. Qian.
7. ZL202310301008.0 – "A sensor quick-mount for hyper-redundant robots". X. Sheng, **H. Song**, W. Guo.
8. ZL202210752423.3  – "A camera gimbal".

## About My GitHub:

<div align="left"> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Haoyi-SJTU&hide=TeX,html&hide_title=true&hide_border=true&layout=compact&langs_count=6&text_color=000&icon_color=fff&bg_color=ccebc5,a8ddb5,7bccc4,4eb3d3&theme=graywhite" /> </div><img align="left" width="300" src="https://github.com/Haoyi-SJTU/Haoyi-SJTU/blob/main/figure/about.png" />


 <div>&nbsp;</div>
 
<!-- [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=stay%20foolish,%20stay%20hungry;求知若渴，虚心若愚&center=true&size=27)](https://git.io/typing-svg) -->


