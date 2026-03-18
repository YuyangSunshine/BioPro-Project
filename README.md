# BioProSuite: Towards Reliable Autonomous Wet-Lab Experimentation 🧪🤖

[![Webpage](https://img.shields.io/badge/Project-Webpage-blue.svg)](https://yuyangsulphur.github.io/bioprotocolbench/) [![Paper (Agent)](https://img.shields.io/badge/Paper-BioProAgent-red.svg)](https://arxiv.org/abs/2603.00876)
[![Paper (Bench)](https://img.shields.io/badge/Paper-BioProBench-red.svg)](https://arxiv.org/abs/2505.07889)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-BioProBench-yellow)](https://huggingface.co/BioProBench)

[English](#english) | [中文](#chinese)

---

<h2 id="english">English</h2>

Welcome to the official repository for the **BioProSuite** (formerly BioPro Project). This repository hosts the code, dataset, and evaluation framework for bridging the reasoning and execution gap in autonomous biological wet-lab experiments.

Our work consists of two major components:
1. **BioProBench:** The first large-scale benchmark (550k+ instances) dedicated to procedural reasoning in biological protocols.
2. **BioProAgent:** A neuro-symbolic agent framework anchored in a deterministic Finite State Machine (FSM), designed to ensure strict physical compliance and reliable execution in irreversible wet-lab environments.

### 🚀 Latest News
* **[2025-12]** Code and dataset (v1.0) are officially released!

### 📊 Performance Highlights
* **Safety First:** BioProAgent achieves **95.6%** physical hardware compliance, compared to just 21.0% for standard ReAct agents.
* **Self-Healing:** Demonstrates an **88.7%** success rate in autonomous error recovery for physical and logic violations.
* **High Efficiency:** Reduces token consumption by **~82%** in long-horizon tasks via Semantic Symbol Grounding.

### 🛠️ Quick Start
*(Provide your installation steps, environment setup, and basic usage scripts here)*
```bash
git clone [https://github.com/YuyangSunshine/bioprotocolbench.git](https://github.com/YuyangSunshine/bioprotocolbench.git)
cd bioprotocolbench
pip install -r requirements.txt
````

### 📝 Citation

If you find our data or framework useful, please cite our papers:

```bibtex
@article{liu2026bioproagent,
  title={BioProAgent: Neuro-Symbolic Grounding for Constrained Scientific Planning},
  author={Liu, Yuyang and Wang, Jingya and Lv, Liuzhenghao and Tian, Yonghong},
  journal={arXiv preprint arXiv:2603.00876},
  year={2026}
}

@article{liu2025bioprobench,
  title={BioProBench: Comprehensive Dataset and Benchmark in Biological Protocol Understanding and Reasoning},
  author={Liu, Yuyang and Lv, Liuzhenghao and Zhang, Xiancheng and Yuan, Li and Tian, Yonghong},
  journal={arXiv preprint arXiv:2505.07889},
  year={2025}
}
```

-----

\<h2 id="chinese"\>中文\</h2\>

欢迎来到 **BioProSuite** 的官方代码仓库。本项目旨在解决自主生物湿实验中大语言模型 (LLM) 推理与物理执行之间的巨大鸿沟。

我们的工作主要由两部分组成：

1.  **BioProBench:** 首个专注于生物实验草案过程推理的大规模基准测试（包含 55万+ 实例）。
2.  **BioProAgent:** 一种神经符号智能体框架。它将大模型的概率性规划锚定在确定性的有限状态机（FSM）中，以确保在不可逆的湿实验环境中实现严格的物理合规性和可靠执行。

### 🚀 最新动态

  * **[2025-12]** 代码与数据集 (v1.0) 正式开源发布！

### 📊 核心性能

  * **安全至上:** BioProAgent 达到了 **95.6%** 的物理硬件合规率，而标准 ReAct 智能体仅为 21.0%。
  * **自主纠错:** 在面临物理和逻辑违规注入时，展现了 **88.7%** 的自主错误恢复率。
  * **极高效率:** 通过语义符号接地技术，在长序列任务中将 Token 消耗降低了约 **82%**。

### 🛠️ 快速开始

*(在这里补充你的安装步骤、环境配置和基础运行脚本)*

```bash
git clone [https://github.com/YuyangSunshine/bioprotocolbench.git](https://github.com/YuyangSunshine/bioprotocolbench.git)
cd bioprotocolbench
pip install -r requirements.txt
```

### 📝 引用

如果您觉得我们的数据或框架对您的研究有帮助，请引用我们的论文：

```bibtex
@article{liu2026bioproagent,
  title={BioProAgent: Neuro-Symbolic Grounding for Constrained Scientific Planning},
  author={Liu, Yuyang and Wang, Jingya and Lv, Liuzhenghao and Tian, Yonghong},
  journal={arXiv preprint arXiv:2603.00876},
  year={2026}
}

@article{liu2025bioprobench,
  title={BioProBench: Comprehensive Dataset and Benchmark in Biological Protocol Understanding and Reasoning},
  author={Liu, Yuyang and Lv, Liuzhenghao and Zhang, Xiancheng and Yuan, Li and Tian, Yonghong},
  journal={arXiv preprint arXiv:2505.07889},
  year={2025}
}
```

