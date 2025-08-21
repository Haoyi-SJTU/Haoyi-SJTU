

### 🙋 Haoyi Song

<p>&emsp;&emsp;PhD student in Shanghai Jiao Tong University</p>
<p>&emsp;&emsp;email: songhaoyi@sjtu.edu.cn</p>

### 🏢 Education Experience

<img align="right" width="88" src="https://vi.sjtu.edu.cn/img/base/Logo.png" />

- `PhD` Institute of Robotics, School of Mechanical Engineering, Shanghai Jiao Tong University

     📌 09/2020 – Present  &emsp; 📍 Shanghai

  - Advisor: [Prof.Xiangyang Zhu](https://me.sjtu.edu.cn/teacher_directory1/zhuxiangyang.html)
  - Research: Vibration suppression of hyper-redundant robots (Multimodal Perception, Robotics, etc)

<img align="right" width="88" src="https://ooo.0x0.ooo/2025/08/21/OfcWbX.png" />

- `BA` Mechanical Engineering, School of Mechanical Engineering, Southeast University

     📌 09/2016 – 06/2020  &emsp; 📍 Shanghai

  - GPA: 3.597/4.0
  - Rank: 16/183

### 📃 Research Project

#### Residual Learning for Robotic Arm Motion (ongoing)

  - Compensation for motion errors introduced by gaps, friction, and unmodeled factors in hyper-redundant robots.
    
  - Utilize force sensors, joint encoders, and IMU data. Kinematic + data-driven modeling; construct a ResNet deep residual network to learn kinematic residuals; build a simulation environment based on physical properties. The output motion residuals are used to correct the control variables. (**Python, MATLAB, Qt, CNN**)


#### Precise Positioning of Hyper-redundant Robot End

  - Accurate positioning of robots in constrained environments.

  - Use image and IMU data. Construct a visual-inertial odometry framework and a monocular image depth estimation method. In the frontend, process multi-modal sensor data through concurrent programming and ROS process scheduling. A monocular image depth estimation method based on triangulation principles is proposed. The backend processes multi-modal residuals based on optimization and outputs the six-degree-of-freedom pose of the robotic arm's end-effector. (**C++, ROS, OpenCV, PCL, Gurobi**)

  - The accuracy is improved by 4.5 times compared to DM-VIO. Published 1 [SCI journal paper](https://ieeexplore.ieee.org/document/10619992) and obtained 1 invention patent authorization.

Open-source Project:
[`lvi`](https://github.com/Haoyi-SJTU/lvi)

Project Video:

<p align="center">
  <a href="https://www.youtube.com/embed/FsOk0mO07QY">
    <img src="https://img.youtube.com/vi/FsOk0mO07QY/0.jpg" alt="点击观看视频">
  </a>
</p>

#### Disturbance-Resistance Performance Analysis of Hyper-Redundant Robots

  - Disturbance transmission analysis of hyper-redundant robots based on robot kinematics.

  - Propose a disturbance superellipsoid index, combining the robot's characteristics to quantitatively describe the impact of disturbances on the robot's joints. Derive the transfer function based on robot kinematics, and use optimization methods to filter the robot's redundant inverse solutions. The disturbance resistance performance index is used to select path planning results. Built in a CoppeliaSim simulation environment. (**C++, MATLAB, Gurobi, CoppeliaSim**)

  - Validated the effectiveness of the proposed method in both simulation and real-world scenarios. Submitted 1 SCI journal paper.

Project Video:

<p align="center">
  <a href="https://www.youtube.com/embed/s-bzES5cZls">
    <img src="https://img.youtube.com/vi/s-bzES5cZls/0.jpg" alt="点击观看视频">
  </a>
</p>

#### Coupler Target Recognition for Complex Field Environments

  - Train coupling recognition for outdoor complex operating conditions, providing targets and operation feedback for robotic arm manipulation.

  - Use structured light camera point cloud data. In the preprocessing stage, interference is eliminated using clustering, template matching, and other methods. The geometric features of the target coupling are encoded as genetic genes, and a genetic algorithm is designed to iteratively match the point cloud. (**C++, Python, PCL, Open3d**)

  - The project was deployed at a power station under a state-owned enterprise, achieving a high success rate (95%) in industrial environments. Published 1 [IEEE conference paper](https://ieeexplore.ieee.org/document/9665109) and obtained 1 invention patent authorization.

Project Video:

#### Collaborative Handling by Multiple Mobile Manipulator Robots

  - Multi-robot multi-modal sensor data collection and communication issues, providing perception data for multi-robot transportation.

  - Single-robot image and force data collection, based on the ROS multi-robot communication framework. (**C++, ROS**)

  - Validated the effectiveness of the method on multiple mobile manipulator robots. Submitted 1 SCI journal paper.

Project Video:

<p align="center">
  <a href="https://www.youtube.com/watch?v=Y8ZrnspIuBg">
    <img src="https://img.youtube.com/vi/Y8ZrnspIuBg/0.jpg" alt="点击观看视频">
  </a>
</p>

#### Humanoid Robotic Hand–Arm Grasp Coordination

  - Use a 6-degree-of-freedom robotic arm combined with a humanoid robotic hand to grasp objects, utilizing an external-mounted RGBD camera to extract object coordinates.
  - Coordinated with JAKA Robotics engineers for joint debugging, aimed at the company's external demonstrations.

Open-source Code: [`jaka_show`](https://github.com/Haoyi-SJTU/jaka_show)

Project Video:

<p align="center">
  <a href="https://youtu.be/w6cCVBafOrc">
    <img src="https://img.youtube.com/vi/w6cCVBafOrc/0.jpg" alt="点击观看视频">
  </a>
</p>

### 📃 Academic Achievements

#### Paper:

1. **H. Song**, J. Deng, W. Guo and X. Sheng, "Visual–Inertial Fusion With Depth Measuring for Hyper-Redundant Robot’s End Under Constrained Environment," in *IEEE Transactions on Instrumentation and Measurement (TIM)* with *IEEE I2MTC 2025*
2. **H. Song**, Z. Zhu, Z. Peng, W. Guo, C. Liu and X. Sheng, "Perturbation Hyper-ellipsoid: An Evaluation Method for the Anti-perturbation Performance of Hyper-redundant Robot," (Under Revision)
3. **H. Song**, Z. Chai, X. Sheng, Z. Xiong and X. Zhu, "Cylinder Fitting of Coupler Using an Improved Genetic Algorithm," in *International Conference on Mechatronics and Machine Vision in Practice (IEEE M2VIP 2021)*
4. H. Zhang, **H. Song**, W. Liu, Z. Xiong, X. Zhu, "A Novel Semi-Coupled Hierarchical Motion Planning Framework for Cooperative Transportation of Multiple Mobile Manipulators," (Under Revision)

#### Patents:

5. CN110102068A 一种无碳小车转向调节机构 (Authorized invention patent, first inventor)
6. CN110388430A 一种带有自锁结构的滚珠丝杆 (Authorized invention patent, first inventor)
7. CN116277154A 一种超冗余蛇形机械臂传感器快装 (Authorized invention patent, second inventor)
8. CN114995027A 一种相机云台 (Authorized invention patent)

### About My GitHub:

<div align="left"> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Haoyi-SJTU&hide=TeX,html&hide_title=true&hide_border=true&layout=compact&langs_count=6&text_color=000&icon_color=fff&bg_color=ccebc5,a8ddb5,7bccc4,4eb3d3&theme=graywhite" /> </div>


 <div>&nbsp;</div>
 
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=stay%20foolish,%20stay%20hungry;求知若渴，虚心若愚&center=true&size=27)](https://git.io/typing-svg)


