# 饶承坤 · Chengkun Rao

**具身智能 · 计算机视觉 · AI Agent 工程 · AI 全栈开发**

我是 **2027 届本科应届毕业生**，目前大四，近期研究机器人操作的世界-动作模型。

**正在寻找具身智能、计算机视觉、AI Agent 工程或 AI 全栈开发相关的工作机会。** 也欢迎技术交流与项目合作。[邮件联系我](mailto:lama@ckrao.dev)

[个人主页](https://lllllllama.github.io/) · [CSDN · 约 1.4 万粉丝](https://blog.csdn.net/2301_79168784) · [求职方向](#求职方向) · [近期项目](#近期项目) · [代表项目](#代表项目) · [实习经历](#实习经历) · [科研](#科研)

## 近期项目

### Physical WAM · 机器人操作的世界-动作模型

**进行中。** 基于 V-JEPA，从当前观测预测物体位姿、运动与相对关系，验证紧凑的未来物理表征能否用于生成机器人动作。

在一组小规模离线仿真实验中，未来查询数从 1,568 减到 196，**预测器计算量（FLOPs）约降 86%，训练循环耗时减少一半以上**。

## 求职方向

- **具身智能算法研发**。关注机器人操作、世界-动作模型和仿真评测，能参与动作策略的模型实现、训练和离线验证。[Physical WAM](#近期项目)
- **计算机视觉算法研发**。关注 RGB-D 感知、多模态融合、目标检测和语义分割，能用 PyTorch 完成模型实现、训练、消融实验和基准评测。[DDSkel](#科研)
- **AI Agent 应用与基础设施研发**。关注 Agent Harness、工具调用、MCP 和 Skills 集成，能开发带执行日志和评测记录的智能体工作流。[RigorPilot-Skills](#代表项目)
- **AI 全栈开发**。能开发 Web 界面、后端 API 和数据层，接入模型与 MCP 工具，并配置部署和自动更新。DeepTrender 展示了公开仪表盘、Flask API 和 SQLite 数据层的完整链路。[DeepTrender 在线演示](https://lllllllama.github.io/DeepTrender/)

## 代表项目

### RigorPilot-Skills · 科研智能体与实验复现

[![RigorPilot-Skills 的 GitHub 星标](https://img.shields.io/github/stars/lllllllama/RigorPilot-Skills?style=flat-square&logo=github&label=Stars)](https://github.com/lllllllama/RigorPilot-Skills/stargazers)

**[skills.sh 累计约 460 万次安装](https://www.skills.sh/lllllllama/rigorpilot-skills)**（2026-11-20）

我独立开发的深度学习复现工具。Agent 解析 README，Python 执行命令并记录日志和指标。**Trusted / Explore** 分开运行基线复现与研究探索，结果可通过标注版 README 和结构化记录回溯。

[源码](https://github.com/lllllllama/RigorPilot-Skills) · [可核验的复现案例](https://github.com/lllllllama/RigorPilot-Skills#examples)

### PICO ElderCare VR/MR

我主导实机交互和追踪层开发，统一腕部追踪器与手柄的位姿接口，支持追踪丢失时切换来源。也搭建了 Codex Skill 实机复测流程，用头显第一视角画面诊断问题并回到设备验证。[项目源码](https://github.com/lllllllama/eldercare-vr)

### DeepTrender · AI 论文趋势分析与 MCP 服务

我独立开发的科研数据系统，接入 arXiv、OpenReview 等四个来源，分层保存原始数据、去重论文和趋势分析。通过 MCP、REST API 和在线仪表盘提供查询。2026 年 5 月公开快照收录 **142,263 条结构化论文记录**。

[源码](https://github.com/lllllllama/DeepTrender) · [在线仪表盘](https://lllllllama.github.io/DeepTrender/)

### xget · 开发者资源访问基础设施

[![xget 上游仓库的 GitHub 星标](https://img.shields.io/github/stars/xixu-me/xget?style=flat-square&logo=github&label=Stars)](https://github.com/xixu-me/xget/stargazers)
[![xget 曾登上 GitHub Trending JavaScript 日榜第 3 名](https://img.shields.io/badge/GitHub%20Trending%20%28JavaScript%29-%233-F59E0B?style=flat-square&logo=github)](https://trendshift.io/repositories/14768)

我是 xget 的**两位主要贡献者之一**。项目统一路由 GitHub、Hugging Face、软件包和容器镜像请求，支持分段下载与按平台缓存。上游仓库有 **8,000+ GitHub 星标**。[上游仓库](https://github.com/xixu-me/xget)

### SSHFerry · SSH/SFTP 文件传输工作台

我独立开发的多会话传输工具。针对高延迟 SSH 链路使用连接复用、SFTP 流水线预读、分块并行和断点续传。[源码](https://github.com/lllllllama/SSHFerry)

### GrillRadar · 多智能体面试准备

六个角色 Agent 根据简历与目标岗位或研究方向生成问题，经过去重和质量过滤后汇总为面试报告。[源码与报告示例](https://github.com/lllllllama/GrillRadar)

## 实习经历

### 同元软控

**具身智能应用研究实习生** · 2026.09 起

为具身智能仿真平台开发 Agent 接口，完成调用联调与测试。参与开源模型在目标环境中的迁移、复现和调优，并验证模型运行情况。

### 上海悦心健康集团

**AI 技术实习生** · 2026.05–2026.09

在研发部主导 PICO 原型的实机交互和动作追踪，处理追踪抖动、短时丢失和坐标系变化。把头显第一视角接入 Codex Skill，用于定位交互问题和实机复测。[项目详情](#pico-eldercare-vrmr)

### 上海交通大学

**科研助理（实习）** · 主动健康战略与发展研究院 · 2025.07–2025.10

参与可穿戴设备与智能健康管理研究，协助讨论研究方案、组织实验和编写阶段性研究材料。

## 科研

### DDSkel · 自然图像物体骨架检测

**第一作者 · arXiv 预印本。** 我提出以深度为主、轻量 RGB 分支为辅的物体骨架检测方法，负责实现、训练和评测。v2 在四个基准上取得对比方法中的最高 ODS F-measure，SymPASCAL 为 **0.644**，高出次优方法 **0.062**。

[arXiv 预印本](https://arxiv.org/abs/2608.16367v2 "Depth-Dominant Skeleton Detection for Natural Scenes") · [实验结果](https://arxiv.org/html/2608.16367v2#S4.SS3.SSS1)

## 联系方式

**邮箱** · [lama@ckrao.dev](mailto:lama@ckrao.dev)
