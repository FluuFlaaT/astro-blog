---
layout: '@/layouts/CommonPage.astro'
title: "Projects"
---

# Projects

## C / C++

### Qt

- SvgEditor
  - 提供自由画板，支持导入、导出含有图形和文字的SVG、PNG文件；
  - 实现了适配 Qt 框架的XML Parser，编译静态及动态库灵活调用
  - 注重工程规范，使用 CMake 管理组件，vcpkg 管理三方库，commit 和注释完善

- LianLianKan
  - 前后端分离，统一接口，支持热更换
  - 自学 Qt 框架并入门，开发多窗口 UI 界面，用户友好
- 桌面计算器
  - 引擎模块化为静态库
  - 支持 JSON/QSS 热加载配置，避免硬编码

### CUDA

- N-Body 并行模拟 - 基于 CUDA C++ 的天体粒子力学并行模拟
  - CPU 串行版耗时 1.67×10⁸ ms，GPU 并行版耗时 4.9×10⁷ ms（约 3.4× 加速）；
  - 学习CUDA C++ 及 GPU 并行计算原理，获得 NVIDIA 证书

## Python

- StepIntoYOLOv3
  - 完整复现 YOLOv3 主干网络，加载公开权重进行推理；
  - GPU 单张 416×416 图像推理 3 s，较 CPU（20 s）提速约 6.7×；
  - 负责环境搭建、模型加载、CUDA 优化和性能验证。