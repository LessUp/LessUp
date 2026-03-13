---
layout: default
title: LessUp — 项目与文档入口
description: LessUp 的 GitHub Profile 与项目集合入口：研究方向、推荐阅读路径与核心仓库导航
---

# LessUp

LessUp 是一个围绕 AI 基础设施、高性能计算与系统工程实践展开的公开项目集合。`README.md` 继续承担 GitHub Profile 展示页角色，这个页面则作为 GitHub Pages 文档入口，帮助你快速理解项目版图、阅读路径与核心仓库。

## 项目定位

这里聚合了三类工作：一类是 CUDA / Triton 算子优化与性能实验，一类是 LLM 推理引擎与系统实现，另一类是面向实时协作、数字人或 GPU 计算可视化的应用型项目。站点首页的目标不是重复每个仓库的完整说明，而是告诉你应该先看哪一类、再进入哪个仓库继续阅读。

## 适合谁

- 想系统浏览 LessUp 项目版图并快速定位主题的读者
- 想从 CUDA kernel、LLM 推理或系统工程项目中选择一条学习路径的工程师
- 需要从公开项目里寻找实现参考、实验样例和进一步阅读入口的维护者

## 从哪里开始

1. 如果你关注 CUDA kernel 与性能优化，先看 [TensorCraft-HPC](https://github.com/LessUp/modern-ai-kernels)、[LLM-Speed](https://github.com/LessUp/llm-speed) 与 [SGEMM Optimization](https://github.com/LessUp/sgemm-optimization)。
2. 如果你更关注完整推理系统，继续看 [Tiny-LLM](https://github.com/LessUp/tiny-llm)、[Mini Inference Engine](https://github.com/LessUp/mini-inference-engine) 与 [Tiny-DL-Inference](https://github.com/LessUp/tiny-dl-inference)。
3. 如果你想看应用与系统工程项目，再查看 [MetaHuman](https://github.com/LessUp/MetaHuman)、[WebRTC](https://github.com/LessUp/WebRTC) 与 [Note Sync Now](https://github.com/LessUp/brave-sync-notes)。

## 推荐阅读路径

### 我想先看算子优化

- [TensorCraft-HPC](https://github.com/LessUp/modern-ai-kernels)
- [LLM-Speed](https://github.com/LessUp/llm-speed)
- [SGEMM Optimization](https://github.com/LessUp/sgemm-optimization)

### 我想先看推理引擎

- [Tiny-LLM](https://github.com/LessUp/tiny-llm)
- [Mini Inference Engine](https://github.com/LessUp/mini-inference-engine)
- [Tiny-DL-Inference](https://github.com/LessUp/tiny-dl-inference)

### 我想看实时应用与系统项目

- [MetaHuman](https://github.com/LessUp/MetaHuman)
- [WebRTC](https://github.com/LessUp/WebRTC)
- [Note Sync Now](https://github.com/LessUp/brave-sync-notes)

## 核心项目

| 类别 | 仓库 | 说明 |
|------|------|------|
| GPU 算子优化 | [TensorCraft-HPC](https://github.com/LessUp/modern-ai-kernels) | 现代 C++ / CUDA AI kernel library，覆盖 Elementwise、GEMM、Attention、Conv2D、Sparse 与 FP8 |
| GPU 算子优化 | [LLM-Speed](https://github.com/LessUp/llm-speed) | FlashAttention、FP16/INT8 GEMM、Python 绑定与属性测试 |
| 推理引擎 | [Tiny-LLM](https://github.com/LessUp/tiny-llm) | 轻量级 CUDA C++ LLM 推理引擎，关注 W8A16、KV Cache 与采样策略 |
| 推理引擎 | [Mini Inference Engine](https://github.com/LessUp/mini-inference-engine) | 从 Naive 到 Tensor Core 的 7 级 GEMM 优化学习项目 |
| 应用项目 | [Note Sync Now](https://github.com/LessUp/brave-sync-notes) | 端到端加密笔记同步与实时协作实验项目 |
| 应用项目 | [MetaHuman](https://github.com/LessUp/MetaHuman) | 面向 3D 数字人、语音交互与行为控制的应用工程 |

## 核心入口

| 类别 | 页面 | 说明 |
|------|------|------|
| 概览 | [README](README.md) | GitHub Profile 展示页，包含项目全景、经历、技术栈与联系信息 |
| 快速开始 | [GitHub 个人主页](https://github.com/LessUp) | 浏览全部公开仓库与最新动态 |
| 使用指南 | [本页项目导航](index.md) | 按主题快速进入相关仓库继续阅读 |
| 归档 | [changelog/CHANGELOG.md](changelog/CHANGELOG.md) | Profile 与 Pages 调整记录 |

## 归档与更新

- GitHub Profile 展示页：`README.md`
- Pages 变更记录：`changelog/CHANGELOG.md`
- GitHub 主页：`https://github.com/LessUp`
