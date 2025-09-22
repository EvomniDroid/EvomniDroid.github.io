---
layout: archive                    # 页面布局：使用归档页面模板
title: "CV"                        # 页面标题：简历
permalink: /cv/                    # 页面永久链接：/cv/
author_profile: true               # 显示作者信息栏：启用
redirect_from:                     # 重定向设置：从以下路径重定向到当前页面
  - /resume                        # 从/resume重定向到本页面
---

{% include base_path %}            <!-- 包含基础路径配置 -->

<!-- 教育背景部分 -->
<span style="color: #800000;">Education</span>    <!-- 红色标题：教育背景 -->
======                                          <!-- 二级标题分隔线 -->
* 2021.9-2025.6: Dual Bachelor's Degree in Mechanical Electronics Engineering and Software Engineering
  <!-- 2021年9月-2025年6月: 机械电子工程与软件工程双学士学位 -->

<!-- 工作经历部分 -->
<span style="color: #800000;">Work experience</span>    <!-- 红色标题：工作经历 -->
======                                               <!-- 二级标题分隔线 -->
* 2024.6-2025.6: Research Intern in National Key Laboratory of Intelligent Technology and Systems, Tsinghua University
  <!-- 2024年6月-2025年6月: 清华大学智能技术与系统国家重点实验室研究实习生 -->
* 2024.11-2025.6: Research Intern in AIR Discover Lab, Tsinghua University
  <!-- 2024年11月-2025年6月: 清华大学AIR Discover实验室研究实习生 -->

<!-- 研究兴趣部分 -->
<span style="color: #800000;">Research interests</span>    <!-- 红色标题：研究兴趣 -->
======                                                  <!-- 二级标题分隔线 -->
* vision-language navigation              <!-- 视觉-语言导航 -->
* vision-language-action model            <!-- 视觉-语言-动作模型 -->
* Motion control of humanoid and quadruped robots    <!-- 人形和四足机器人运动控制 -->
* mobile manipulation                     <!-- 移动操作 -->



<!-- 技能部分 -->
<span style="color: #800000;">Skills</span>    <!-- 红色标题：技能 -->
======                                       <!-- 二级标题分隔线 -->
* SLAM: Familiar with 2D and 3D laser mapping algorithms, able to use radars like MID360, MID70, Robosense, AVIA to complete terrestrial and aerial mapping, as well as UAV/vehicle perception tasks. Knowledgeable about the context of 3D reconstruction based on deep learning, has experience with classic MVS and NeRF, and can quickly dive into a specific point of study.
  <!-- SLAM: 熟悉2D和3D激光建图算法，能够使用MID360、MID70、Robosense、AVIA等雷达完成地面和空中建图，以及无人机/车辆感知任务。了解基于深度学习的3D重建背景，具有经典MVS和NeRF经验，能够快速深入特定研究点。 -->

* UAV&UGV: Navigation algorithms for drones and unmanned vehicles can be deployed in various simulators, with familiarity in planning and actual deployment of gradient optimization, heuristic search, and PPO-based navigation algorithms.
  <!-- 无人机和无人车: 无人机和无人车的导航算法可以在各种仿真器中部署，熟悉梯度优化、启发式搜索和基于PPO的导航算法的规划和实际部署。 -->

* Reinforcement Learning: Understand basic white-box problems such as multi-armed bandits, Markov decision processes and their basic optimizations like action-value and state-value; basic black-box problems, Monte Carlo and Temporal Difference methods lacking P(s,a), introducing derivatives with respect to dl to optimize the policy itself, can be optimized in Unreal using PPO for basic ring crossing.
  <!-- 强化学习: 理解基本的白盒问题，如多臂老虎机、马尔可夫决策过程及其基本优化，如动作值和状态值；基本的黑盒问题，缺乏P(s,a)的蒙特卡洛和时序差分方法，引入关于dl的导数来优化策略本身，可以在Unreal中使用PPO进行基本的穿环优化。 -->

* English: CET-4 score 560, CET-6 score 493
  <!-- 英语: 大学英语四级560分，六级493分 -->

<!-- 基金项目部分 -->
## <span style="color: #800000;">Fund</span>    <!-- 红色二级标题：基金 -->

