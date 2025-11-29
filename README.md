# Python Game 🚀 玩转滑雪 🎿

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pygame](https://img.shields.io/badge/Pygame-Supported-yellowgreen)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

## 介绍

一款基于 `Pygame` 库制作的趣味滑雪小游戏！在游戏中，玩家需要躲避障碍物并收集旗帜，挑战自我，欢迎体验！ 🎮

_**注意：本说明基于 Linux 操作系统 (如 Ubuntu) 环境，其他系统用户可酌情参考。**_

## 功能特性

✅ 简单易上手的操作方式
✅ 随机生成的障碍与积分机制
✅ 基于 Python 自编代码
✅ 支持自建代理加速下载

## 准备工作

运行此游戏需要以下条件：
- 操作系统：Linux（推荐），或其他支持 Python 运行的系统
- Python 运行环境
- `pip` 包管理工具

## 安装说明

### 下载游戏源码

1. 点击项目页面的绿色按钮 **[代码]**
2. 选择 **下载压缩包**
3. 等待下载完成，文件大小约 16MB
4. 如果下载速度过慢，可使用以下代理加速：
   - 推荐： [Moeyy Github Proxy](https://github.moeyy.xyz/)

### 安装运行依赖

配置运行库，确保以下运行库均已准备就绪：
- `pygame` （需手动安装）
- `sys` （Python 内置，不需要单独安装）
- `random` （Python 内置，不需要单独安装）

安装 `pygame`：
```bash
pip install pygame
```

### 运行游戏

1. 将下载好的 ZIP 文件解压到本地
2. 进入解压目录，右键选择 **在终端中打开**，或在终端手动导航至该目录
3. 输入以下指令运行游戏：
```bash
python main.py
```

_注：如果运行失败，请确保安装了正确的 Python 版本和依赖包。_

## 游戏玩法

打开游戏后：
- 玩家初始分数为 `100`，左右控制滑雪方向
- 目标是躲避松树障碍物，同时尽可能吃到小红旗
- 游戏失败条件：分数下降到 `0` 以下

**操作指南：**
- `←` 向左偏移一档，连按增加偏移距离
- `→` 向右偏移一档，连按增加偏移距离
- 每个方向可偏移两档

## 文件结构

```
├─ main.py          # 游戏入口
├─ assets/          # 游戏素材
└─ README.md        # 使用说明文档
```

## 关于

- 代码：纯原创
- 素材：来源于网络
- 欢迎 star 🌟 和 fork 🍴，提出建议一起优化项目！

## 许可协议

本项目采用 [MIT License](LICENSE) 开源，欢迎自由使用与分发。
