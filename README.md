<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0077b6,00b4d8,90e0ef&height=220&section=header&text=Hi,%20I'm%20LessUp&fontSize=70&animation=fadeIn&fontAlignY=35&desc=AI%20Infrastructure%20%26%20HPC%20Developer&descAlignY=65&descAlign=60&fontColor=ffffff" width="100%" alt="Header" />

  <br/>

  <h2>LessUp · AI Infrastructure &amp; HPC Developer</h2>
  <p>
    Building efficient AI infrastructure, high-performance systems, and data pipelines.<br/>
    专注于 AI 基础设施与高性能计算的工程实践。
  </p>

  <br/>

  <p>
    ⚡ Focus: CUDA Kernel Optimization · LLM Inference · GPU Computing<br/>
    🌱 Currently exploring: AI inference acceleration &amp; large-scale pipeline orchestration<br/>
    📍 Open to: Research collaboration &amp; open-source co-building
  </p>

  <br/>

  <img src="https://img.shields.io/github/followers/LessUp?label=Followers&style=flat-square&color=2ea44f&logo=github" alt="Followers" />
  &nbsp;
  <img src="https://img.shields.io/github/stars/LessUp?affiliations=OWNER&style=flat-square&color=dbab09&logo=github" alt="Stars" />
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=LessUp&label=Profile%20views&color=0077b6&style=flat-square" alt="Views" />
  &nbsp;
  <img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FLessUp%2FLessUp&label=Visitors&countColor=%23e76f51&style=flat-square&labelColor=%23555555" alt="Visitors" />
  <br/>
  <p>
    <a href="#about">About</a> ·
    <a href="#projects">Projects</a> ·
    <a href="#experience">Experience</a> ·
    <a href="#tech-stack">Tech Stack</a> ·
    <a href="#stats">Stats</a> ·
    <a href="#contact">Contact</a>
  </p>
</div>

<br/>

---

<a id="about"></a>
### 👨‍💻 About Me / 关于我

> I build AI infrastructure and high-performance systems with C++/CUDA, Python, and Go.  
> 主要关注 AI 基础设施、GPU 算子优化与高性能计算等方向的工程实践。

- **GPU Kernel Engineering**: CUDA/Triton kernel optimization, FlashAttention, GEMM, quantization / GPU 算子优化
- **AI Inference Systems**: LLM inference engines, model quantization (W8A16/FP8), KV Cache / AI 推理系统
- **High-Performance Computing**: N-body simulation, ray tracing, image processing pipelines / 高性能计算
- **Real-time Systems**: WebRTC signaling, real-time detection, digital human platform / 实时系统

---

<a id="projects"></a>
### 🚀 Projects / 项目全景

#### ⚡ GPU Kernel Optimization / GPU 算子优化

<table>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/modern-ai-kernels">TensorCraft-HPC</a></h4>
      <p>Modern C++17/CUDA AI kernel library — Elementwise, GEMM, FlashAttention, Conv2D, SpMV, FP8 quantization</p>
      <p>
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++17" />
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/Tensor_Core-111827?style=flat-square&logo=nvidia&logoColor=white" alt="Tensor Core" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/sgemm-optimization">SGEMM Optimization</a></h4>
      <p>From naive 3-loop to Tensor Core — progressive SGEMM optimization reaching 40% cuBLAS</p>
      <p>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/WMMA-111827?style=flat-square&logo=nvidia&logoColor=white" alt="WMMA" />
        <img src="https://img.shields.io/badge/Roofline-4CC9F0?style=flat-square" alt="Roofline" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/triton-fused-ops">Triton Fused Ops</a></h4>
      <p>RMSNorm+RoPE fusion, Gated MLP fusion, FP8 GEMM with auto-tuning for Transformers</p>
      <p>
        <img src="https://img.shields.io/badge/Triton-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="Triton" />
        <img src="https://img.shields.io/badge/FP8-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="FP8" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/llm-speed">LLM-Speed</a></h4>
      <p>CUDA LLM kernel library — FlashAttention (online softmax), FP16/INT8 GEMM with Tensor Core</p>
      <p>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
        <img src="https://img.shields.io/badge/FlashAttn-111827?style=flat-square" alt="FlashAttention" />
      </p>
    </td>
  </tr>