* 国家科技创新2030重大项目    <!-- 国家级重大项目 -->
  * 面向跨域异构自主无人系统的高端智能控制器集成验证（3710万元）
    <!-- 项目名称：面向跨域异构自主无人系统的高端智能控制器集成验证（总资金3710万元） -->
  * 多旋翼无人机-机械臂平台（600万元子课题）
    <!-- 子项目：多旋翼无人机-机械臂平台（子课题资金600万元） -->
  * 描述：面向开放通用智能控制器在物流、农业、安防、无人驾驶、水下作业等重点行业中规模化应用需求，研究高端控制器跨域强适应性与集成技术，突破自主无人系统智能控制器的环境适应性设计、加固与优化，及特定应用需求下的软硬件系统二次开发与专用算法设计等技术，在3类5种跨域异构自主无人系统上实现高端智能控制器的部署、集成和应用验证。
    <!-- 项目描述：详细说明项目的应用领域、技术要求和目标 -->
  * 成果：验证爆炸物识别、爆炸物处置等功能≥3种；SLAM最大可支持场景≥1000平方米；爆炸物感知目标检出率≥95%。
    <!-- 预期成果：具体的量化指标和性能要求 -->
  * 职责：在Jetson Orin NX上实现多种SLAM建图算法如ORB-SLAM纯视觉方案、FASTLIO激光方案等，在Altas国产设备上实现高精度SLAM建图可支持场景>1000平方米，通过局域网、ROS2实现多机通讯。使用D435I和睿尔曼机械臂完成手眼标定、物品抓取。
    <!-- 个人职责：具体的技术实现任务和责任分工 -->

* 国网浙江省电力有限公司科学技术项目    <!-- 企业合作项目 -->
  * 基于大模型的带电作业机器人智能人机交互关键技术研究(290万元)
    <!-- 项目名称和资金：基于大模型的带电作业机器人智能人机交互关键技术研究（290万元） -->

* 盛虹巡检防爆机器人    <!-- 工业应用项目 -->
  * 立项阶段    <!-- 项目状态：正在立项阶段 -->

<!-- 发表论文部分 -->
<span style="color: #800000;">Publications</span>    <!-- 红色标题：发表论文 -->
======                                            <!-- 二级标题分隔线 -->
## <span style="color: #800000;">PAPERS</span>    <!-- 红色二级标题：论文 -->

### 2025    <!-- 三级标题：2025年论文 -->

**Hao Z**, Shi F, Jia D, Yao J, Wei G, and Lu S. "VERSA-Nav: Versatile Object-Goal Navigation Across Environments using Lightweight Explicit Maps and Open-Vocabulary Scene Graphs," in RAL
<!-- 论文1: VERSA-Nav: 使用轻量级显式地图和开放词汇场景图的跨环境通用目标导航，发表于RAL -->

**Hao Z**, Yao J. "Real-Time Semantic Terrain Segmentation and Policy Switching for Autonomous Navigation in Complex Environments," in IROS
<!-- 论文2: 复杂环境中自主导航的实时语义地形分割和策略切换，发表于IROS -->

**Hao Z**, Yao J "DPSG: A Dynamic Physical Scene Graph for Long-Horizon Mobile Manipulation in Unstructured Environments," in ICRA
<!-- 论文3: DPSG: 非结构化环境中长期移动操作的动态物理场景图，发表于ICRA -->

**Hao Z**, Yao J "Semantic Consistency: The Missing Keystone for Cross-Scale Robot Navigation," in Science robotics
<!-- 论文4: 语义一致性: 跨尺度机器人导航的缺失基石，发表于Science robotics -->

### 2024    <!-- 三级标题：2024年论文 -->




<!-- 专利部分 -->
## <span style="color: #800000;">PATENTS</span>    <!-- 红色二级标题：专利 -->
<!-- **Hao Z** , Yang W, Yan Z, Yu Y, Wo K, Zhao C, Zhao W and Yang C. A type of viscometer[P]. 2023032800847340,2023-03-28.  -->
<!-- 注释掉的专利：粘度计专利申请，2023年 -->

Ting X, **Hao Z**, Xu S, Shuai D. A type of AGV cart carrying bracket[P]. CN219524077U,2023-08-15. 
<!-- 已授权专利：一种AGV小车承载支架，专利号CN219524077U，2023年8月15日 --> 




<!-- 项目经历部分 -->
<span style="color: #800000;">Project</span>    <!-- 红色标题：项目 -->
======                                        <!-- 二级标题分隔线 -->

