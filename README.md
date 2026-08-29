<div align="center">

<h1>Awesome Unreal Plugins</h1>
<img src="social-preview.svg" alt="Awesome Unreal Plugins — curated by SeeleAI" width="100%">
<p>A curated collection of open-source Unreal Engine plugins and reusable modules.</p>
<p><img src="https://img.shields.io/badge/Unreal%20Engine-5.x-0E1128?logo=unrealengine&logoColor=white" alt="Unreal Engine"> <img src="https://img.shields.io/badge/Curated%20by-SeeleAI-7C3AED" alt="Curated by SeeleAI"> <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"></a></p>
<p><a href="README.md"><strong>English</strong></a> · <a href="README_zh-CN.md">中文</a></p>
</div>

---

## Build with AI

Want to prototype an Unreal game faster? Try [SeeleAI Unreal Game Creator](https://www.seeles.ai/features/create/unreal-game).

## Featured plugins

> ★ Star counts checked on 2026-08-29; they may change over time.

### 🧱 Runtime rendering

- **[RealtimeMeshComponent](https://github.com/TriAxis-Games/RealtimeMeshComponent)** · ★ 1,755 · MIT · UE5

  A UE5 plugin component for rendering runtime-generated content, with a reusable mesh abstraction for procedural geometry, streaming data, and custom runtime rendering pipelines.

### 🌐 Procedural content & worlds

- **[PCGExtendedToolkit](https://github.com/PCGEx/PCGExtendedToolkit)** · ★ 684 · MIT · UE5

  Fills in missing pieces around Unreal's PCG framework with graph theory, advanced pathfinding, spatial operations, filtering, asset management, and other tools for building procedural worlds.
- **[VoxelPluginFreeLegacy](https://github.com/VoxelPlugin/VoxelPluginFreeLegacy)** · ★ 1,756 · No license file found · UE4/UE5 legacy

  The legacy free edition of Voxel Plugin for Unreal, focused on voxel terrain and procedural-world experiments. Review version support and project status before using it in a new production project.
- **[OceanProject](https://github.com/UE4-OceanProject/OceanProject)** · ★ 1,401 · No license file found · UE4.22/4.25 legacy

  An environment plugin project that combines ocean simulation, sky simulation, buoyancy, time, and fish systems. It is a useful starting point for prototyping a large water environment rather than building each environmental system from scratch.

### 🏃 Character movement & animation

- **[ALS-Community](https://github.com/PanicPetal/ALS-Community)** · ★ 2,665 · MIT · UE5.4

  A replicated and optimized community version of Advanced Locomotion System V4 for UE5.4, with additional features and bug fixes for third-person locomotion projects.

### ⏳ Loading & workflow

- **[AsyncLoadingScreen](https://github.com/truong-bui/AsyncLoadingScreen)** · ★ 1,109 · MIT · UE4/UE5

  A free, open-source loading-screen system configurable from project settings. It can automatically display a loading screen when opening a new level, including workflows that do not rely on level streaming.

### 🧪 Language & runtime integration

- **[UnrealCLR](https://github.com/nxrighthere/UnrealCLR)** · ★ 3,310 · MIT · UE4/UE5

  Unreal Engine .NET 6 integration for bringing C# and managed-code workflows into UE projects. It is useful for evaluating alternative gameplay, tooling, and interoperability patterns beyond native C++ and Blueprint.
- **[UnrealSharp](https://github.com/UnrealSharp/UnrealSharp)** · ★ 1,915 · MIT · UE5

  A UE5 plugin that enables C# development on modern .NET with hot reload support. It is worth comparing with UnrealCLR when a team wants a current managed-code workflow for gameplay and editor extensions.
- **[sluaunreal](https://github.com/Tencent/sluaunreal)** · ★ 1,978 · BSD-3-Clause · UE4/UE5

  A Lua development plugin for Unreal Engine 4 and 5. It is useful for teams exploring a lightweight scripting layer for rapid iteration while retaining Unreal's native C++ foundation.

### 🔧 DCC & shader development

- **[HoudiniEngineForUnreal](https://github.com/sideeffects/HoudiniEngineForUnreal)** · ★ 1,594 · BSD-3-Clause · UE5.6+

  Houdini Engine plugin for Unreal Engine, designed to connect Houdini's procedural asset authoring with Unreal scenes and production workflows used by technical artists.
- **[UnrealEngineShaderPluginDemo](https://github.com/Temaran/UnrealEngineShaderPluginDemo)** · ★ 1,006 · MIT · UE4

  A tutorial project showing how to implement HLSL Pixel and Compute shaders in UE4. It is particularly useful as a focused learning reference for custom shader plugins rather than as a general-purpose production plugin.

### 🧭 Geospatial & XR

- **[Cesium for Unreal](https://github.com/CesiumGS/cesium-unreal)** · ★ 1,232 · Apache-2.0 · UE5

  A geospatial 3D platform integration for bringing global 3D Tiles, terrain, imagery, and real-world coordinates into Unreal. Use it for digital twins, mapping, simulation, or location-scale visualization projects.
- **[VRExpansionPlugin](https://github.com/mordentral/VRExpansionPlugin)** · ★ 761 · MIT · UE4/5

  A mature UE VR framework with reusable interaction and multiplayer-oriented systems. It is a strong reference for projects that need more than the stock VR template.

### 🧠 Navigation & gameplay AI

- **[DonAINavigation](https://github.com/VSZue/DonAINavigation)** · ★ 270 · MIT · UE4

  A 3D dynamic pathfinding system designed for flying AI in dynamic or procedural worlds. It is especially relevant when standard ground-based navigation meshes do not describe the movement space.

### 🔌 Source control & networking

- **[UEGitPlugin](https://github.com/ProjectBorealis/UEGitPlugin)** · ★ 817 · MIT · UE5

  A refactored Unreal Engine Git Source Control plugin that brings Git operations into the editor workflow. It is relevant to teams evaluating native source-control integration for UE projects.
- **[SocketIOClient-Unreal](https://github.com/getnamo/SocketIOClient-Unreal)** · ★ 977 · MIT · UE4

  Socket.IO client integration for Unreal, useful for connecting a game or visualization application to real-time web services, event-driven backends, and browser-facing systems.
- **[VaRest](https://github.com/ufna/VaRest)** · ★ 1,133 · MIT · UE4

  A REST API and JSON communication plugin for Unreal Engine. It is a practical reference for Blueprint-friendly HTTP integration with game backends and web services; verify its current engine support before adoption.

### 📦 Packaging & asynchronous workflows

- **[HotPatcher](https://github.com/hxhb/HotPatcher)** · ★ 1,506 · MIT · UE4/UE5

  A hot-update management and packaging plugin for Unreal. It is useful for studying how patch generation, content packaging, and update-oriented delivery can be organized around an Unreal project.
- **[ue5coro](https://github.com/landelare/ue5coro)** · ★ 1,103 · BSD-3-Clause · UE4/UE5

  A deeply integrated C++20 coroutine plugin for Unreal Engine 4 and 5. Consider it when asynchronous gameplay or tooling logic would be clearer as structured coroutines than as chained callbacks.

## What to check

Before adopting a plugin, review its license, supported Unreal Engine versions, target platforms, maintenance activity, documentation, and build instructions. Listed projects belong to their original authors; this repository is an independent curated index.

## Contributing

Open a pull request with the original repository URL, license information, supported UE version, and a brief description of the plugin.
