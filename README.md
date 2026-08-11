<h1 align="center">Yunus Berkay İnci</h1>

<h3 align="center">Software Engineer · Applied AI, LLM Systems & Full-Stack Development</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=500&lines=On-Premise+LLM+%26+RAG+Architecture;Computer+Vision+%26+Hyperspectral+Imaging;Full-Stack+Engineering+at+Production+Scale;Research+%E2%86%92+Production" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/yunusberkayinci" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="[https://yunusberkayinci.vercel.app/](https://yberkayinci.github.io/personal-portfolio/)" target="_blank"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:berkayinci25@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### About

B.Sc. Software Engineering, Honor Student — Ankara Yıldırım Beyazıt University (2026). I build AI systems that survive contact with production, not just notebooks.

- 🏢 **AI & Full-Stack Engineer (LLM/RAG)** at *4Dimension Information Technology* — building a fully on-premise RAG platform for Turkish public-sector internal audit, with zero paid-API dependency and no institutional data leaving the environment.
- 🔬 **TÜBİTAK 2209-A** research grant recipient · **2 international conference papers** on hyperspectral anomaly detection (Madrid & Istanbul, 2026 — both oral presentations).
- 🤝 **Founder & General Secretary**, AYBU Software Engineering Club — the university's first dedicated software engineering community.
- 🎯 Focus areas: retrieval architecture, offline/edge LLM inference, computer vision, remote sensing.

---

### Featured Work

#### 🛡️ On-Premise RAG Platform for Public-Sector Audit
`Production` · `Client work — source private`

Fully air-gapped retrieval system over legislation and historical audit findings, built to satisfy KVKK and institutional data-privacy constraints.

- Hybrid retrieval — multilingual-e5 + BM25 + Reciprocal Rank Fusion + cross-encoder reranking → **97.5% Hit@5**
- Local Ollama/Qwen 2.5 inference with claim-level citation validation; offline scikit-learn fallback at **93% CV accuracy**
- Human-in-the-loop active learning with approval gating and dry-run diffing
- FastAPI ↔ Laravel 12 + Vue 3 via RBAC-gated proxy with SSE streaming — **40+ endpoints across 11 production UI pages**

<sub>`Python` · `FastAPI` · `Ollama` · `ChromaDB` · `Laravel 12` · `Vue 3` · `Docker`</sub>

#### 🛰️ AI-Driven Hyperspectral Anomaly Detection
`TÜBİTAK 2209-A Funded` · `2 published papers`

Senior capstone and undergraduate research on hybrid deep-learning methods for urban hyperspectral imagery.

- Fused GAN representations with LAD-PCA across **103+ spectral bands** → **~0.99 AUC**, outperforming classical RX and Local-RX detectors
- Extended the approach with a GAN-driven Fractional Fourier Transform representation
- Benchmarked **8+ anomaly-detection methods**; designed scalable dimensionality-reduction and denoising workflows

<sub>`Python` · `MATLAB` · `GANs` · `Autoencoders` · `FrFT` · `PCA`</sub>

#### 👥 Crowd Density Estimation & Multimodal XAI Agent
`Research`

Hybrid CNN crowd counter paired with a dual-model explainability agent for ultra-dense scenes.

- **MAE 61.14** on ShanghaiTech Part A, beating the CSRNet baseline (68.2) via architectural optimization and CBAM attention
- Hybrid MSE/SSIM/Optimal Transport loss for structurally accurate predictions in scenes with **500+ people**
- Dual-model multimodal explanation layer (Qwen-VL + Qwen-Chat)

<sub>`PyTorch` · `Hybrid CNNs` · `Qwen-VL` · `CUDA`</sub>

#### 📡 Self-Healing AIoT Network Monitor & Edge LLM Agent
`Personal research`

Fully offline edge agent that diagnoses network faults and recovers from them without any cloud dependency.

