# **Embodied AI & Robotics Benchmarks**
系统性梳理和追踪**具身智能（Embodied AI）与机器人**领域的基准测试（Benchmarks）与评测平台。  

> **组织与维护 (Maintained by):** CAICT EAIBench Team  
> **收录范围 (Scope):** 真实环境评测 (Real-world) + 仿真器 (Simulation) + 世界模型 (World Models)
## **🤖 具身智能基准测试发展时间轴图**
![具身智能基准测试发展时间轴图](images/EAIBench.png)

**📑 目录 (Table of Contents)**

* [真实场景评测 (Real-World Evaluation)](#bookmark=id.svjplge6rdwg)
* [仿真环境评测 (Simulation Evaluation)](#bookmark=id.qx2fq06kg0uo)
* [基于世界模型的评测 (World Model Evaluation)](#bookmark=id.7pr0l1wqdwcs)

## ---

**🌍 真实场景评测 (Real-World Evaluation)**

针对真实物理环境中机器人操作、推理与泛化能力的基准测试 。近年来越来越注重规模化和复杂推理能力 。由于硬件搭建与数据收集成本较高，发布时间相对较晚，且多采用软硬件结合的挑战赛形式释出 。

| 基准名称 (Benchmark) | 首次发布/收录年份 | 第一作者机构 | 参考文献与链接信息 |
| :---- | :---- | :---- | :---- |
|  **[SCENEREPLICA](https://ieeexplore.ieee.org/abstract/document/10610180/)** | 2023 / 2024 | 得克萨斯大学达拉斯分校 | Khargonkar N, et al. Scenereplica: Benchmarking real-world robot manipulation by creating replicable scenes\[C\]//ICRA 2024\. (arXiv:2306.15620) |
|  [**RoboArena**](https://arxiv.org/abs/2506.18123) | 2024 / 2025 | 加州大学伯克利分校 | ATREYA P, et al. RoboArena: Distributed Real-World Evaluation of Generalist Robot Policies\[C\]//CoRL 2025\. (arXiv:2506.18123) |
|  [**RoboChallenge**](https://arxiv.org/abs/2510.17950) | 2025 | 上海交通大学 | Yakefu A, et al. RoboChallenge: Large-scale Real-robot Evaluation of Embodied Policies\[J\]. arXiv preprint arXiv:2510.17950, 2025\. (arXiv:2510.17950) |
|  [**ManipulationNet**](https://arxiv.org/abs/2603.04363) | 2026 | 莱斯大学 | Chen Y, et al. ManipulationNet: An Infrastructure for Benchmarking Real-World Robot Manipulation with Physical Skill Challenges and Embodied Multimodal Reasoning\[J\]. arXiv preprint arXiv:2603.04363, 2026\. (arXiv:2603.04363) |
|  [**ManipArena**](https://arxiv.org/abs/2603.28545) | 2026 | 中山大学 | Sun Y, et al. ManipArena: Comprehensive Real-world Evaluation of Reasoning-Oriented Generalist Robot Manipulation\[J\]. arXiv preprint arXiv:2603.28545, 2026\. (arXiv:2603.28545) |

## ---

**🎮 仿真环境评测 (Simulation Evaluation)**

基于虚拟仿真环境的低成本、可重复验证平台，涵盖长视野（Long-Horizon）任务、多模态指令与大规模物理仿真 。过去几年呈现爆发式增长，逐渐演进为长视野、多模态大语言模型导向以及安全性、物理规则的复合评测 。

| 基准名称 (Benchmark) | 首次发布年份 | 第一作者机构 | 参考文献与链接信息 |
| :---- | :---- | :---- | :---- |
|  **[BEHAVIOR-1K](https://proceedings.mlr.press/v205/li23a)** | 2022 | 斯坦福大学 | LI C, et al. BEHAVIOR-1K: A Benchmark for Embodied AI with 1,000 Everyday Activities and Realistic Simulation\[C\]//CoRL 2022/2023. (arXiv:2203.05060) |
|  [**VIMA-Bench**](https://openreview.net/forum?id=nkDMZ8yqBt) | 2022 | 哥伦比亚大学 | JIANG Y, et al. VIMA: Robot Manipulation with Multimodal Prompts\[C\]//ICML 2023\. (arXiv:2210.03094) |
|  [**ManiSkill2**](https://arxiv.org/abs/2302.04659) | 2023 | 加州大学圣地亚哥分校 | GU J, et al. ManiSkill2: A Unified Benchmark for Generalizable Manipulation Skills\[C\]//ICLR 2023\. (arXiv:2302.04659) |
|  [**LIBERO**](https://proceedings.neurips.cc/paper_files/paper/2023/hash/8c3c666820ea055a77726d66fc7d447f-Abstract-Datasets_and_Benchmarks.html) | 2023 | 得克萨斯大学奥斯汀分校 | LIU B, et al. LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning\[C\]//NeurIPS 2023\. (arXiv:2306.03310) |
|  [**Habitat 3.0**](https://openreview.net/forum?id=4znwzG92CE) | 2023 | Meta AI | PUIG X, et al. Habitat 3.0: A Co-Habitat for Humans, Avatars, and Robots\[C\]//ICLR 2024\. (arXiv:2310.13724) |
|  [**LoHoRavens**](https://arxiv.org/abs/2310.12020) | 2023 | 斯坦福大学 / 慕尼黑大学 | Zhang S, et al. Lohoravens: A long-horizon language-conditioned benchmark for robotic tabletop manipulation\[J\]. arXiv preprint arXiv:2310.12020, 2023\. (arXiv:2311.00967) |
|  [**THE COLOSSEUM**](https://arxiv.org/abs/2402.08191) | 2024 | Google DeepMind / 秘鲁圣保罗天主教大学 | PUMACAY W, et al. THE COLOSSEUM: A Benchmark for Evaluating Generalization for Robotic Manipulation\[C\]//RSS 2024\. (arXiv:2402.08148) |
|  [**RoboCasa**](https://arxiv.org/abs/2406.02523) | 2024 | 得克萨斯大学奥斯汀分校 | NASIRIANY S, et al. RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots\[C\]//RSS 2024\. (arXiv:2405.04803) |
|  [**CHORES (SPOC)**](https://openreview.net/forum?id=mOZEYx3x8s) | 2024 | Meta AI / 艾伦人工智能研究所 | EHSANI K, et al. SPOC: Imitating Shortest Paths in Simulation Enables Effective Navigation and Manipulation in the Real World\[C\]//CVPR 2024\. (arXiv:2406.11827) |
|  [**ManiSkill3**](https://arxiv.org/abs/2410.00425) | 2024 | 加州大学圣地亚哥分校 | Tao S, et al. Maniskill3: Gpu parallelized robotics simulation and rendering for generalizable embodied ai\[J\]. arXiv preprint arXiv:2410.00425, 2024\. (arXiv:2409.02323) |
|  [**ManiSkill-HAB**](https://openreview.net/forum?id=g6AJs0ob4X) | 2024 / 2025 | 加州大学圣地亚哥分校 | SHUKLA A, et al. ManiSkill-HAB: A Benchmark for Low-Level Manipulation in Home Rearrangement Tasks\[C\]//ICLR 2025\. OpenReview, 2025\. |
|  [**EmbodiedBench**](https://arxiv.org/abs/2502.09560) | 2025 | 伊利诺伊大学香槟分校 | YANG R, et al. EmbodiedBench: Comprehensive Benchmarking Multi-modal Large Language Models for Vision-Driven Embodied Agents\[C\]//ICML 2025\. (arXiv:2502.09560) |
|  [**RoboTwin**](https://openaccess.thecvf.com/content/CVPR2025/html/Mu_RoboTwin_Dual-Arm_Robot_Benchmark_with_Generative_Digital_Twins_CVPR_2025_paper.html) | 2025 | 香港大学 | MU Y, et al. RoboTwin: Dual-Arm Robot Benchmark with Generative Digital Twins\[C\]//CVPR 2025\. (arXiv:2506.01027) |
|  [**LeVERB-Bench**](https://arxiv.org/abs/2506.13751) | 2025 | 上海人工智能实验室 / 加州大学伯克利分校 | Xue H, et al. Leverb: Humanoid whole-body control with latent vision-language instruction\[J\]. arXiv preprint arXiv:2506.13751, 2025\. |
|  [**RoboTwin 2.0**](https://arxiv.org/abs/2506.18088) | 2025 | 上海交通大学 | Chen T, et al. Robotwin 2.0: A scalable data generator and benchmark with strong domain randomization for robust bimanual robotic manipulation\[J\]. arXiv preprint arXiv:2506.18088, 2025\. |
|  [**VLABench**](https://openaccess.thecvf.com/content/ICCV2025/html/Zhang_VLABench_A_Large-Scale_Benchmark_for_Language-Conditioned_Robotics_Manipulation_with_Long-Horizon_ICCV_2025_paper.html) | 2025 | 复旦大学 | ZHANG S, et al. VLABench: A Large-Scale Benchmark for Language-Conditioned Robotics Manipulation with Long-Horizon Reasoning Tasks\[C\]//ICCV 2025\. (arXiv:2412.18194) |
|  [**VLA-RISK**](https://openreview.net/forum?id=31EjDFwFEe) | 2025 | 香港大学 / 西安交通大学 | Ru Y, et al. VLA-Risk: Benchmarking Vision-Language-Action Models with Physical Robustness\[J\]. OpenReview, 2025\. |
|  [**RoboCasa365**](https://arxiv.org/abs/2603.04356) | 2026 | 得克萨斯大学奥斯汀分校 | NASIRIANY S, et al. RoboCasa365: A Large-Scale Simulation Framework for Training and Benchmarking Generalist Robots\[C\]//ICLR 2026\. (arXiv:2603.16861) |
|  [**EmbodiedGovBench**](https://arxiv.org/abs/2604.11174) | 2026 | 北京大学 / 哈尔滨工业大学 | Qin X, et al. EmbodiedGovBench: A Benchmark for Governance, Recovery, and Upgrade Safety in Embodied Agent Systems\[J\]. arXiv preprint arXiv:2604.11174, 2026\. |

## ---

**🌐 基于世界模型的评测 (World Model Evaluation)**

利用生成式视频或交互式物理世界模型作为“仿真器”进行策略验证与评估的新兴基准 。这种方式能够打破传统刚体物理引擎的限制 。

| 基准名称 (Benchmark) | 首次发布年份 | 第一作者机构 | 参考文献与链接信息 |
| :---- | :---- | :---- | :---- |
|  **[Vid2World](https://arxiv.org/abs/2505.14357)** | 2025 | 清华大学 | HUANG S, et al. Vid2World: Crafting Video Diffusion Models to Interactive World Models\[C\]//ICLR 2026\. (arXiv:2505.14357) |
|  [**WorldEval**](https://arxiv.org/abs/2505.19017) | 2025 | 美的集团+华东师范大学 | Li Y, et al. Worldeval: World model as real-world robot policies evaluator\[J\]. arXiv preprint arXiv:2505.19017, 2025\. |
|  [**1XWM**](https://www.1x.tech/1x-world-model.pdf) | 2025 / 2026 | 1X Technologies | Ho Daniel, et al. 1X World Model \[Online\]. 2025\. Available: [https://www.1x.tech/1x-world-model.pdf](https://www.1x.tech/1x-world-model.pdf). |

