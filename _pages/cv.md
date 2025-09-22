---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<span style="color: #800000;">Education</span>
======
* 2021.9-2025.6: Dual Bachelor's Degree in Mechanical Electronics Engineering and Software Engineering

<span style="color: #800000;">Work experience</span>
======
* 2024.6-2025.6: Research Intern in National Key Laboratory of Intelligent Technology and Systems, Tsinghua University
* 2024.11-2025.6: Research Intern in AIR Discover Lab, Tsinghua University

<span style="color: #800000;">Research interests</span>
======
* vision-language navigation
* vision-language-action model
* Motion control of humanoid and quadruped robots
* mobile manipulation



<span style="color: #800000;">Skills</span>
======
* SLAM: Familiar with 2D and 3D laser mapping algorithms, able to use radars like MID360, MID70, Robosense, AVIA to complete terrestrial and aerial mapping, as well as UAV/vehicle perception tasks. Knowledgeable about the context of 3D reconstruction based on deep learning, has experience with classic MVS and NeRF, and can quickly dive into a specific point of study.
* UAV&UGV: Navigation algorithms for drones and unmanned vehicles can be deployed in various simulators, with familiarity in planning and actual deployment of gradient optimization, heuristic search, and PPO-based navigation algorithms.
* Reinforcement Learning: Understand basic white-box problems such as multi-armed bandits, Markov decision processes and their basic optimizations like action-value and state-value; basic black-box problems, Monte Carlo and Temporal Difference methods lacking P(s,a), introducing derivatives with respect to dl to optimize the policy itself, can be optimized in Unreal using PPO for basic ring crossing.
* English: CET-4 score 560, CET-6 score 493

## <span style="color: #800000;">Fund</span>

* 国家科技创新2030重大项目
  * 面向跨域异构自主无人系统的高端智能控制器集成验证（3710万元）
  * 多旋翼无人机-机械臂平台（600万元子课题）
  * 描述：面向开放通用智能控制器在物流、农业、安防、无人驾驶、水下作业等重点行业中规模化应用需求，研究高端控制器跨域强适应性与集成技术，突破自主无人系统智能控制器的环境适应性设计、加固与优化，及特定应用需求下的软硬件系统二次开发与专用算法设计等技术，在3类5种跨域异构自主无人系统上实现高端智能控制器的部署、集成和应用验证。
  * 成果：验证爆炸物识别、爆炸物处置等功能≥3种；SLAM最大可支持场景≥1000平方米；爆炸物感知目标检出率≥95%。
  * 职责：在Jetson Orin NX上实现多种SLAM建图算法如ORB-SLAM纯视觉方案、FASTLIO激光方案等，在Altas国产设备上实现高精度SLAM建图可支持场景>1000平方米，通过局域网、ROS2实现多机通讯。使用D435I和睿尔曼机械臂完成手眼标定、物品抓取。

* 国网浙江省电力有限公司科学技术项目
  * 基于大模型的带电作业机器人智能人机交互关键技术研究(290万元)

* 盛虹巡检防爆机器人
  * 立项阶段

<span style="color: #800000;">Publications</span>
======
## <span style="color: #800000;">PAPERS</span>

### 2025

**Hao Z**, Shi F, Jia D, Yao J, Wei G, and Lu S. "VERSA-Nav: Versatile Object-Goal Navigation Across Environments using Lightweight Explicit Maps and Open-Vocabulary Scene Graphs," in RAL

**Hao Z**, Yao J. "Real-Time Semantic Terrain Segmentation and Policy Switching for Autonomous Navigation in Complex Environments," in IROS

**Hao Z**, Yao J "DPSG: A Dynamic Physical Scene Graph for Long-Horizon Mobile Manipulation in Unstructured Environments," in ICRA

**Hao Z**, Yao J "Semantic Consistency: The Missing Keystone for Cross-Scale Robot Navigation," in Science robotics

### 2024




## <span style="color: #800000;">PATENTS</span>
<!-- **Hao Z** , Yang W, Yan Z, Yu Y, Wo K, Zhao C, Zhao W and Yang C. A type of viscometer[P]. 2023032800847340,2023-03-28.  -->

Ting X, **Hao Z**, Xu S, Shuai D. A type of AGV cart carrying bracket[P]. CN219524077U,2023-08-15. 




<span style="color: #800000;">Project</span>
======

* Autonomous exploration planning for drones
  * Description: A drone that achieves autonomous navigation, obstacle avoidance, and exploration mapping based on the fusion of visual and point cloud data.
  * Results: Achieved shuttling and obstacle avoidance in environments with multiple obstacles like forests, completed 3D reconstruction of campus scenes.
  * Responsibilities: Complete the assembly of drone carbon fiber hardware, and carry out wiring and soldering of radar, cameras, industrial computers, power supplies, GPS, flight controllers, and other equipment. Use multiple ground stations such as Qground and Prometheus for comparative development attempts, completing point-to-point navigation and takeoff/landing based on ground stations. Implement remote communication methods such as SSH and NoMachine. Achieve Vins-Fusion positioning based on D435i and flight control IMU, deploy SLAM algorithms like Vins-mono and Orb-slam, and implement planning algorithms such as Ego-planner and Fast-panner. Innovatively use laser height measurement and two-dimensional mapping to complete indoor scene positioning and navigation in an integral form.

* Autonomous navigation robot based on SLAM and computer vision
  * Description: Deploy SLAM algorithms using the ROS framework, achieving autonomous navigation based on LiDAR and depth cameras, and completing both simulation environments and real experiments.
  * Results: Results: Achieved campus-level autonomous driving based on prior maps in common scenarios such as ordinary cement and asphalt roads.
  * Responsibilities: Based on the Ackermann steering model, encapsulate the lower layers into a callable SDK, implementing 2D and 3D navigation using Autoware and movebase respectively. Visually, achieve AR tag recognition, KCF tracking, human skeletal recognition tracking, specific sign recognition based on YOLO, gesture control, and pure visual mapping and navigation based on RTAB-map. For mapping, implement 2D mapping using Gmapping, Hector, and Cartographer, and 3D mapping using LIO-SAM and LeGo-LOAM. Realize global path planning based on A* and Dijkstra, and local path planning based on point cloud expansion.




<span style="color: #800000;">Awards</span>
======
* 2021.12: Third Prize in the 13th National College Students Mathematics Competition of Shaanxi Province
* 2022.03: S Award of the American College Student Mathematical Modeling Contest
* 2022.07: 2022 China Artificial Intelligence Challenge Provincial Second Prize
* 2022.08: National Second Prize of the 15th Artificial Intelligence Challenge
* 2023.05: First Prize in the Northwest Region of the 2023 China College Student Computer Design Competition

