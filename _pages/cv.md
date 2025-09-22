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
* 2024.11-2025.6: Research Intern in AIR discover lab, Tsinghua University

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

*国家科技创新2030重大项目
  *High-end intelligent controller integration and verification for cross-domain heterogeneous autonomous unmanned systems (37.1 million yuan)
  *Multi-rotor drone - robotic arm platform (6 million yuan sub-project)
  *Description: Aimed at the large-scale application needs of open general intelligent controllers in key industries such as logistics, agriculture, security, unmanned driving, and underwater operations, this research focuses on high-end controller cross-domain strong adaptability and integration technology. It seeks to break through the environmental adaptability design, reinforcement and optimization of intelligent controllers for autonomous unmanned systems, as well as the secondary development of hardware and software systems and the design of specialized algorithms under specific application requirements. The goal is to implement the deployment, integration, and application verification of high-end intelligent controllers on 3 categories and 5 types of cross-domain heterogeneous autonomous unmanned systems.
  *Results: Verification of at least 3 functions such as explosive detection and disposal; SLAM can support scenes of up to 1000 square meters; Explosive detection target detection rate ≥ 95%.
  *Responsibilities: Implement various SLAM mapping algorithms such as ORB-SLAM pure visual solution and FASTLIO laser solution on Jetson Orin NX, achieve high-precision SLAM mapping on Altas domestic devices that can support scenes over 1000 square meters, and enable multi-machine communication through local area network and ROS2. Use D435I and Reeman robotic arm to complete hand-eye calibration and object grasping.


<span style="color: #800000;">Publications</span>
======
## <span style="color: #800000;">PAPERS</span>
### 2025
**Feng L**, Gui L, Xu W, et al. "Locomotion Joint Angle and Moment Estimation With Soft Wearable Sensors for Personalized Exosuit Control," in IEEE Transactions on Neural Systems and Rehabilitation Engineering, vol. 33, pp. 1048-1060, 2025, doi: 10.1109/TNSRE.2025.3547361.

### 2024
**Feng L**, Yu L, Lyu H, Yang C, Liu X, Zhou C, and Yang W. Synergy in motion: Exploring the similarity and variability of muscle synergy patterns in healthy individuals, Human Movement Science, vol. 98, p. 103300, 2024, doi: 10.1016/j.humov.2024.103300.

**Feng L**, Gui L, Wang X, et al. Force Calibration of Soft-Sensing Unit for Flexible Exoskeleton[C]//2024 6th International Conference on Data-driven Optimization of Complex Systems (DOCS). IEEE, 2024: 358-364.



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

