---
layout: archive                    # 页面布局：使用归档页面模板
title: "Projects"                  # 页面标题：项目展示
permalink: /Projects/              # 页面永久链接：/Projects/
author_profile: true               # 显示作者信息栏：启用
redirect_from:                     # 重定向设置：从以下路径重定向到当前页面
  - /resume                        # 从/resume重定向到本页面
---

{% include base_path %}            <!-- 包含基础路径配置 -->

## Research Projects                <!-- 二级标题：研究项目 -->

<!-- 研究方向介绍段落 -->
Our research focuses on robotics, autonomous systems, and human-robot interaction. Below are our key projects with demonstration videos:
<!-- 我们的研究专注于机器人技术、自主系统和人机交互。以下是我们的关键项目及演示视频： -->

---                                   <!-- 分隔线：项目内容开始 -->

### 🚁 Unmanned Aerial Vehicle (UAV) Systems    <!-- 三级标题：无人机系统项目 -->

#### Battery Quick Replacement System for UAV    <!-- 四级标题：无人机电池快速更换系统 -->
**Project Overview:** Development of a low-cost, high-precision battery quick change system for UAVs to reduce operational costs and improve efficiency.
<!-- 项目概述：开发低成本、高精度的无人机电池快速更换系统，以降低运营成本并提高效率 -->

**Key Features:**                               <!-- 关键特性列表 -->
- GPS navigation system integrated with UAV vision    <!-- GPS导航系统与无人机视觉集成 -->
- External positioning device with four positioning rods    <!-- 带有四个定位杆的外部定位装置 -->
- Automatic hovering and positioning calibration    <!-- 自动悬停和位置校准 -->
- Special battery box design for rapid replacement    <!-- 用于快速更换的特殊电池盒设计 -->

<!-- 视频容器：居中显示，上下边距20px -->
<div style="display:flex;justify-content:center;margin:20px 0;">
<video width="600" controls>           <!-- 视频播放器：宽度600px，显示控制条 -->
  <source src="/images/publications/UAV/UAV.mp4" type="video/mp4">    <!-- 视频源：UAV项目演示视频 -->
  Your browser does not support the video tag.    <!-- 浏览器不支持视频时的提示信息 -->
</video>
</div>

---                                   <!-- 分隔线：项目间分隔 -->

### 🦾 Flexible Exoskeleton and Wearable Sensing    <!-- 三级标题：柔性外骨骼和可穿戴传感项目 -->

#### Soft Sensing Unit for Flexible Exoskeleton    <!-- 四级标题：柔性外骨骼的软传感单元 -->
**Project Overview:** Development of advanced force calibration and prediction systems for soft stretch sensors using deep learning techniques.
<!-- 项目概述：使用深度学习技术开发先进的软拉伸传感器力校准和预测系统 -->

**Key Technologies:**                              <!-- 关键技术列表 -->
- Deep learning-based force calibration           <!-- 基于深度学习的力校准 -->
- Soft stretch sensor integration                 <!-- 软拉伸传感器集成 -->
- Real-time force prediction algorithms           <!-- 实时力预测算法 -->
- Flexible exoskeleton control systems           <!-- 柔性外骨骼控制系统 -->

<!-- 视频容器：DOCS项目演示视频 -->
<div style="display:flex;justify-content:center;margin:20px 0;">
<video width="600" controls>           <!-- 视频播放器：宽度600px，显示控制条 -->
  <source src="/images/publications/DOCS/DOCS.mp4" type="video/mp4">    <!-- 视频源：DOCS项目演示视频 -->
  Your browser does not support the video tag.    <!-- 浏览器不支持视频时的提示信息 -->
</video>
</div>

#### Personalized Exoskeleton Control System      <!-- 四级标题：个性化外骨骼控制系统 -->
**Project Overview:** Locomotion joint angle and moment estimation using soft wearable sensors for personalized exoskeleton control.
<!-- 项目概述：使用软可穿戴传感器进行运动关节角度和力矩估计，用于个性化外骨骼控制 -->

