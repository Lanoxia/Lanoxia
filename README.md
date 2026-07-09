# Hi there, I'm Zixuan Li 👋

<!-- 
  ELEGANT TWO-COLUMN HEADER 
  This table layout creates a professional, scientist-style homepage.
  Ensure profile.jpg and CV_Zixuan Li.pdf are in the root of your repository.
-->
<table border="0" width="100%">
  <tr>
    <!-- Left Column: Large Full-Body Photo & CV Button -->
    <td align="center" valign="top" width="35%">
      <a href="https://github.com/Lanoxia/Lanoxia/blob/main/CV_Zixuan%20Li.pdf" target="_blank">
        <img src="profile.jpg" alt="Zixuan Li's Full Body Profile" width="240" style="border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.15); transition: transform 0.2s ease;" onmouseover="this.style.transform='scale(1.02)';" onmouseout="this.style.transform='scale(1)';" />
      </a>
      <br /><br />
      <a href="https://github.com/Lanoxia/Lanoxia/blob/main/CV_Zixuan%20Li.pdf" target="_blank">
        <img src="https://img.shields.io/badge/📄_View_My_CV_/_Resume-0d1117?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=red" style="border-radius: 4px;" />
      </a>
    </td>
    <!-- Right Column: Quick Bio & Badges -->
    <td valign="top" width="65%" style="padding-left: 20px;">
      <p align="left">
        <img src="https://img.shields.io/badge/HKUST-BDT_'27_(Incoming)-003865?style=flat-square&logoColor=white" />
        <img src="https://img.shields.io/badge/Tencent_WeChat-Research_Intern-07C160?style=flat-square&logo=wechat&logoColor=white" />
        <img src="https://img.shields.io/badge/COLM_2026-First_Author-0969da?style=flat-square" />
      </p>
      <p>
        I am an incoming Master's student in <b>Big Data Technology</b> at <b>The Hong Kong University of Science and Technology (HKUST)</b>, and a graduate of <b>Jilin University</b> (B.Eng. in CS, Top 13%). Currently, I am working as a Research Intern & Algorithm Engineer at <b>Tencent WeChat Headquarters</b>.
      </p>
      <p>
        My work thrives at the intersection of <b>Large Language Models (LLMs)</b>, <b>Agent Systems Infrastructure</b>, and <b>Hardware-Software Co-Design for Deep Learning</b>.
      </p>
      <p>
        <b> Research Focus:</b><br />
        • <b>LLMs:</b> Parameter-efficient fine-tuning (PEFT/LoRA), active learning, and data-centric efficiency.<br />
        • <b>Agent Infrastructure:</b> Multi-turn tool integration, high-concurrency workflows, and topological scaling.<br />
        • <b>AI Architecture & HPC:</b> Near-Memory Processing (NMP) and hardware-software co-simulation.
      </p>
    </td>
  </tr>
</table>

---

## Featured Research & Publications

### FLINT: An Active Learning Framework for LoRA via Curvature-Aware Data Selection and Fine-Tuning
* **First Author** | *Accepted to the **Conference on Language Modeling (COLM) 2026***
* Designed a two-stage active learning pipeline integrating entropy pre-filtering, SVD cold-start stabilization, and **K-FAC curvature-aware influence scoring** optimized for the LoRA manifold.
* Streamlined candidate evaluations by 70-80% via adaptive entropy thresholding, constraining data selection to a strict 20% budget.
* Achieved LLaMA-3.2-3B accuracies of **71.13% / 66.8% / 73.0%** on GSM8K/BBH/StrategyQA, consistently outperforming full-data LoRA baselines.
* Accelerated end-to-end selection to 1.67h on a single V100 GPU (**5.73× speedup over LESS**, 2.80× over DataInf) with a peak VRAM of 16.6GB.

### Dimension-Mapped Near-Memory Computing for Sparse Attention Acceleration
* **First Author** | *Supervised by Prof. Xiaohui Wei @ Jilin University HPC Center*
* Proposed a novel **dimension-based dataflow mapping** (as opposed to token-level partitioning) for Near-Memory Processing (NMP) systems, enforcing strict load balancing across parallel DRAM bank arrays.
* Developed a trace-driven hardware-software co-simulation engine using PyTorch hooks and **SimPy discrete-event modeling** to simulate physical DRAM row-buffer conflicts.
* Achieved a **27.7% reduction** in end-to-end LLM inference step latency ($6920\text{ ns} \rightarrow 5000\text{ ns}$) and minimized workload variance (C.V. dropped from 23.89% to 7.09%).

---

## Industry Experience

### Tencent WeChat Headquarters (WeChat Agent Research)
*Research Intern (E-commerce Governance Team)* | *05/2026 - Present*
*   **Algorithmic Optimization for Multi-Turn Tool Integration:** Formulated an in-context tool composition mechanism within hierarchical skill abstractions, accelerating end-to-end response velocity by **2.0x** (20s $\rightarrow$ 10s).
*   **Topological Design of Agentic Execution Systems:** Conceptualized a hybrid architecture integrating heuristic routing, stateful workflows, and autonomous agentic fallbacks; achieved a state-of-the-art first-token latency of **5-6s** under high-concurrency settings.

### Ping An Technology Semantics Laboratory (NLP Research Group)
*Research Intern* | *12/2025 - 05/2026*
*   **Mitigating Catastrophic Forgetting:** Developed an interactive conversational decision framework; fine-tuned parameterized LLMs (**Qwen3-8B**) via synthetic, chain-of-thought (CoT) alignment topologies to mitigate knowledge degradation.
*   **High-Dimensional Representation Pipelines:** Engineered a dual-stage cascade infrastructure leveraging dense neural vector retrieval coupled with fine-grained LLM classification; expanded the evaluation space from 31 to **340 semantic classes** while maintaining Precision/Recall > 95%.

---

## Tech Stack & Toolbox

| Category | Technologies |
| :--- | :--- |
| **Programming** | `Python` `C/C++` `CUDA C` `Verilog` `SQL` `Java` `Lua` |
| **Machine Learning** | `PyTorch` `Hugging Face (Transformers, PEFT)` `Ray` `DeepSpeed` |
| **LLM Infrastructure** | `ReAct Framework` `Model Context Protocol (MCP)` `Tool-Use` `Dify` `SSE Streaming` |
| **Data Systems & Simulation** | `SimPy (Discrete-Event Simulation)` `Spark SQL` `WeData` `MySQL` |


---

## ✉️ Contact & Connect
*   **Email:** [lizx2122@mails.jlu.edu.cn](mailto:lizx2122@mails.jlu.edu.cn) & [minkalee0715@gmail.com](mailto:minkalee0715@gmail.com)
