# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 项目概述

`dodge-the-creeps-3D` 是基于 Godot 4.x 的 3D 躲避游戏，参考 [Godot 官方 2D 教程](https://docs.godotengine.org/zh-cn/4.x/getting_started/first_2d_game/index.html) 改编为 3D 版本。

## 开发环境

- **引擎**: Godot 4.x
- **语言**: GDScript

## 操作命令

- **运行游戏**: 在 Godot 编辑器中打开项目，点击运行
- **导出游戏**: `项目` → `导出` → 选择预设 → `导出项目`

## 项目结构

```
├── art/              # 3D 模型 (.glb, .blend) 和材质 (.tres)
│   ├── player.glb    # 玩家模型
│   └── mob.glb      # 怪物模型
├── fonts/           # 字体文件（Montserrat）
├── project.godot    # 项目配置
└── icon.webp        # 应用图标
```

## 技术栈

- Godot 4.6
- GDScript
- 3D 渲染（MSAA 2x）
- GLTF/GLB 3D 模型格式

## 状态

项目目前处于初始阶段，仅包含资源和基础配置，等待场景和脚本开发。