- Bidirectional MQTT pipeline for telemetry analysis, root-cause diagnosis and automated recovery
- ESP32 telemetry → Python controller → quantized local LLM, with a live health dashboard

<sub>`Python` · `MQTT` · `Ollama/Phi-4` · `ESP32` · `Streamlit`</sub>

#### 🚲 NYC Citi Bike Demand Forecasting & Weather Impact Analysis
`Data science`

ETL/ML pipeline over millions of trip and weather records for hourly demand forecasting.

- Random Forest model reaching **R² 0.98**; simulated fleet-capacity scenarios
- Identified 8 AM / 6 PM peak commuting windows and weather–ridership relationships

<sub>`Python` · `Pandas` · `Scikit-learn` · `AWS S3` · `Open-Meteo`</sub>

---

### Publications

- **GAN-Driven Fractional Fourier Transform for Hyperspectral Anomaly Detection** — *10th ISPEC International Congress on Modern Scientific Research*, Madrid, Apr 2026. Oral presentation.
- **Evaluating the Impact of Generative Adversarial Networks on Classical Anomaly Detectors in Urban Hyperspectral Imagery** — *International Üsküdar Scientific Research Congress*, Istanbul, Feb 2026. Oral presentation.

---

### Open Source

| Repository | What it is | Stack |
| --- | --- | --- |
| [personal-portfolio](https://github.com/yberkayinci/personal-portfolio) | Bilingual (TR/EN) portfolio site — [live ↗](https://yunusberkayinci.vercel.app/) | JavaScript |
| [Petlebi.com-DataScraper](https://github.com/yberkayinci/Petlebi.com-DataScraper) | ETL scraper for product data → JSON → MySQL | Python |
| [Breast-Cancer-Prediction-Comparative-Study](https://github.com/yberkayinci/Breast-Cancer-Prediction-Comparative-Study) | CART vs. Naive Bayes comparison with ROC analysis | Python, scikit-learn |
| [RegexEngine](https://github.com/yberkayinci/RegexEngine) | Regular expression parser built from scratch | C++ |
| [countermeasure-simulator](https://github.com/yberkayinci/countermeasure-simulator) | High-performance Windows desktop simulation | C# |

---

### Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,fastapi,docker&theme=dark" alt="AI stack" />
  <br />
  <img src="https://skillicons.dev/icons?i=laravel,vue,dotnet,angular,nodejs,postgres,redis,aws&theme=dark" alt="Web stack" />
</p>

**Core** — Python · SQL · C# · JavaScript

**Generative AI & Retrieval** — LLMs, RAG, LangChain, Ollama, multilingual-e5, BM25, cross-encoder reranking, ChromaDB / Qdrant / pgvector, active learning

**Computer Vision & ML** — PyTorch, TensorFlow/Keras, OpenCV, YOLO, CNNs, GANs, scikit-learn, LSTM, hyperspectral imaging

**Backend & Web** — FastAPI, Laravel 12, Vue 3 + Inertia, .NET Core, Angular, REST, SSE, RBAC

**Platform & IoT** — Docker, Redis, AWS S3/EC2, GitHub Actions, Linux, MQTT, ESP32, secure SDLC (OWASP Top 10, JWT/OAuth2)

---

### GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=yberkayinci&show_icons=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&icon_color=58A6FF&cache_seconds=86400" alt="GitHub Stats" />
  <img height="165" src="https://streak-stats.demolab.com?user=yberkayinci&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF&stroke=30363D&sideLabels=C9D1D9&dates=8B949E" alt="GitHub Streak" />
</p>

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yberkayinci&layout=compact&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&langs_count=8&cache_seconds=86400" alt="Top Languages" />
</p>

---

<p align="center">
  <b>Open to Applied AI / ML Engineering and Backend roles.</b><br />
  <a href="mailto:berkayinci25@gmail.com">berkayinci25@gmail.com</a> · Ankara, Türkiye
</p>
