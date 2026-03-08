<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0077b6,00b4d8,90e0ef&height=220&section=header&text=Hi,%20I'm%20LessUp&fontSize=70&animation=fadeIn&fontAlignY=30&desc=AI%20Infrastructure%20%26%20HPC%20Developer&descAlignY=58&descAlign=60&fontColor=ffffff" width="100%" alt="Header" />

  <br/>

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=0077B6&center=true&vCenter=true&multiline=true&repeat=true&width=680&height=80&lines=Building+AI+Infrastructure+%26+HPC+Systems;CUDA+Kernel+Optimization+%7C+LLM+Inference+%7C+GPU+Computing" alt="Typing SVG" />
  </a>

  <br/>

  <p>
    专注于 AI 基础设施与高性能计算的工程实践
  </p>

  <p>
    🔬 <b>Focus</b>: CUDA Kernel Optimization · LLM Inference · GPU Computing<br/>
    🌱 <b>Exploring</b>: AI inference acceleration &amp; large-scale pipeline orchestration<br/>
    🤝 <b>Open to</b>: Research collaboration &amp; open-source co-building
  </p>

  <br/>

  <a href="https://github.com/LessUp?tab=followers">
    <img src="https://img.shields.io/github/followers/LessUp?label=Followers&style=for-the-badge&color=0077b6&logo=github&logoColor=white" alt="Followers" />
  </a>
  &nbsp;
  <a href="https://github.com/LessUp?tab=repositories">
    <img src="https://img.shields.io/github/stars/LessUp?affiliations=OWNER&style=for-the-badge&color=e76f51&logo=github&logoColor=white" alt="Stars" />
  </a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=LessUp&label=Profile+Views&color=00b4d8&style=for-the-badge" alt="Views" />

  <br/><br/>

  <p>
    <a href="#about"><img src="https://img.shields.io/badge/-About-0077b6?style=flat-square" alt="About"/></a>&nbsp;
    <a href="#projects"><img src="https://img.shields.io/badge/-Projects-00b4d8?style=flat-square" alt="Projects"/></a>&nbsp;
    <a href="#experience"><img src="https://img.shields.io/badge/-Experience-90e0ef?style=flat-square&logoColor=000" alt="Experience"/></a>&nbsp;
    <a href="#tech-stack"><img src="https://img.shields.io/badge/-Tech_Stack-0077b6?style=flat-square" alt="Tech Stack"/></a>&nbsp;
    <a href="#stats"><img src="https://img.shields.io/badge/-Stats-00b4d8?style=flat-square" alt="Stats"/></a>&nbsp;
    <a href="#contact"><img src="https://img.shields.io/badge/-Contact-e76f51?style=flat-square" alt="Contact"/></a>
  </p>
</div>

<br/>

---

<a id="about"></a>

<h3>👨‍💻 About Me / 关于我</h3>

<img align="right" width="300" src="https://github-readme-stats-six-iota-99.vercel.app/api/top-langs/?username=LessUp&layout=donut-vertical&theme=default&locale=en&hide_border=true&title_color=0077b6&text_color=555555&bg_color=00000000&cache_seconds=86400" alt="Top Languages" />

> I build AI infrastructure and high-performance systems with C++/CUDA, Python, and Go.  
> 主要关注 AI 基础设施、GPU 算子优化与高性能计算等方向的工程实践。

- 🔥 **GPU Kernel Engineering** — CUDA/Triton kernel optimization, FlashAttention, GEMM, quantization
- 🧠 **AI Inference Systems** — LLM inference engines, model quantization (W8A16/FP8), KV Cache
- ⚡ **High-Performance Computing** — N-body simulation, ray tracing, image processing pipelines
- 🌐 **Real-time Systems** — WebRTC signaling, real-time detection, digital human platform

<br clear="both"/>

---

<a id="projects"></a>

<h3>🚀 Projects / 项目全景</h3>

<h4>⚡ GPU Kernel Optimization / GPU 算子优化</h4>