**Research Highlights:**                          <!-- 研究亮点列表 -->
- Flexible sensing system for accurate joint prediction    <!-- 用于精确关节预测的柔性传感系统 -->
- LSTM and CNN models for real-time estimation    <!-- 用于实时估计的LSTM和CNN模型 -->
- Personalized assistance based on individual gait patterns    <!-- 基于个体步态模式的个性化辅助 -->
- Significant improvements in mobility and comfort    <!-- 在移动性和舒适性方面的显著改善 -->

##### Data Collection Process              <!-- 五级标题：数据收集过程 -->
<!-- 视频容器：数据收集过程演示 -->
<div style="display:flex;justify-content:center;margin:20px 0;">
<video width="600" controls>           <!-- 视频播放器：宽度600px，显示控制条 -->
  <source src="/images/publications/TNSRE/Data_collection_LOCO.mp4" type="video/mp4">    <!-- 视频源：数据收集过程视频 -->
  Your browser does not support the video tag.    <!-- 浏览器不支持视频时的提示信息 -->
</video>
</div>

##### Personalized Assistance Demonstration    <!-- 五级标题：个性化辅助演示 -->
<!-- 视频容器：个性化辅助演示 -->
<div style="display:flex;justify-content:center;margin:20px 0;">
<video width="600" controls>           <!-- 视频播放器：宽度600px，显示控制条 -->
  <source src="/images/publications/TNSRE/Personalized.mp4" type="video/mp4">    <!-- 视频源：个性化辅助演示视频 -->
  Your browser does not support the video tag.    <!-- 浏览器不支持视频时的提示信息 -->
</video>
</div>

---                                   <!-- 分隔线：模板结构开始 -->

### 🎯 Project Template Structure          <!-- 三级标题：项目模板结构 -->

<!-- 模板说明段落 -->
For each project, we follow this comprehensive documentation structure:
<!-- 对于每个项目，我们遵循以下综合文档结构： -->

#### 1. Project Header                     <!-- 四级标题：1. 项目标题部分 -->
```markdown                               <!-- 代码块开始：markdown格式示例 -->
### 🔬 [Project Name]                     <!-- 项目名称模板 -->
**Project Overview:** Brief description of the project goals and significance    <!-- 项目概述：项目目标和意义的简要描述 -->
**Duration:** [Start Date] - [End Date] (if applicable)    <!-- 项目持续时间：开始日期-结束日期（如适用） -->
**Team:** Principal investigators and collaborators        <!-- 团队：主要研究人员和合作者 -->
**Funding:** Grant information (if applicable)             <!-- 资助：资助信息（如适用） -->
```                                       <!-- 代码块结束 -->

#### 2. Technical Details               <!-- 四级标题：2. 技术细节部分 -->
```markdown                               <!-- 代码块开始：markdown格式示例 -->
**Key Technologies:**                     <!-- 关键技术 -->
- Technology 1: Brief description         <!-- 技术1：简要描述 -->
- Technology 2: Brief description         <!-- 技术2：简要描述 -->
- Technology 3: Brief description         <!-- 技术3：简要描述 -->

**Methodology:**                          <!-- 方法论 -->
- Step 1: Research approach               <!-- 步骤1：研究方法 -->
- Step 2: Implementation details          <!-- 步骤2：实施细节 -->
- Step 3: Validation methods              <!-- 步骤3：验证方法 -->
```                                       <!-- 代码块结束 -->

#### 3. Visual Documentation            <!-- 四级标题：3. 视觉文档部分 -->
```markdown                               <!-- 代码块开始：markdown格式示例 -->
**Demonstration Video:**                  <!-- 演示视频 -->
<div style="display:flex;justify-content:center;margin:20px 0;">    <!-- 视频容器：居中显示，上下边距20px -->
<video width="600" controls>              <!-- 视频播放器：宽度600px，显示控制条 -->
  <source src="/path/to/video.mp4" type="video/mp4">    <!-- 视频源：视频文件路径 -->
  Your browser does not support the video tag.          <!-- 浏览器不支持视频时的提示信息 -->
</video>
</div>

**Additional Media:**                     <!-- 附加媒体 -->
<div style="display:flex;justify-content:center;margin:20px 0;">    <!-- 图片容器：居中显示，上下边距20px -->
   <img src="/path/to/image.png" width="800" alt="Project Image" style="margin:auto;">    <!-- 图片：宽度800px，自动居中 -->
</div>
```                                       <!-- 代码块结束 -->

