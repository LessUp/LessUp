---
layout: default
title: LessUp — AI Infrastructure & HPC Developer
---

# 👨‍💻 LessUp

专注于 AI 基础设施与高性能计算的工程实践。

## 🔥 Research Focus

- **GPU Kernel Engineering** — CUDA/Triton kernel optimization, FlashAttention, GEMM, quantization
- **AI Inference Systems** — LLM inference engines, model quantization (W8A16/FP8), KV Cache
- **High-Performance Computing** — N-body simulation, ray tracing, image processing pipelines
- **Real-time Systems** — WebRTC signaling, real-time detection, digital human platform

## ⚡ GPU Kernel Optimization

| 项目 | 简介 |
|------|------|
| [TensorCraft-HPC](https://github.com/LessUp/modern-ai-kernels) | Modern C++17/CUDA AI kernel library — Elementwise, GEMM, FlashAttention, Conv2D, SpMV, FP8 |
| [SGEMM Optimization](https://github.com/LessUp/sgemm-optimization) | From naive 3-loop to Tensor Core — progressive SGEMM optimization |
| [Triton Fused Ops](https://github.com/LessUp/triton-fused-ops) | RMSNorm+RoPE fusion, Gated MLP fusion, FP8 GEMM with auto-tuning |
| [LLM-Speed](https://github.com/LessUp/llm-speed) | CUDA LLM kernel library — FlashAttention, FP16/INT8 GEMM with Tensor Core |

## 🧠 AI Inference Engines

| 项目 | 简介 |
|------|------|
| [Tiny-LLM](https://github.com/LessUp/tiny-llm) | Lightweight LLM inference — W8A16 quantization, KV Cache, multi-sampling |
| [Mini Inference Engine](https://github.com/LessUp/mini-inference-engine) | 7-level GEMM optimization (Naive→Tensor Core), MNIST demo |
| [Tiny-DL-Inference](https://github.com/LessUp/tiny-dl-inference) | WebGPU micro inference engine — Conv2d, kernel fusion, Im2Col |
| [YOLO-Toys](https://github.com/LessUp/YOLO-Toys) | Multi-model real-time vision — YOLO/DETR/OWL-ViT/BLIP |

## 🎮 GPU Computing & Simulation

| 项目 | 简介 |
|------|------|
| [CUDA Ray Tracer](https://github.com/LessUp/ray-tracer) | Pure CUDA ray tracer — Phong shading, path tracing, BVH |
| [N-Body Simulation](https://github.com/LessUp/n-body) | Million-particle GPU simulation — Barnes-Hut, Spatial Hash, CUDA-OpenGL interop |
| [Particle Fluid Sim](https://github.com/LessUp/particle-fluid-sim) | WebGPU real-time fluid simulation with compute shaders |
| [Mini-OpenCV](https://github.com/LessUp/mini-opencv) | CUDA image processing library |
| [Mini-ImagePipe](https://github.com/LessUp/mini-image-pipe) | DAG-based heterogeneous GPU image pipeline |

## 🌐 Applications

| 项目 | 简介 |
|------|------|
| [MetaHuman](https://github.com/LessUp/MetaHuman) | 3D digital human platform — Three.js, voice interaction |
| [WebRTC](https://github.com/LessUp/WebRTC) | Minimal WebRTC demo — Go WebSocket signaling |
| [Note Sync Now](https://github.com/LessUp/sync-notes) | E2E encrypted note sync — AES-256 |
| [Mind Gym](https://github.com/LessUp/mind-gym) | Browser-based memory training — N-back, PWA |

## 🛠️ Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | C++, CUDA, Python, Rust, Go, Bash |
| **AI & HPC** | PyTorch, Triton, cuBLAS, Tensor Core, WebGPU |
| **System** | Linux, Docker, Git, CMake, Nginx |
| **Web** | React, TypeScript, Vite, Tailwind, Three.js |

## 📫 Contact

- [GitHub](https://github.com/LessUp)
- [Email](mailto:jiashuai.shi@qq.com)
