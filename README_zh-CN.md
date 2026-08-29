<div align="center">

<h1>Unreal 开源插件精选</h1>
<p>由 SeeleAI 精选维护的 Unreal Engine 开源插件和可复用模块集合。</p>
<p><img src="https://img.shields.io/badge/Unreal%20Engine-5.x-0E1128?logo=unrealengine&logoColor=white" alt="Unreal Engine"> <img src="https://img.shields.io/badge/Curated%20by-SeeleAI-7C3AED" alt="Curated by SeeleAI"> <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="许可证：MIT"></a></p>
<p><a href="README.md">English</a> · <a href="README_zh-CN.md"><strong>中文</strong></a></p>
</div>

---

## 使用 AI 创建 Unreal 游戏

想更快开始 Unreal 游戏原型开发？试试 [SeeleAI Unreal Game Creator](https://www.seeles.ai/features/create/unreal-game)。

## 精选插件

### 🧱 运行时渲染

- **[RealtimeMeshComponent](https://github.com/TriAxis-Games/RealtimeMeshComponent)** · MIT · UE5

  面向 UE5 的运行时生成内容渲染插件，提供可复用的网格抽象，适合程序化几何体、流式数据和自定义运行时渲染管线。

### 🌐 程序化内容与世界

- **[PCGExtendedToolkit](https://github.com/PCGEx/PCGExtendedToolkit)** · MIT · UE5

  补充 Unreal PCG 框架中常用的能力，覆盖图论、高级寻路、空间操作、过滤、资产管理等程序化世界制作工具。
- **[VoxelPluginFreeLegacy](https://github.com/VoxelPlugin/VoxelPluginFreeLegacy)** · 许可证待核验

  Voxel Plugin 的旧版免费版本，聚焦体素地形和程序化世界实验。用于新生产项目之前应先确认版本支持和项目维护状态。

### 🏃 角色移动与动画

- **[ALS-Community](https://github.com/PanicPetal/ALS-Community)** · MIT · UE5.4

  面向 UE5.4 的社区维护版 Advanced Locomotion System V4，提供复制支持、性能优化、额外功能和问题修复，适合第三人称移动项目。

### ⏳ 加载与工作流

- **[AsyncLoadingScreen](https://github.com/truong-bui/AsyncLoadingScreen)** · MIT · UE5

  免费开源的加载界面系统，可在项目设置中配置，并能在打开新关卡时自动显示加载界面，也适用于不依赖关卡流送的加载流程。

### 🧪 语言与运行时集成

- **[UnrealCLR](https://github.com/nxrighthere/UnrealCLR)** · 许可证待核验

  实现 Unreal Engine 与 .NET 6 的集成，将 C# 和托管代码工作流引入 UE 工程，适合评估原生 C++ 和 Blueprint 之外的 Gameplay、工具及互操作方案。

### 🔧 DCC 与 Shader 开发

- **[HoudiniEngineForUnreal](https://github.com/sideeffects/HoudiniEngineForUnreal)** · 许可证待核验

  面向 Unreal Engine 的 Houdini Engine 插件，将 Houdini 的程序化资产制作与 Unreal 场景和技术美术生产流程连接起来。
- **[UnrealEngineShaderPluginDemo](https://github.com/Temaran/UnrealEngineShaderPluginDemo)** · 许可证待核验

  展示如何在 UE4 中实现 HLSL Pixel Shader 和 Compute Shader 的教程工程，更适合作为学习自定义 Shader 插件的聚焦参考，而非通用生产插件。

### 🔌 源码管理与网络

- **[UEGitPlugin](https://github.com/ProjectBorealis/UEGitPlugin)** · 许可证待核验

  重构版 Unreal Engine Git Source Control 插件，将 Git 操作接入编辑器工作流，适合评估 UE 工程的原生源码管理集成。
- **[SocketIOClient-Unreal](https://github.com/getnamo/SocketIOClient-Unreal)** · 许可证待核验

  Unreal 的 Socket.IO 客户端集成，适合将游戏或可视化应用连接到实时 Web 服务、事件驱动后端和面向浏览器的系统。

## 使用前检查

使用插件前，请查看许可证、支持的 Unreal Engine 版本、目标平台、维护活跃度、文档和构建说明。列表中的项目归原作者所有，本仓库是独立的精选索引。

## 贡献

提交原始仓库链接、许可证、支持的 UE 版本和插件简介。