* Autonomous exploration planning for drones    <!-- 项目1：无人机自主探索规划 -->
  * Description: A drone that achieves autonomous navigation, obstacle avoidance, and exploration mapping based on the fusion of visual and point cloud data.
    <!-- 描述：基于视觉和点云数据融合实现自主导航、避障和探索建图的无人机 -->
  * Results: Achieved shuttling and obstacle avoidance in environments with multiple obstacles like forests, completed 3D reconstruction of campus scenes.
    <!-- 结果：在森林等多障碍环境中实现穿梭和避障，完成校园场景3D重建 -->
  * Responsibilities: Complete the assembly of drone carbon fiber hardware, and carry out wiring and soldering of radar, cameras, industrial computers, power supplies, GPS, flight controllers, and other equipment. Use multiple ground stations such as Qground and Prometheus for comparative development attempts, completing point-to-point navigation and takeoff/landing based on ground stations. Implement remote communication methods such as SSH and NoMachine. Achieve Vins-Fusion positioning based on D435i and flight control IMU, deploy SLAM algorithms like Vins-mono and Orb-slam, and implement planning algorithms such as Ego-planner and Fast-panner. Innovatively use laser height measurement and two-dimensional mapping to complete indoor scene positioning and navigation in an integral form.
    <!-- 职责：完成无人机碳纤维硬件组装，进行雷达、摄像头、工控机、电源、GPS、飞控等设备的接线和焊接。使用Qground和Prometheus等多个地面站进行对比开发尝试，完成基于地面站的点对点导航和起降。实现SSH和NoMachine等远程通信方法。基于D435i和飞控IMU实现Vins-Fusion定位，部署Vins-mono和Orb-slam等SLAM算法，实现Ego-planner和Fast-panner等规划算法。创新性地使用激光测高和二维建图以一体化形式完成室内场景定位和导航。 -->

* Autonomous navigation robot based on SLAM and computer vision    <!-- 项目2：基于SLAM和计算机视觉的自主导航机器人 -->
  * Description: Deploy SLAM algorithms using the ROS framework, achieving autonomous navigation based on LiDAR and depth cameras, and completing both simulation environments and real experiments.
    <!-- 描述：使用ROS框架部署SLAM算法，基于激光雷达和深度相机实现自主导航，完成仿真环境和真实实验 -->
  * Results: Results: Achieved campus-level autonomous driving based on prior maps in common scenarios such as ordinary cement and asphalt roads.
    <!-- 结果：在普通水泥路面和沥青路面等常见场景中基于先验地图实现校园级别的自主驾驶 -->
  * Responsibilities: Based on the Ackermann steering model, encapsulate the lower layers into a callable SDK, implementing 2D and 3D navigation using Autoware and movebase respectively. Visually, achieve AR tag recognition, KCF tracking, human skeletal recognition tracking, specific sign recognition based on YOLO, gesture control, and pure visual mapping and navigation based on RTAB-map. For mapping, implement 2D mapping using Gmapping, Hector, and Cartographer, and 3D mapping using LIO-SAM and LeGo-LOAM. Realize global path planning based on A* and Dijkstra, and local path planning based on point cloud expansion.
    <!-- 职责：基于阿克曼转向模型，将底层封装为可调用的SDK，分别使用Autoware和movebase实现2D和3D导航。视觉方面，实现AR标签识别、KCF跟踪、人体骨骼识别跟踪、基于YOLO的特定标志识别、手势控制，以及基于RTAB-map的纯视觉建图和导航。建图方面，使用Gmapping、Hector和Cartographer实现2D建图，使用LIO-SAM和LeGo-LOAM实现3D建图。实现基于A*和Dijkstra的全局路径规划，以及基于点云扩展的局部路径规划。 -->




<!-- 获奖经历部分 -->
<span style="color: #800000;">Awards</span>    <!-- 红色标题：获奖 -->
======                                       <!-- 二级标题分隔线 -->
* 2021.12: Third Prize in the 13th National College Students Mathematics Competition of Shaanxi Province
  <!-- 2021年12月：第十三届全国大学生数学竞赛陕西省三等奖 -->
* 2022.03: S Award of the American College Student Mathematical Modeling Contest
  <!-- 2022年3月：美国大学生数学建模竞赛S奖 -->
* 2022.07: 2022 China Artificial Intelligence Challenge Provincial Second Prize
  <!-- 2022年7月：2022中国人工智能挑战赛省级二等奖 -->
* 2022.08: National Second Prize of the 15th Artificial Intelligence Challenge
  <!-- 2022年8月：第十五届人工智能挑战赛国家级二等奖 -->
* 2023.05: First Prize in the Northwest Region of the 2023 China College Student Computer Design Competition
  <!-- 2023年5月：2023年中国大学生计算机设计大赛西北地区一等奖 -->

