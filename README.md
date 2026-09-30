<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:1D4ED8,100:7aa2f7&height=200&section=header&text=Gabriel%20James&fontSize=48&fontColor=c0caf5&animation=twinkling&fontAlignY=38&desc=AI%20Systems%20Engineer%20%E2%80%94%20Financial%20AI%20%C2%B7%20Real-Time%20Systems%20%C2%B7%20AI%20Infrastructure&descAlignY=58&descSize=16" />

<div align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=7AA2F7&center=true&vCenter=true&width=620&lines=AI+Systems+Engineer+%2F+AI-ML+Engineer;Financial+AI+%2B+Real-Time+Systems+%2B+AI+Infra;PyTorch+%C2%B7+C%2B%2B17+%C2%B7+FastAPI+%C2%B7+Streaming;Building+systems%2C+not+just+models" alt="Typing SVG" /></a>
</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-gabrieljames.me-1a1b27?style=for-the-badge&logo=googlechrome&logoColor=7aa2f7)](https://gabrieljames.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabrieljamesamara)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gabriel22dec@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-gabsgj-1a1b27?style=for-the-badge&logo=github&logoColor=c0caf5)](https://github.com/gabsgj)

**AI/ML Engineer and AI Systems Engineer building intelligent systems across financial intelligence, real-time data infrastructure, computer vision, and verified software.**

`B.Tech CSE @ GEC Thrissur '28` · `Open to AI/ML internships`

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=2&section=header" width="100%" />

<table>
<tr>
<td>

```yaml
name: Gabriel James
role: AI Systems Engineer / AI-ML Engineer
focus:
  - Financial AI + time-series systems
  - Real-time + streaming infrastructure
  - AI infra + agent memory + MLOps
  - Verified software + HPC systems
now:
  building: production ML systems with live demos
  exploring: signal processing x deep learning
  open_to: AI/ML internships, research collabs
```

</td>
<td width="320">

**`> where I spend my time`**
```
Financial AI systems........... ████████░░░░░░░░░░░░ 40%
Real-time + streaming.......... █████░░░░░░░░░░░░░░░ 25%
AI infra + agents.............. ████░░░░░░░░░░░░░░░░ 20%
HPC + systems + C++............ ███░░░░░░░░░░░░░░░░░ 15%
```
<br/>

📍 **India** · 🌐 **[gabrieljames.me](https://gabrieljames.me)**<br/>
🏆 **Top 6 @ HackOdisha 5.0** · **Top 15 @ HackHazards '25**<br/>
📝 **NPTEL Top 2% — High-Performance Scientific Computing**

</td>
</tr>
</table>

---

## <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="24" /> 𝙵𝚎𝚊𝚝𝚞𝚛𝚎𝚍 𝚂𝚢𝚜𝚝𝚎𝚖𝚜 — *𝚎𝚟𝚒𝚍𝚎𝚗𝚌𝚎 𝚘𝚟𝚎𝚛 𝚌𝚕𝚊𝚒𝚖𝚜*

> Each is a complete, runnable system with architecture, docs, and a live demo where available. Problem → Architecture → Result.

<table>
<tr>
<td width="50%" valign="top">

### 1. [ChronoSpectra](https://github.com/gabsgj/ChronoSpectra) — Financial Forecasting Engine
**Multimodal time-series forecasting with time-frequency deep learning**

```yaml
stack: [PyTorch, FastAPI, React 19, SciPy]
signal: [STFT, CWT, HHT/EMD, CNNs]
infra: [SSE streaming, drift detection, Docker, Redis]
```

- **Problem:** Non-stationary markets — volatility clustering + low SNR break ARIMA / plain RNNs.
- **Architecture:** Ingestion → STFT/CWT/HHT scalograms → custom 2D CNNs → FastAPI + SSE → React 19 / D3 telemetry. Single `stocks.json` drives frontend + backend. 3 modes: per-stock, transfer, embedding-aware.
- **Result:** Production pipeline with drift-triggered retraining, versioned rollback, auto-generated Colab GPU notebooks.

🔴 **[Live Demo](https://chronospectra.gabrieljames.me/)** · 📂 **[Code](https://github.com/gabsgj/ChronoSpectra)**

</td>
<td width="50%" valign="top">

### 2. [Safe-Semantic-Planner](https://github.com/gabsgj/Safe-Semantic-Planner) — C++ Planning Engine
**Real-time safe motion + semantic planning in ℝᵈ — zero cloud deps**

```yaml
stack: [C++17, D* Lite, k-d Tree, LTL, cpp-httplib]
safety: [potential barriers, zero-violation invariant]
ui: [embedded visualizer, 4 views, Canvas]
```

- **Problem:** Agents need sub-ms replanning with hard safety + temporal rules, offline.
- **Architecture:** Lifelong Planning D* Lite + orthogonal k-d tree hazard index + exponential potential fields + native 64-D NLP/LTL parser + multithreaded single-binary HTTP visualizer.
- **Result:** Repo-benchmarked up to **219× faster** than static A\* (0.33–8.4μs), NLP parse in ~9.2μs, 100% local.

🔴 **[Live Demo](https://ssp.gabrieljames.me)** · 📂 **[Code](https://github.com/gabsgj/Safe-Semantic-Planner)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 3. [Synapse-Memory](https://github.com/gabsgj/Synapse-Memory) — Agent Infrastructure
**Zero-dependency, local-first memory + knowledge graph for AI agents**

```yaml
stack: [Python 3.12, FastMCP, FastAPI, binary log]
retrieval: [vector + BM25 + graph + recency]
```

- **Problem:** Coding agents reset context every session — decisions and constraints lost.
- **Architecture:** Append-only flat-file storage (no Postgres/Redis) + background compaction + multi-signal ranking `w₁·semantic + w₂·BM25 + w₃·graph + w₄·recency + w₅·importance` + token-budget compression. Tools: `memory_store / recall / graph_traverse / optimize`.
- **Result:** 35/35 tests passing, full docs (architecture, storage, ranking, API/MCP spec), MCP-ready for Claude/Cursor/Copilot.

📂 **[Code](https://github.com/gabsgj/Synapse-Memory)** · 📖 **[Docs](https://github.com/gabsgj/Synapse-Memory/tree/main/docs)**

</td>
<td width="50%" valign="top">

### 4. [Kaagaz](https://github.com/gabsgj/Kaagaz) — Live Research Agent
**Indian banking-document agent that researches live and cites everything**

```yaml
stack: [Python, Flask, live web search, audit trail]
built: [IBM Bob 2.0, lablab.ai Sep 2026]
```

- **Problem:** Banking requirements scattered across bank sites, RBI circulars, stamp-duty schedules — people discover missing docs at the counter.
- **Architecture:** Free-text transaction → cache check → live search → source reading → ordered, costed, regulator-aware checklist (RBI vs State govt separated) with every URL filed.
- **Result:** Handles unseen transactions (home loan, KCC renewal, gold loan), not just curated FAQs. Pre-warmed cache as floor, not ceiling.

🔴 **[Live Demo](https://kaagaz.gabrieljames.me/)** · 📂 **[Code](https://github.com/gabsgj/Kaagaz)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 5. [Stampede-Predictor](https://github.com/gabsgj/Stampede-Predictor) — Real-Time Safety AI
**Crowd density + stampede-risk prediction on live video**

```yaml
stack: [YOLO, OpenCV, Fluvio, Flask, SSE]
perf: [~30ms/frame, multithreaded ingestion]
```

- **Problem:** CCTV is reactive — misses local pressure surges before crush events.
- **Architecture:** Non-blocking capture → spatial-grid density + flow scoring → Fluvio event pub/sub → SSE live dashboard with heatmaps + early-warning alarms.
- **Result:** 🏆 **Top 15 / 17,000+ teams — HackHazards '25 (Fluvio Track)**. ⭐⭐ most-starred safety system in profile.

📂 **[Code](https://github.com/gabsgj/Stampede-Predictor)**

</td>
<td width="50%" valign="top">

### 6. [SID — Structural Inspection Drone](https://github.com/gabsgj/SID-Software-Team-ideator) — Edge AI
**Autonomous crack detection + BIM integration — leading 8 engineers**

```yaml
stack: [YOLOv11s-seg, OpenCV, Jetson Orin NX]
metrology: [GSD + ArUco + stereo depth, IS 456:2000]
bim: [IfcOpenShell, PyVista, Pydantic v2]
```

- **Problem:** Manual bridge/dam inspection is slow, dangerous, qualitative.
- **Architecture:** Drone/ZED2 feed → YOLOv11s-seg → skeletonization + PCA → sub-pixel mm width → severity grading → `IfcSurfaceFeature` written directly into `.ifc`.
- **Result:** **mAP@50: 0.716** under edge memory/latency constraints. Software Lead @ IDEATOR, GEC Thrissur.

📂 **[Code](https://github.com/gabsgj/SID-Software-Team-ideator)**

</td>
</tr>
</table>

---

## <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="24" /> 𝚀𝚞𝚊𝚗𝚝, 𝚂𝚝𝚊𝚝𝚒𝚜𝚝𝚒𝚌𝚊𝚕 𝙻𝚎𝚊𝚛𝚗𝚒𝚗𝚐 & 𝙳𝚎𝚟𝚎𝚕𝚘𝚙𝚎𝚛 𝚃𝚘𝚘𝚕𝚜

<table>
<tr>
<td width="50%" valign="top">

**[Market-Volatility-Spike-Detector](https://github.com/gabsgj/Market-Volatility-Spike-Detector)** — systemic-risk anomaly detection
`Python · NumPy · SciPy · Mahalanobis`
Rolling 60-day 4-D Gaussian (log-return, σ₁₄, |return|, volume-change) + Mahalanobis scoring. Tested on COVID crash / SVB regimes.
🔴 [Demo](https://marketvolatilityanomaly.gabrieljames.me/) · [Code](https://github.com/gabsgj/Market-Volatility-Spike-Detector)

**[Baum-Welch-Algorithm](https://github.com/gabsgj/Baum-Welch-Algorithm)** — HMM EM from scratch
`Python · JS · D3.js · log-space`
Forward-backward + Baum-Welch re-estimation with underflow-safe log trellis, convergence dashboard.
🔴 [Demo](https://bwa.gabrieljames.me) · [Code](https://github.com/gabsgj/Baum-Welch-Algorithm)

**[SynonymNN](https://github.com/gabsgj/SynonymNN)** — embeddings from first principles
`NumPy · PyTorch · BPTT · Adam · MPS/CUDA`
150-line NumPy teaching script + full raw-NumPy BPTT + PyTorch modules. `T_syn≈I`, `T_ant≈−I`.

</td>
<td width="50%" valign="top">

**[State-Transition-Diagrams](https://github.com/gabsgj/State-Transition-Diagrams)** — PyPI library ⭐⭐
`pip install state-transition-diagrams`
Interactive D3 (particle flow, timeline replay, de-congestion) + Graphviz static export + Flask blueprint for HMM/FSM/Markov chains.

**[K-Means-Image-Compressor](https://github.com/gabsgj/K-Means-Image-Compressor)** — color quantization API
`Flask · scikit-learn · Docker`
K-Means++ on 100k-pixel sample, up to ~6× compression, split-screen artifact inspector + REST endpoint.
🔴 [Demo](http://imagecompressor.gabrieljames.me/)

**[Circuit-Analyzer](https://github.com/gabsgj/Circuit-Analyzer)** — schematic AI ⭐
`Flask · Gemini Vision · Schemdraw`
Image → topology + node voltages + E12/E24 snapping + text-to-schematic + BOM. Offline solver fallback.

</td>
</tr>
</table>

---

## <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="24" /> 𝚃𝚘𝚘𝚕𝚋𝚘𝚡 — *𝚕𝚊𝚢𝚎𝚛𝚜, 𝚗𝚘𝚝 𝚊 𝚋𝚊𝚍𝚐𝚎 𝚠𝚊𝚕𝚕*

<div align="center">
<img src="https://skillicons.dev/icons?i=py,cpp,c,java,ts,js,fastapi,flask,react,nextjs,tailwind,postgres,redis,docker,aws,linux,git&theme=dark&perline=9" />
</div>

**AI/ML:** `PyTorch` `TensorFlow` `scikit-learn` `OpenCV` `YOLOv5/v8/v11` `ONNX` `HMMs` `time-series` `anomaly detection`
**Serving & Infra:** `FastAPI` `Flask` `Docker` `Redis` `SSE` `Fluvio` `Kafka` `CI/CD` `Cloudflare` `Render` `Vercel`
**Data & Frontend:** `PostgreSQL` `Supabase` `SQL` `React 19` `Next.js` `TypeScript` `Tailwind` `D3.js` `Recharts`
**Systems:** `C++17` `C` `CUDA` `OpenMP` `MPI` `OpenACC` `Numba` `pthreads` `Bash` `LaTeX`

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Vector_Search-DC244C?style=flat-square&logo=qdrant&logoColor=white)

---

## 💼 𝙴𝚡𝚙𝚎𝚛𝚒𝚎𝚗𝚌𝚎 & 𝚂𝚒𝚐𝚗𝚊𝚕

**Software Engineering Intern — [Giolit Labs](https://giolit.com)** `Jan 2026 – Present`
High-assurance software company — formal verification, program synthesis & verified systems (IEC 62304 / ISO 26262 / DO-178C alignment), building a verified Hospital Management System + formally verified Enterprise Orchestrator.
Architected verification-ready enterprise modules (Accounting, HR, CRM) on Java / Spring Boot + PostgreSQL with OOD multi-tenant schemas. Built decoupled inter-module routing + REST API gateways for cross-service communication. Shipped 3 production React / Next.js + TypeScript apps on the platform, with Docker + GitHub Actions CI/CD and automated test suites.

**Software Lead — Structural Inspection Drone, IDEATOR GEC Thrissur** `Feb 2026 – Present`
Leading 8 engineers on Jetson Orin NX inspection stack. Competitive analysis, investor-grade proposals, institutional funding.

**AI Project Lead — Team Arete, GEC Thrissur** `Apr 2025 – Present`
Hackathon systems leadership — Top 6 HackOdisha 5.0, Top 15 HackHazards '25.

**Key achievements:** `mAP@50 0.716 edge CV` · `~30ms/frame streaming` · `219× replanning (repo-bench)` · `35/35 agent-memory tests` · `37 DSA programs in C` · `NPTEL Top 2% HPC`

---

## <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="24" /> 𝚂𝚢𝚜𝚝𝚎𝚖𝚜 𝙳𝚎𝚙𝚝𝚑, 𝙲𝚘𝚞𝚛𝚜𝚎𝚠𝚘𝚛𝚔 & 𝙽𝚘𝚝𝚎𝚜

**Below-Python proof — what runs when abstractions end:**

| Area | Repo | What it proves |
|---|---|---|
| **HPC** | [High-Performance-Computing-Architectures-Algorithms](https://github.com/gabsgj/High-Performance-Computing-Architectures-Algorithms) | Shared (OpenMP + SIMD), distributed (MPI `Isend/Irecv`, `Bcast/Scatter/Gather/Reduce`), GPU (CUDA tiling, OpenACC `parallel loop`), JIT (Numba) — speedup + scaling analysis, not just ports |
| **OS** | [Operating-Systems-Lab](https://github.com/gabsgj/Operating-Systems-Lab) | FCFS/SRTF/Priority/RR scheduling · pthreads + semaphores (readers-writers, dining philosophers) · Banker's safe sequences · FIFO/LRU/Optimal paging · pipes, message queues, shared memory · `/proc` inspection |
| **DSA** | [Data-Structures-Lab-2025-S3](https://github.com/gabsgj/Data-Structures-Lab-2025-S3) | 37 self-contained C programs — binary/circular search · Quick/Merge/Heap/Insertion sorts · LLs, deque, expression eval · BST/AVL/heaps/graphs + BFS/DFS |

> 🎓 **NPTEL Spotlight — High-Performance Scientific Computing (Top 2% nationally):** 12-week program covering parallel architectures end to end — OpenMP scheduling + SIMD vectorization, MPI point-to-point + collectives, CUDA memory hierarchy + shared-memory tiling, OpenACC offload, Numba JIT — each with speedup and scaling analysis in the [HPC repo](https://github.com/gabsgj/High-Performance-Computing-Architectures-Algorithms). This is the systems foundation behind the ML work above: knowing what the hardware actually does.

**Coursework (KTU, S3–S5):** `Systems:` OS · Databases · Distributed Computing · HPC · OOP · DSA — `Math/ML:` Statistics & Probability · Machine Learning · Pattern Recognition

**Deep dives live inside the repos:** [Synapse docs](https://github.com/gabsgj/Synapse-Memory/tree/main/docs) — binary-log storage, multi-signal ranking, MCP spec · [SSP](https://github.com/gabsgj/Safe-Semantic-Planner) — D\* Lite + k-d tree + LTL design notes · [Kaagaz](https://github.com/gabsgj/Kaagaz) — RBI-vs-State regulator separation · More systems writing at [gabrieljames.me](https://gabrieljames.me)

<details>
<summary><b>📚 Certifications — click to expand (credential → where applied)</b></summary>
<br/>

**Specialization:** Machine Learning Specialization — DeepLearning.AI · Stanford Online (Nov 2025) → applied in ChronoSpectra + Market-Volatility + K-Means

**NPTEL (Top 2% nationally):** High Performance Scientific Computing → applied in HPC repo (OpenMP/MPI/CUDA) · Project Management

**Selected courses (31 total):** Generative AI Engineering + Advanced Fine-Tuning (IBM) → Kaagaz/Synapse · RAG + LangChain (IBM) → Synapse · Flask + Python (IBM) → Kaagaz/Circuit · Financial Markets (Yale) + ML in Trading/Finance (NYIF/Google Cloud) + Guided Tour ML in Finance (NYU) → ChronoSpectra/Market-Volatility · AWS Technical Essentials + Serverless (AWS) → deployments · SQL for Data Science (UC Davis) + Java + DB with Java/SQL (Amazon) → Giolit modules · Version Control (Meta) · Prompt Engineering (Vanderbilt) + ChatGPT Data Analysis

Full list on [LinkedIn](https://www.linkedin.com/in/gabrieljamesamara) — GitHub stays proof-first by design.

</details>

---

## 📊 𝚂𝚝𝚊𝚝𝚜

<div align="center">
<table>
<tr>
<td>
<img src="https://github-stats-extended.vercel.app/api?username=gabsgj&show_icons=true&theme=tokyonight&hide_border=true&border_radius=12&bg_color=1a1b27&title_color=7aa2f7&icon_color=7dcfff&text_color=c0caf5&count_private=true&include_all_commits=true&cache_seconds=86400" />
</td>
<td>
<img src="https://github-stats-extended.vercel.app/api/top-langs?username=gabsgj&theme=tokyonight&hide_border=true&border_radius=12&layout=compact&langs_count=8&title_color=7aa2f7&text_color=c0caf5&bg_color=1a1b27&hide=Jupyter%20Notebook&cache_seconds=518400" />
</td>
</tr>
</table>

<img src="https://streak-stats.demolab.com?user=gabsgj&theme=tokyonight&hide_border=true&border_radius=12&background=1a1b27&fire=bb9af7&ring=7aa2f7&currStreakLabel=7dcfff" />
<br/>
<img src="https://github-readme-activity-graph.vercel.app/graph?username=gabsgj&theme=tokyo-night&bg_color=1a1b27&color=c0caf5&line=7aa2f7&point=bb9af7&hide_border=true" width="100%" />
</div>

---

## 🌳 𝙶𝚛𝚘𝚠𝚝𝚑

<div align="center">
<img src="https://raw.githubusercontent.com/gabsgj/gabsgj/output/bonsai.gif" width="380" alt="git-bonsai" />
<br/>
<sub>bonsai grown from commit history — quiet compounding, loud performance</sub>
</div>

<!--
BONSAI SETUP (one-time, keeps the tree above live):
1. Create repo file .github/workflows/bonsai.yml:
   name: git-bonsai
   on: { schedule: [{ cron: "0 0 * * *" }], workflow_dispatch: {} }
   jobs:
     bonsai:
       runs-on: ubuntu-latest
       steps:
         - uses: actions/checkout@v4
         - uses: egorthinks/git-bonsai@v1
           with: { github_token: ${{ secrets.GITHUB_TOKEN }} }
         - uses: stefanzweifel/git-auto-commit-action@v5
           with: { branch: output, create_branch: true }
2. Run it once manually under Actions, then the gif above renders.
Fallback while unset: the section gracefully shows alt text.
SNAKE ALTERNATIVE (if you prefer): Platane/snk/svg-only@v3 -> output branch.
STATS RELIABILITY (2026): using github-stats-extended fork + demolab streak
instead of paused official vercel/heroku endpoints. Self-host if critical.
-->

---

<div align="center">

### 📫 Let's build systems that matter

`AI Systems` · `Financial AI` · `Real-Time Infra` · `Computer Vision` · `Verified Software`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabrieljamesamara)
[![Portfolio](https://img.shields.io/badge/Portfolio-gabrieljames.me-1a1b27?style=flat&logo=googlechrome&logoColor=7aa2f7)](https://gabrieljames.me)
[![Email](https://img.shields.io/badge/Email-gabriel22dec@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:gabriel22dec@gmail.com)

<img src="https://komarev.com/ghpvc/?username=gabsgj&style=flat&color=7aa2f7" alt="Profile views" />
<br/><br/>
<code>$ echo "AI that compounds quietly, performs loudly." 🚀</code>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:1D4ED8,100:1a1b27&height=120&section=footer" />