<table>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/modern-ai-kernels">🔷 TensorCraft-HPC</a></h4>
      <p>Modern C++17/CUDA AI kernel library — Elementwise, GEMM, FlashAttention, Conv2D, SpMV, FP8 quantization</p>
      <p>
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++17" />
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/Tensor_Core-111827?style=flat-square&logo=nvidia&logoColor=white" alt="Tensor Core" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/sgemm-optimization">🔷 SGEMM Optimization</a></h4>
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
      <h4><a href="https://github.com/LessUp/triton-fused-ops">🔷 Triton Fused Ops</a></h4>
      <p>RMSNorm+RoPE fusion, Gated MLP fusion, FP8 GEMM with auto-tuning for Transformers</p>
      <p>
        <img src="https://img.shields.io/badge/Triton-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="Triton" />
        <img src="https://img.shields.io/badge/FP8-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="FP8" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/llm-speed">🔷 LLM-Speed</a></h4>
      <p>CUDA LLM kernel library — FlashAttention (online softmax), FP16/INT8 GEMM with Tensor Core</p>
      <p>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
        <img src="https://img.shields.io/badge/FlashAttn-111827?style=flat-square" alt="FlashAttention" />
      </p>
    </td>
  </tr>
</table>

<h4>🧠 AI Inference Engines / AI 推理引擎</h4>

<table>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/tiny-llm">🟢 Tiny-LLM</a></h4>
      <p>Lightweight LLM inference engine — W8A16 quantization, KV Cache, multi-sampling strategies</p>
      <p>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++17" />
        <img src="https://img.shields.io/badge/INT8-4CC9F0?style=flat-square" alt="INT8" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/mini-inference-engine">🟢 Mini Inference Engine</a></h4>
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
      <h4><a href="https://github.com/LessUp/tiny-dl-inference">🟢 Tiny-DL-Inference</a></h4>
      <p>WebGPU micro inference engine — Conv2d, kernel fusion, Im2Col, MNIST classification</p>
      <p>
        <img src="https://img.shields.io/badge/WebGPU-005A9C?style=flat-square&logo=webgpu&logoColor=white" alt="WebGPU" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/WGSL-4CC9F0?style=flat-square" alt="WGSL" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/YOLO-Toys">🟢 YOLO-Toys</a></h4>
      <p>Multi-model real-time vision — YOLO/DETR/OWL-ViT/BLIP with WebSocket streaming</p>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/YOLOv8-5E60CE?style=flat-square&logo=opencv&logoColor=white" alt="YOLOv8" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      </p>
    </td>
  </tr>
</table>

<h4>🎮 GPU Computing & Simulation / GPU 计算与仿真</h4>

<table>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/ray-tracer">🟠 CUDA Ray Tracer</a></h4>
      <p>Pure CUDA ray tracer — Phong shading, path tracing, BVH acceleration, warp divergence optimization</p>
      <p>
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
        <img src="https://img.shields.io/badge/Path_Tracing-E76F51?style=flat-square" alt="Path Tracing" />
        <img src="https://img.shields.io/badge/BVH-4CC9F0?style=flat-square" alt="BVH" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/n-body">🟠 N-Body Simulation</a></h4>
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
      <h4><a href="https://github.com/LessUp/particle-fluid-sim">🟠 Particle Fluid Sim</a></h4>
      <p>10K-particle real-time fluid simulation using WebGPU compute shaders with trail effects</p>
      <p>
        <img src="https://img.shields.io/badge/WebGPU-005A9C?style=flat-square&logo=webgpu&logoColor=white" alt="WebGPU" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/WGSL-4CC9F0?style=flat-square" alt="WGSL" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/mini-opencv">🟠 Mini-OpenCV</a></h4>
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
      <h4><a href="https://github.com/LessUp/mini-image-pipe">🟠 Mini-ImagePipe</a></h4>
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

<h4>🌐 Applications / 应用项目</h4>

