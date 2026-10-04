<div align="center">

```text
        ✨        🧠  ∑  ∇  ⚡        ✨
   🧢
  👦💻  ───▶  ⌨️  ───▶  🖥️  ───▶  🤖
  "just one more kernel..."   ☕
```

# Hi, I'm Nikilesh 👋

**Senior Software Engineer** · custom operators · kernel optimization · LLM/VLM bring-up on hardware accelerators

[![Email](https://img.shields.io/badge/Email-nikileshofficial99%40gmail.com-0891b2?style=flat-square&logo=gmail&logoColor=white)](mailto:nikileshofficial99@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/niklesh-kumar-994259123/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-087f8c?style=flat-square&logo=googlechrome&logoColor=white)](https://nikileshk.netlify.app/)

</div>

---

## 🧭 About

I build hardware-aware ML systems, from cycle-level kernel tuning to deploying full models with high efficiency for inference on custom accelerators. 4+ years across DSPs, runtimes and inference servers.

## 🔧 What I work on

| | |
|---|---|
| 🛰️ **Radar-SDK porting** | FFT, CA-CFAR, OS-CFAR and DML target detection on a custom DSP platform, integrated with the SDK framework |
| ⚙️ **SIMD / VECC kernels** | Optimized kernels for SensPro DSP workloads, targeting cycle-level performance and hardware utilization |
| 🚚 **DMA & memory optimization** | Single/double-buffered transfers; theoretical vs. achieved cycle analysis |
| 🧩 **Custom device operators** | Native convolution, deformable convolution and arithmetic kernels in C++/Python |
| 🔁 **ONNX custom operators** | Custom ops in ONNX Runtime (x86) plus a symbolic-mapping bridge between PyTorch and ONNX |
| 🧠 **LLM / VLM bring-up** | Text and multimodal models integrated into vLLM/Inference Servers |

## 🧰 Tech

![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=flat-square)
![SGLang](https://img.shields.io/badge/SGLang-6D28D9?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

Also: SIMD/VECC, DSP acceleration, MLA attention, Decoupled-RoPE, MTP, model conversion, profiling and debugging, AI agentic workflows.

## 📝 Engineering notes

- **Fusion vs. scheduling overhead:** distributed inference is often limited by kernel launch granularity and memory copies, not raw compute.
- **DMA double-buffering:** it hides transfer latency only when pipeline depth matches the accelerator's command queue depth. Profile, don't guess.
- **PyTorch ↔ ONNX:** numerical precision silently degrades at symbolic-mapping boundaries. Validate at every one.
- **On-device LLMs:** memory-constrained first, compute-bound second. Design for quantization from day one.

## 🤝 Let's talk

Always interested in challenging ML systems work and hardware-accelerated inference. See my [portfolio](https://nikileshk.netlify.app/), or reach me by [email](mailto:nikileshofficial99@gmail.com) or on [LinkedIn](https://www.linkedin.com/in/niklesh-kumar-994259123/).
