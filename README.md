<h1 align="center">Vivek Gangwani</h1>

<p align="center">
  <b>ML Inference · Vision-Language Models · Spatio-Temporal ML</b><br/>
  MS Data Science @ <b>UC San Diego</b> (Sept 2026 – June 2028) · BTech Computer Engineering @ SPIT (CGPA 9.20/10)
</p>

<p align="center">
  <a href="https://vivvek09.github.io/"><img src="https://img.shields.io/badge/Portfolio-vivvek09.github.io-0A0A0A?style=flat-square" /></a>
  <a href="https://vivvek09.github.io/pdfs/Resume_Vivek_Gangwani.pdf"><img src="https://img.shields.io/badge/Resume-PDF-B31B1B?style=flat-square" /></a>
  <a href="https://www.linkedin.com/in/vivek-gangwani-8a434b25b/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:vgangwani@ucsd.edu"><img src="https://img.shields.io/badge/Email-vgangwani%40ucsd.edu-D14836?style=flat-square" /></a>
</p>

I make vision-language models faster and more reliable. My work sits where inference systems meet model behaviour: deciding how much compute a question actually needs, profiling where the latency goes, and finding out why multimodal models fail when their inputs shift.

> **Open to Summer 2027 internships** in ML inference, vision-language models, applied ML and data science.

---

## Featured work

### [Foveate: Adaptive Inference for Vision-Language Models](https://github.com/Vivvek09/Foveate-Adaptive-Inference-for-Vision-Language-Models)
`PyTorch` `vLLM` `Qwen2.5-VL` `AWQ` `FastAPI`

An open-source framework that gives each video question only the frames, resolution and model size it needs.
- Profiled the vision encoder, prefill and decode with CUDA events; visual tokens dominate prefill cost.
- A learned routing policy **matches 7B accuracy at 37% lower latency** and **halves median latency** on vLLM.

### Robustness of Encoders and Fusion in Medical VQA · [ICML 2026 SD4H](https://openreview.net/pdf?id=g9PRvysBkU) · [AAAI 2026 SECURE-AI4H](https://vivvek09.github.io/pdfs/AAAI_Paper.pdf)
Diagnosed encoder vs. fusion failures across 5 encoders, 7 fusion architectures, 3 datasets and 30 perturbations.
- Fusion-layer drift predicts accuracy loss (ρ = 0.79); fusion choice alone causes up to **2×** error variation.
- Image-swap interventions reveal compensatory suppression: image reliance fell in **16 of 21** settings.

### Trip Generation from 80M Parking Records · IHPC, A*STAR Singapore · [Poster](https://vivvek09.github.io/pdfs/WCS_Poster_Trip_Generation_ML_Framework.pdf)
Spatio-temporal pipeline over 1,829 carparks. Fixed spatial leakage with group CV and lifted unseen R² from **0.26 to 0.64** with DTW + PCA clusters and LightGBM. Presented at World Cities Summit 2026; under review at *Transportation Research Part A*.

### [Memory-Augmented Transformers for Traffic Forecasting](https://vivvek09.github.io/pdfs/IIPEM_346.pdf) · IEEE IIPEM 2025
Extended Titans neural memory with graph propagation and causal attention. **36.9% lower MAE** than historical-average baselines on PeMS08, with near-linear sequence scaling.

### Rain-Driven Commuter Delay · IIT Bombay · [Preprint](https://ssrn.com/abstract=7451470)
Turned **50M GPS trajectories** into segment-level delay and recovery metrics; CatBoost reached R² = 0.98 on recovery time. Under review at *Transportation Research Part D*.

---

## Publications and patent

| | Venue |
|---|---|
| [Beyond Accuracy: Robustness Analysis of Encoders and Fusion in Medical VQA](https://openreview.net/pdf?id=g9PRvysBkU) | SD4H @ ICML 2026 |
| [Robust and Interpretable Multimodal Fusion in Med-VQA](https://vivvek09.github.io/pdfs/AAAI_Paper.pdf) | SECURE-AI4H @ AAAI 2026 |
| [Memory-Augmented Transformers for Scalable Urban Traffic Forecasting](https://vivvek09.github.io/pdfs/IIPEM_346.pdf) | IEEE IIPEM 2025 |
| AttendEase: face-recognition attendance with geofencing and forecasting | Indian Patent 202421095056 |

---

## Toolbox

| | |
|---|---|
| **Inference and serving** | vLLM, AWQ, INT8/4-bit quantization, TensorRT, ONNX Runtime, multi-GPU serving |
| **Profiling** | CUDA events, per-stage latency, MFU, TTFT, p50/p95/p99, latency–accuracy frontiers |
| **ML and deep learning** | PyTorch, Hugging Face Transformers, LoRA, scikit-learn, LightGBM, XGBoost, CatBoost, SHAP |
| **Languages and tools** | Python, C++, SQL, Java, TypeScript, FastAPI, Docker, AWS, Spark, MLflow, Linux, Git |
