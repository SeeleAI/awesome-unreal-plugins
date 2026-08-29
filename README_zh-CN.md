<div align="center">

<h1>Unreal 开源插件精选</h1>
<img src="social-preview.svg" alt="Unreal 开源插件精选 — SeeleAI 精选维护" width="100%">
<p>由 SeeleAI 精选维护的 Unreal Engine 开源插件和可复用模块集合。</p>
<p><img src="https://img.shields.io/badge/Unreal%20Engine-5.x-0E1128?logo=unrealengine&logoColor=white" alt="Unreal Engine"> <img src="https://img.shields.io/badge/Curated%20by-SeeleAI-7C3AED" alt="Curated by SeeleAI"> <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="许可证：MIT"></a></p>
<p><a href="README.md">English</a> · <a href="README_zh-CN.md"><strong>中文</strong></a></p>
</div>

---

## 使用 AI 创建 Unreal 游戏

想更快制作原生 Unreal 游戏原型？SeeleAI 的 Seele Agent 可以将自然语言想法转化为浏览器中的可编辑 Unreal Engine 5 工程。

- 🧠 用自然语言描述游戏类型、场景、玩法机制或视觉方向，再通过 AI 生成的起始提示词塑造工程。
- 🏗️ 生成包含工程文件、Gameplay、摄像机、控制、环境和视觉方向的原生 `.uproject`，而不是非 Unreal 的演示页面。
- 🔍 通过 Pixel Streaming 在浏览器中查看运行中的游戏，迭代提示词，并在深入开发前检查生成结果。
- 🚀 继续进入 Unreal Editor，进行 Blueprint、C++、资产、平台和引擎级定制，然后打包、下载或发布结果。