</table>

#### 🧠 AI Inference Engines / AI 推理引擎

<table>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/tiny-llm">Tiny-LLM</a></h4>
      <p>Lightweight LLM inference engine — W8A16 quantization, KV Cache, multi-sampling strategies</p>
      <p>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++17" />
        <img src="https://img.shields.io/badge/INT8-4CC9F0?style=flat-square" alt="INT8" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/mini-inference-engine">Mini Inference Engine</a></h4>
      <p>7-level GEMM optimization (Naive→Tensor Core), reaching 72% cuBLAS with MNIST demo</p>
      <p>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++17" />
        <img src="https://img.shields.io/badge/FP16-76B900?style=flat-square" alt="FP16" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/tiny-dl-inference">Tiny-DL-Inference</a></h4>
      <p>WebGPU micro inference engine — Conv2d, kernel fusion, Im2Col, MNIST classification</p>
      <p>
        <img src="https://img.shields.io/badge/WebGPU-005A9C?style=flat-square&logo=webgpu&logoColor=white" alt="WebGPU" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/WGSL-4CC9F0?style=flat-square" alt="WGSL" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/YOLO-Toys">YOLO-Toys</a></h4>
      <p>Multi-model real-time vision — YOLO/DETR/OWL-ViT/BLIP with WebSocket streaming</p>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/YOLOv8-5E60CE?style=flat-square&logo=opencv&logoColor=white" alt="YOLOv8" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      </p>
    </td>
  </tr>
</table>

#### 🎮 GPU Computing & Simulation / GPU 计算与仿真

<table>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/ray-tracer">CUDA Ray Tracer</a></h4>
      <p>Pure CUDA ray tracer — Phong shading, path tracing, BVH acceleration, warp divergence optimization</p>
      <p>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/Path_Tracing-E76F51?style=flat-square" alt="Path Tracing" />
        <img src="https://img.shields.io/badge/BVH-4CC9F0?style=flat-square" alt="BVH" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/n-body">N-Body Simulation</a></h4>
      <p>Million-particle GPU simulation — Direct N², Barnes-Hut, Spatial Hash with CUDA-OpenGL interop</p>
      <p>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" alt="OpenGL" />
        <img src="https://img.shields.io/badge/Barnes--Hut-111827?style=flat-square" alt="Barnes-Hut" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/particle-fluid-sim">Particle Fluid Sim</a></h4>
      <p>10K-particle real-time fluid simulation using WebGPU compute shaders with trail effects</p>
      <p>
        <img src="https://img.shields.io/badge/WebGPU-005A9C?style=flat-square&logo=webgpu&logoColor=white" alt="WebGPU" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/WGSL-4CC9F0?style=flat-square" alt="WGSL" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/mini-opencv">Mini-OpenCV</a></h4>
      <p>CUDA image processing library — convolution, morphology, geometric transforms, pipeline processing</p>
      <p>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++17" />
        <img src="https://img.shields.io/badge/Image_Processing-E76F51?style=flat-square" alt="Image Processing" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/mini-image-pipe">Mini-ImagePipe</a></h4>
      <p>DAG-based heterogeneous image pipeline — multi-stream scheduling, pinned memory pool</p>
      <p>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++17" />
        <img src="https://img.shields.io/badge/DAG-4CC9F0?style=flat-square" alt="DAG" />
      </p>
    </td>
    <td></td>
  </tr>
</table>

#### 🌐 Applications / 应用项目

<table>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/MetaHuman">MetaHuman</a></h4>
      <p>3D digital human platform — Three.js rendering, voice interaction, behavior control, emotion FSM</p>
      <p>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
        <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/WebRTC">WebRTC</a></h4>
      <p>Minimal WebRTC demo — Go WebSocket signaling, room management, peer-to-peer media</p>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
        <img src="https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white" alt="WebRTC" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/sync-notes">Note Sync Now</a></h4>
      <p>E2E encrypted note sync — AES-256, 12-word mnemonic, real-time collaboration via WebSocket</p>
      <p>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
        <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
        <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/mind-gym">Mind Gym</a></h4>
      <p>Browser-based memory training — N-back, spaced reinforcement, adaptive difficulty, PWA</p>
      <p>
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
        <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind" />
        <img src="https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white" alt="PWA" />
      </p>
    </td>
  </tr>