#### 4. Results and Impact              <!-- 四级标题：4. 结果和影响部分 -->
```markdown                               <!-- 代码块开始：markdown格式示例 -->
**Key Results:**                          <!-- 关键结果 -->
- Achievement 1: Quantified results      <!-- 成就1：量化结果 -->
- Achievement 2: Performance metrics     <!-- 成就2：性能指标 -->
- Achievement 3: Validation outcomes     <!-- 成就3：验证结果 -->

**Publications:**                         <!-- 发表论文 -->
- [Paper Title](link) - Conference/Journal Name, Year    <!-- 论文标题(链接) - 会议/期刊名称，年份 -->
- [Paper Title](link) - Conference/Journal Name, Year    <!-- 论文标题(链接) - 会议/期刊名称，年份 -->

**Impact:**                               <!-- 影响 -->
- Industrial applications                 <!-- 工业应用 -->
- Academic contributions                  <!-- 学术贡献 -->
- Future research directions             <!-- 未来研究方向 -->
```                                       <!-- 代码块结束 -->

#### 5. Additional Resources            <!-- 四级标题：5. 附加资源部分 -->
```markdown                               <!-- 代码块开始：markdown格式示例 -->
**Code Repository:** [GitHub Link](url)  <!-- 代码仓库：GitHub链接 -->
**Dataset:** [Data Access](url)          <!-- 数据集：数据访问链接 -->
**Documentation:** [Technical Docs](url) <!-- 文档：技术文档链接 -->
**Collaboration:** Contact information for partnerships    <!-- 合作：合作伙伴关系联系信息 -->
```                                       <!-- 代码块结束 -->

---                                   <!-- 分隔线：添加新项目指南开始 -->

### 📚 How to Add New Projects          <!-- 三级标题：如何添加新项目 -->

1. **Create Project Directory:** Add relevant media files to `/images/projects/[project-name]/`    <!-- 1. 创建项目目录：将相关媒体文件添加到指定路径 -->
2. **Upload Videos:** Ensure videos are in MP4 format for web compatibility    <!-- 2. 上传视频：确保视频为MP4格式以保证网页兼容性 -->
3. **Follow Template:** Use the structure above for consistency    <!-- 3. 遵循模板：使用上述结构保持一致性 -->
4. **Update Navigation:** Add project links to navigation menu if needed    <!-- 4. 更新导航：如需要，将项目链接添加到导航菜单 -->
5. **Test Media:** Verify all videos and images load correctly    <!-- 5. 测试媒体：验证所有视频和图片能正确加载 -->

### 🔧 Video Guidelines                 <!-- 三级标题：视频指南 -->

- **Format:** MP4 (recommended for web compatibility)    <!-- 格式：MP4（推荐用于网页兼容性） -->
- **Resolution:** 1080p or 720p for optimal loading     <!-- 分辨率：1080p或720p以获得最佳加载效果 -->
- **Duration:** Keep videos concise (2-5 minutes)       <!-- 时长：保持视频简洁（2-5分钟） -->
- **Compression:** Balance quality and file size        <!-- 压缩：平衡质量和文件大小 -->
- **Captions:** Add subtitles for accessibility when possible    <!-- 字幕：在可能的情况下添加字幕以提高可访问性 -->

---                                   <!-- 分隔线：页面结束 -->

<!-- 页面底部联系信息 -->
*For questions about our projects or collaboration opportunities, please [contact us](/contact/).*
<!-- 如有关于我们项目的问题或合作机会，请联系我们 -->