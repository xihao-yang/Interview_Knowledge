# Interview & AI Study Notes

> Personal study notes for technical interviews, built around **understanding → implementation → explanation → review**.

This directory is the main learning area of my `Interview_Knowledge` repository.  
I use it to organize core topics in algorithms, computer science, machine learning, deep learning, LLMs, and related AI fields.

---

## Study Goals

I do not want this repository to become a simple collection of materials.

For each topic, the goal is to be able to:

- **Understand** the core idea and assumptions.
- **Derive** important formulas when necessary.
- **Implement** key algorithms or model components.
- **Verify** behavior with runnable examples.
- **Explain** the topic clearly in an interview.
- **Review** mistakes and weak points repeatedly.

My preferred learning loop is:

```text
Concept
   ↓
Why it works
   ↓
Derivation / Structure
   ↓
Implementation
   ↓
Experiment / Verification
   ↓
Interview Questions
   ↓
Review
```

---

## Topics

| Module | Focus |
| --- | --- |
| [01 · 数据结构与算法](01-数据结构与算法/) | 排序、哈希、链表、树、图、回溯、动态规划、贪心、堆、字符串 |
| [02 · 机器学习](02-机器学习/) | 线性/逻辑回归、SVM、PCA、GBDT、随机森林、KNN、Boosting、HMM、CRF |
| [03 · 深度学习](03-深度学习/) | BP、CNN、RNN/LSTM、归一化、优化器、初始化与正则化 |
| [04 · LLM 大模型](04-LLM大模型/) | Transformer、Attention、RoPE、GQA、Tokenizer、SFT、LoRA、DPO/RLHF、RAG、Agent、MoE、量化 |
| [05 · 八股与工程](05-八股与工程/) | Python、操作系统、计算机网络、数据库、Redis、分布式、工程工具 |
| [06 · 面试复盘](06-面试复盘/) | 面试记录、问题整理、薄弱点复盘 |
| [07 · 强化学习](07-强化学习/) | MDP、DP、Q-Learning、DQN、Policy Gradient、PPO、GRPO |
| [08 · 优化算法](08-优化算法/) | SGD、Momentum、Adam/AdamW、学习率、二阶优化、经典优化 |
| [09 · 计算机视觉](09-计算机视觉/) | 图像基础、CNN、目标检测、YOLO、分割、U-Net、SAM |
| [10 · 自然语言处理](10-自然语言处理/) | 文本表示、语言模型、词向量、序列模型、Transformer、BERT/GPT |
| [11 · 时间序列](11-时间序列/) | ARMA/ARIMA、指数平滑、分解、特征工程、预测与异常检测 |

---

## How I Use the Notes

### Algorithms

The priority is not memorizing individual solutions.

I focus on:

- recognizing reusable patterns;
- understanding time and space complexity;
- writing common templates without reference;
- recording why a wrong solution fails.

### ML / DL / LLM

For model-related topics, I try to connect four layers:

```text
Math → Model Structure → Code → Observable Behavior
```

A formula is useful only when I can explain what it changes in the actual model.

### CS Fundamentals

For operating systems, networks, databases, Redis, and distributed systems, the target is:

- concise definitions;
- mechanism-level understanding;
- common interview follow-up questions;
- practical examples where possible.

---

## Notebook Environment

Most notebooks can be opened locally with Jupyter.

```bash
pip install numpy matplotlib jupyter nbclient
jupyter notebook
```

Some notebooks also use:

```bash
pip install scikit-learn torch
```

The exact dependencies depend on the notebook.

---

## Progress

I treat this repository as a long-term study workspace rather than a finished course.

Useful entry points:

- [ROADMAP.md](ROADMAP.md) — learning order and progress
- [01-数据结构与算法/高频题单.md](01-数据结构与算法/高频题单.md) — algorithm review
- [02-机器学习/高频面试题.md](02-机器学习/高频面试题.md) — ML interview review
- [03-深度学习/高频面试题.md](03-深度学习/高频面试题.md) — DL interview review
- [04-LLM大模型/高频面试题.md](04-LLM大模型/高频面试题.md) — LLM interview review

---

## Notes on Sources

This directory contains materials that I use and reorganize for personal study. Some content is based on or adapted from third-party open-source resources.

Applicable copyright and license notices are retained in the corresponding `LICENSE` files.

---

Back to the main repository: [Interview_Knowledge](../README.md)