如果希望快速从想法进入可玩的 Unreal 原型，可以试试 [SeeleAI Unreal Game Creator](https://www.seeles.ai/features/create/unreal-game)。

## 精选插件

> ★ Star 数量核验于 2026-08-29，后续可能随时间变化。

### 🧱 运行时渲染

- **[RealtimeMeshComponent](https://github.com/TriAxis-Games/RealtimeMeshComponent)** · ★ 1,755 · MIT · UE5

  面向 UE5 的运行时生成内容渲染插件，提供可复用的网格抽象，适合程序化几何体、流式数据和自定义运行时渲染管线。

### 🌐 程序化内容与世界

- **[PCGExtendedToolkit](https://github.com/PCGEx/PCGExtendedToolkit)** · ★ 684 · MIT · UE5

  补充 Unreal PCG 框架中常用的能力，覆盖图论、高级寻路、空间操作、过滤、资产管理等程序化世界制作工具。
- **[VoxelPluginFreeLegacy](https://github.com/VoxelPlugin/VoxelPluginFreeLegacy)** · ★ 1,756 · 未发现许可证文件 · UE4/UE5 旧版

  Voxel Plugin 的旧版免费版本，聚焦体素地形和程序化世界实验。用于新生产项目之前应先确认版本支持和项目维护状态。
- **[OceanProject](https://github.com/UE4-OceanProject/OceanProject)** · ★ 1,401 · 未发现许可证文件 · UE4.22/4.25 旧版

  环境插件工程，将海洋模拟、天空模拟、浮力、时间和鱼类系统组合在一起。适合原型验证大面积水环境，避免从零分别实现每个环境系统。

### 🏃 角色移动与动画

- **[ALS-Community](https://github.com/PanicPetal/ALS-Community)** · ★ 2,665 · MIT · UE5.4

  面向 UE5.4 的社区维护版 Advanced Locomotion System V4，提供复制支持、性能优化、额外功能和问题修复，适合第三人称移动项目。

### ⏳ 加载与工作流

- **[AsyncLoadingScreen](https://github.com/truong-bui/AsyncLoadingScreen)** · ★ 1,109 · MIT · UE4/UE5

  免费开源的加载界面系统，可在项目设置中配置，并能在打开新关卡时自动显示加载界面，也适用于不依赖关卡流送的加载流程。

### 🧪 语言与运行时集成

- **[UnrealCLR](https://github.com/nxrighthere/UnrealCLR)** · ★ 3,310 · MIT · UE4/UE5

  实现 Unreal Engine 与 .NET 6 的集成，将 C# 和托管代码工作流引入 UE 工程，适合评估原生 C++ 和 Blueprint 之外的 Gameplay、工具及互操作方案。
- **[UnrealSharp](https://github.com/UnrealSharp/UnrealSharp)** · ★ 1,915 · MIT · UE5

  面向 UE5 的 C# 开发插件，支持现代 .NET 和热重载。团队希望将托管代码用于 Gameplay 和编辑器扩展时，可与 UnrealCLR 对比评估。
- **[sluaunreal](https://github.com/Tencent/sluaunreal)** · ★ 1,978 · BSD-3-Clause · UE4/UE5

  面向 Unreal Engine 4 和 5 的 Lua 开发插件，适合在保留 Unreal 原生 C++ 基础的同时，引入轻量脚本层以加快迭代。

### 🔧 DCC 与 Shader 开发

- **[HoudiniEngineForUnreal](https://github.com/sideeffects/HoudiniEngineForUnreal)** · ★ 1,594 · BSD-3-Clause · UE5.6+

  面向 Unreal Engine 的 Houdini Engine 插件，将 Houdini 的程序化资产制作与 Unreal 场景和技术美术生产流程连接起来。
- **[UnrealEngineShaderPluginDemo](https://github.com/Temaran/UnrealEngineShaderPluginDemo)** · ★ 1,006 · MIT · UE4

  展示如何在 UE4 中实现 HLSL Pixel Shader 和 Compute Shader 的教程工程，更适合作为学习自定义 Shader 插件的聚焦参考，而非通用生产插件。

### 🧭 地理空间与 XR

- **[Cesium for Unreal](https://github.com/CesiumGS/cesium-unreal)** · ★ 1,232 · Apache-2.0 · UE5

  地理空间 3D 平台集成，可将全球 3D Tiles、地形、影像和真实坐标引入 Unreal，适合数字孪生、地图、仿真或大尺度位置可视化项目。
- **[VRExpansionPlugin](https://github.com/mordentral/VRExpansionPlugin)** · ★ 761 · MIT · UE4/5

  成熟的 UE VR 框架，包含可复用的交互与面向多人联机的系统。需要超出官方 VR 模板能力的项目可优先参考。

### 🧠 导航与 Gameplay AI

- **[DonAINavigation](https://github.com/VSZue/DonAINavigation)** · ★ 270 · MIT · UE4

  面向动态或程序化世界中飞行 AI 的 3D 动态寻路系统。当标准地面 NavMesh 无法描述角色移动空间时尤其值得参考。

### 🔌 源码管理与网络

- **[UEGitPlugin](https://github.com/ProjectBorealis/UEGitPlugin)** · ★ 817 · MIT · UE5

  重构版 Unreal Engine Git Source Control 插件，将 Git 操作接入编辑器工作流，适合评估 UE 工程的原生源码管理集成。
- **[SocketIOClient-Unreal](https://github.com/getnamo/SocketIOClient-Unreal)** · ★ 977 · MIT · UE4

  Unreal 的 Socket.IO 客户端集成，适合将游戏或可视化应用连接到实时 Web 服务、事件驱动后端和面向浏览器的系统。
- **[VaRest](https://github.com/ufna/VaRest)** · ★ 1,133 · MIT · UE4

  Unreal 的 REST API 与 JSON 通信插件，适合作为 Blueprint 友好的 HTTP 后端和 Web 服务集成参考；采用前请确认其当前引擎版本支持情况。

### 📦 打包与异步工作流

- **[HotPatcher](https://github.com/hxhb/HotPatcher)** · ★ 1,506 · MIT · UE4/UE5

  Unreal 热更新管理与打包插件，适合研究如何围绕 UE 工程组织补丁生成、内容打包和面向更新的交付流程。
- **[ue5coro](https://github.com/landelare/ue5coro)** · ★ 1,103 · BSD-3-Clause · UE4/UE5

  深度集成 Unreal Engine 4 和 5 的 C++20 协程插件。当异步 Gameplay 或工具逻辑使用结构化协程比回调链更清晰时值得考虑。

## 使用前检查

使用插件前，请查看许可证、支持的 Unreal Engine 版本、目标平台、维护活跃度、文档和构建说明。列表中的项目归原作者所有，本仓库是独立的精选索引。

## 贡献

提交原始仓库链接、许可证、支持的 UE 版本和插件简介。