<table>
  <tr>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/MetaHuman">🟣 MetaHuman</a></h4>
      <p>3D digital human platform — Three.js rendering, voice interaction, behavior control, emotion FSM</p>
      <p>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
        <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/WebRTC">🟣 WebRTC</a></h4>
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
      <h4><a href="https://github.com/LessUp/sync-notes">🟣 Note Sync Now</a></h4>
      <p>E2E encrypted note sync — AES-256, 12-word mnemonic, real-time collaboration via WebSocket</p>
      <p>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
        <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
        <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" />
      </p>
    </td>
    <td width="50%">
      <h4><a href="https://github.com/LessUp/mind-gym">🟣 Mind Gym</a></h4>
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

<h3>🎓 Education & Experience / 教育与经历</h3>

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
        <img src="https://logo.clearbit.com/mindray.com" height="18" alt="Mindray"/> <b>Mindray</b> ·
        <img src="https://logo.clearbit.com/zego.im" height="18" alt="ZEGO"/> <b>ZEGO</b> ·
        <img src="https://logo.clearbit.com/genomics.cn" height="18" alt="BGI"/> <b>BGI</b>
      </p>
      <p>Medical imaging, RTC & Genomic data. / 医疗、音视频与基因数据工程</p>
    </td>
  </tr>
</table>

---

<a id="tech-stack"></a>

<h3>🛠️ Tech Stack / 技术栈</h3>

<div align="center">

| **Category** | **Technologies** |
| :--- | :--- |
| **Languages** | <img src="https://skillicons.dev/icons?i=cpp,cuda,python,rust,go,bash" alt="Languages"/> |
| **AI &amp; HPC** | <img src="https://skillicons.dev/icons?i=pytorch,tensorflow" alt="AI"/> &nbsp; CUDA · Triton · cuBLAS · Tensor Core · WebGPU |
| **System &amp; DevOps** | <img src="https://skillicons.dev/icons?i=linux,docker,git,github,cmake,nginx" alt="System"/> |
| **Web &amp; Frontend** | <img src="https://skillicons.dev/icons?i=react,ts,vite,tailwind,threejs" alt="Web"/> |

</div>

---

<a id="stats"></a>

<h3>📊 GitHub Stats / 数据概览</h3>

<div align="center">

  <img height="180" src="https://github-readme-stats-six-iota-99.vercel.app/api?username=LessUp&show_icons=true&theme=default&locale=en&hide_border=true&title_color=0077b6&text_color=555555&icon_color=0077b6&bg_color=00000000&rank_icon=github&cache_seconds=86400" alt="LessUp's GitHub stats" />
  &nbsp;
  <img src="https://streak-stats.demolab.com?user=LessUp&theme=default&locale=en&date_format=M%20j%5B%2C%20Y%5D&fire=e76f51&ring=e76f51&currStreakLabel=0077b6&sideNums=0077b6&sideLabels=555555&dates=555555&background=00000000&hide_border=true" alt="GitHub Streak" />

</div>

<br/>

<div align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy-silk-ten.vercel.app/?username=LessUp&theme=flat&no-bg=true&no-frame=true&column=7&margin-w=10" alt="GitHub Trophy" />
  </a>
</div>

<br/>

<details>
  <summary>📈 More Stats / 更多数据</summary>
  <br/>
  <div align="center">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=LessUp&hide_border=true&bg_color=00000000&color=555555&line=00b4d8&point=0077b6&area=true&area_color=90e0ef&cache_seconds=86400" alt="GitHub Activity Graph"/>
  </div>
</details>

---

<div align="center">
  <img src="https://raw.githubusercontent.com/LessUp/LessUp/output/github-snake-dark.svg" alt="Snake animation" />
</div>

---

<a id="contact"></a>

<h3>📫 Connect with me / 联系方式</h3>

<p>
Feel free to reach out for collaboration, technical discussions, or open-source ideas.<br/>
欢迎通过邮箱与我交流技术想法、合作机会或开源项目。
</p>

<div align="left">
  <a href="mailto:jiashuai.shi@qq.com">
    <img src="https://img.shields.io/badge/Email-jiashuai.shi%40qq.com-FF5722?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  &nbsp;
  <a href="https://github.com/LessUp">
    <img src="https://img.shields.io/badge/GitHub-LessUp-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0077b6,00b4d8,90e0ef&height=120&section=footer" width="100%" alt="Footer" />
</div>
