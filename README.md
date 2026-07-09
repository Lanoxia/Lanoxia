# Hi there, I'm Zixuan Li 👋

<p align="center">
  <img src="https://img.shields.io/badge/🎓_HKUST-BDT_'27_(Incoming)-003865?style=flat-square&logo=hong-kong-university-of-science-and-technology&logoColor=white" />
  <img src="https://img.shields.io/badge/🤖_Tencent_WeChat-Research_Intern-07C160?style=flat-square&logo=wechat&logoColor=white" />
  <img src="https://img.shields.io/badge/📝_COLM_2026-First_Author-0969da?style=flat-square" />
</p>

<!-- 
  ELEGANT PROFILE HEADER
  To use your own photo, upload your square picture (e.g., profile.jpg)
  to this repository and replace "profile.jpg" below.
-->
<p align="center">
  <img src="profile.jpg" alt="Zixuan Li's Profile" width="180" height="180" style="border-radius: 50%; border: 4px solid #fff; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

I am an incoming Master's student in **Big Data Technology** at **The Hong Kong University of Science and Technology (HKUST)**, and a graduate of **Jilin University** (B.Eng. in CS, Top 13%). Currently, I am a Research Intern & Algorithm Engineer at **Tencent WeChat Headquarters (E-commerce Governance Team)**. 

My work thrives at the intersection of **Large Language Models (LLMs)**, **Agent Systems Infrastructure**, and **Hardware-Software Co-Design for Deep Learning**.

---

## 🔥 Research Interests
*   **Large Language Models (LLMs):** Parameter-efficient fine-tuning (PEFT/LoRA), active learning, and data-centric efficiency.
*   **Agentic Execution Systems:** Multi-turn tool integration, high-concurrency/low-latency workflows, and topological scaling.
*   **AI Architecture & HPC:** Near-Memory Processing (NMP), trace-driven hardware-software co-simulation, and sparse attention acceleration.

---

## 🚀 Featured Research & Publications

### 📄 FLINT: An Active Learning Framework for LoRA via Curvature-Aware Data Selection and Fine-Tuning
* **First Author** | *Accepted to the **Conference on Language Modeling (COLM) 2026***
* Designed a two-stage active learning pipeline integrating entropy pre-filtering, SVD cold-start stabilization, and **K-FAC curvature-aware influence scoring** optimized for the LoRA manifold.
* Streamlined candidate evaluations by 70-80% via adaptive entropy thresholding, constraining data selection to a strict 20% budget.
* Achieved LLaMA-3.2-3B accuracies of **71.13% / 66.8% / 73.0%** on GSM8K/BBH/StrategyQA, consistently outperforming full-data LoRA baselines.
* Accelerated end-to-end selection to 1.67h on a single V100 GPU (**5.73× speedup over LESS**, 2.80× over DataInf) with a peak VRAM of 16.6GB.

### 💻 Dimension-Mapped Near-Memory Computing for Sparse Attention Acceleration
* **First Author** | *Supervised by Prof. Xiaohui Wei @ Jilin University HPC Center*
* Proposed a novel **dimension-based dataflow mapping** (as opposed to token-level partitioning) for Near-Memory Processing (NMP) systems, enforcing strict load balancing across parallel DRAM bank arrays.
* Developed a trace-driven hardware-software co-simulation engine using PyTorch hooks and **SimPy discrete-event modeling** to simulate physical DRAM row-buffer conflicts.
* Achieved a **27.7% reduction** in end-to-end LLM inference step latency ($6920\text{ ns} \rightarrow 5000\text{ ns}$) and minimized workload variance (C.V. dropped from 23.89% to 7.09%).

---

## 💼 Industry Experience

### 🟢 Tencent WeChat Headquarters (WeChat Agent Research)
*Research Intern (E-commerce Governance Team)* | *05/2026 - Present*
*   **Algorithmic Optimization for Multi-Turn Tool Integration:** Formulated an in-context tool composition mechanism within hierarchical skill abstractions, accelerating end-to-end response velocity by **2.0x** (20s $\rightarrow$ 10s).
*   **Topological Design of Agentic Execution Systems:** Conceptualized a hybrid architecture integrating heuristic routing, stateful workflows, and autonomous agentic fallbacks; achieved a state-of-the-art first-token latency of **5-6s** under high-concurrency settings.

### 🟠 Ping An Technology Semantics Laboratory (NLP Research Group)
*Research Intern* | *12/2025 - 05/2026*
*   **Mitigating Catastrophic Forgetting:** Developed an interactive conversational decision framework; fine-tuned parameterized LLMs (**Qwen3-8B**) via synthetic, chain-of-thought (CoT) alignment topologies to mitigate knowledge degradation.
*   **High-Dimensional Representation Pipelines:** Engineered a dual-stage cascade infrastructure leveraging dense neural vector retrieval coupled with fine-grained LLM classification; expanded the evaluation space from 31 to **340 semantic classes** while maintaining Precision/Recall > 95%.

---

## 🛠️ Tech Stack & Toolbox

| Category | Technologies |
| :--- | :--- |
| **Programming** | `Python` `C/C++` `CUDA C` `Verilog` `SQL` `Java` `Lua` |
| **Machine Learning** | `PyTorch` `Hugging Face (Transformers, PEFT)` `Ray` `DeepSpeed` |
| **LLM Infrastructure** | `ReAct Framework` `Model Context Protocol (MCP)` `Tool-Use` `Dify` `SSE Streaming` |
| **Data Systems & Simulation** | `SimPy (Discrete-Event Simulation)` `Spark SQL` `WeData` `MySQL` |

---

## 📊 GitHub Stats & Open Source Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Lanoxia&show_icons=true&theme=nord&count_private=true" alt="Zixuan Li's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lanoxia&layout=compact&theme=nord" alt="Top Langs" width="48%" />
</p>

---

## ✉️ Contact & Connect
*   **Email:** [lizx2122@mails.jlu.edu.cn](mailto:lizx2122@mails.jlu.edu.cn)
*   **Academic Plan:** Preparing for Fall 2027 Ph.D. Applications in LLM efficiency and agent systems.