</table>

---

<a id="experience"></a>
### 🎓 Education & Experience / 教育与经历

<table>
  <tr>
    <td width="50%">
      <h4>🎓 Education</h4>
      <p>
        <img src="https://logo.clearbit.com/xidian.edu.cn" height="18" alt="Xidian University"/>
        <b>Xidian University</b>
      </p>
      <p>Background in communications engineering. / 通信与信息工程相关背景</p>
    </td>
    <td width="50%">
      <h4>💼 Experience</h4>
      <p>
        <img src="https://logo.clearbit.com/mindray.com" height="18" alt="Mindray"/> Mindray ·
        <img src="https://logo.clearbit.com/zego.im" height="18" alt="ZEGO"/> ZEGO ·
        <img src="https://logo.clearbit.com/genomics.cn" height="18" alt="BGI"/> BGI
      </p>
      <p>Medical imaging, RTC & Genomic data. / 医疗、音视频与基因数据工程</p>
    </td>
  </tr>
</table>

---

<a id="tech-stack"></a>
### 🛠️ Tech Stack / 技术栈

| **Category** | **Technologies** |
| :--- | :--- |
| **Languages** | <img src="https://skillicons.dev/icons?i=cpp,cuda,python,rust,go,bash" alt="Languages"/> |
| **AI &amp; HPC** | <img src="https://skillicons.dev/icons?i=pytorch,tensorflow" alt="AI"/> &nbsp; CUDA · Triton · cuBLAS · Tensor Core · WebGPU |
| **System &amp; DevOps** | <img src="https://skillicons.dev/icons?i=linux,docker,git,github,cmake,nginx" alt="System"/> |
| **Web &amp; Frontend** | <img src="https://skillicons.dev/icons?i=react,ts,vite,tailwind,threejs" alt="Web"/> |

---

<a id="stats"></a>
### 📊 GitHub Stats / 数据概览

<details>
  <summary>Show stats / 展开数据</summary>

  <div align="center">
    <p>
      <img height="180" src="https://github-readme-stats.vercel.app/api?username=LessUp&show_icons=true&theme=default&locale=en&hide_border=true&title_color=0077b6&text_color=555555&icon_color=0077b6&bg_color=ffffff" alt="LessUp's GitHub stats" />
      <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LessUp&layout=compact&theme=default&locale=en&hide_border=true&title_color=0077b6&text_color=555555&bg_color=ffffff" alt="Top Languages" />
    </p>
  </div>

  <div align="center">
    <p>
      <img src="https://streak-stats.demolab.com?user=LessUp&theme=default&locale=en&date_format=M%20j%5B%2C%20Y%5D&fire=e76f51&ring=e76f51&currStreakLabel=0077b6&sideNums=0077b6&sideLabels=555555&dates=555555&background=ffffff" alt="GitHub Streak" />
    </p>
    <p>
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=LessUp&hide_border=true&bg_color=ffffff&color=555555&line=00b4d8&point=0077b6&area=true&area_color=90e0ef" alt="GitHub Activity Graph"/>
    </p>
  </div>
</details>

---

<a id="contact"></a>
### 📫 Connect with me / 联系方式

Feel free to reach out for collaboration, technical discussions, or open-source ideas.

欢迎通过邮箱与我交流技术想法、合作机会或开源项目。

<div align="left">
  <a href="mailto:jiashuai.shi@qq.com">
    <img src="https://img.shields.io/badge/Email-jiashuai.shi%40qq.com-FF5722?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  &nbsp;
  <a href="https://github.com/LessUp">
    <img src="https://img.shields.io/badge/GitHub-LessUp-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0077b6,00b4d8,90e0ef&height=120&section=footer" width="100%" alt="Footer" />
</div>
