# Interview_Knowledge

A personal knowledge base for technical interview preparation and systematic review of core Computer Science and AI topics.

The goal of this repository is simple: **turn scattered knowledge into material that can be reviewed, explained, and implemented.**

## What I Study

The current knowledge base covers:

| Area | Topics |
| --- | --- |
| Data Structures & Algorithms | Sorting, hashing, linked lists, trees, graphs, dynamic programming, greedy algorithms, heaps, strings |
| Machine Learning | Linear / logistic regression, SVM, PCA, GBDT, decision trees, random forests, KNN, boosting, HMM, CRF |
| Deep Learning | Backpropagation, CNN, RNN / LSTM, normalization, optimization, regularization |
| Large Language Models | Transformer, attention, RoPE, GQA, tokenization, SFT, LoRA, RLHF / DPO, RAG, Agent, MoE, quantization |
| CS Fundamentals | Python, operating systems, computer networks, databases, Redis, distributed systems |
| Reinforcement Learning | MDP, dynamic programming, Q-learning, DQN, policy gradient, PPO, GRPO |
| Optimization | SGD, Momentum, Adam / AdamW, learning-rate scheduling, numerical and classical optimization |
| Computer Vision | CNN, object detection, YOLO, segmentation, U-Net, metric learning, SAM |
| NLP | Text representation, language models, embeddings, sequence models, Transformer, BERT / GPT basics |
| Time Series | ARMA / ARIMA, exponential smoothing, decomposition, feature engineering, forecasting and anomaly detection |

## Repository

The main study material is organized here:

**[Interview & AI Study Notes](Autumn-Recruit-Algo-Notes/)**

Inside the notes, most topics follow a practical learning loop:

```text
Concept
  ↓
Derivation / Explanation
  ↓
Implementation
  ↓
Experiment / Numerical Check
  ↓
Interview Questions
  ↓
Review
```

## How I Use This Repository

I use this repository for three different levels of preparation:

1. **Understand** — know what a concept means and why it works.
2. **Implement** — be able to translate the idea into code instead of only memorizing definitions.
3. **Explain** — answer common interview questions clearly and concisely.

For algorithms, the emphasis is on patterns and reusable templates.

For ML / DL / LLM topics, the emphasis is on connecting formulas, model structure, code, and practical behavior.

For CS fundamentals, the emphasis is on building a compact review system for repeated interview preparation.

## Current Structure

```text
Interview_Knowledge/
├── Autumn-Recruit-Algo-Notes/
│   ├── 01-数据结构与算法/
│   ├── 02-机器学习/
│   ├── 03-深度学习/
│   ├── 04-LLM大模型/
│   ├── 05-八股与工程/
│   ├── 06-面试复盘/
│   ├── 07-强化学习/
│   ├── 08-优化算法/
│   ├── 09-计算机视觉/
│   ├── 10-自然语言处理/
│   └── 11-时间序列/
├── LICENSE
└── README.md
```

## Learning Principles

- Prefer understanding over memorization.
- Prefer runnable examples over isolated formulas.
- Keep notes concise enough to review repeatedly.
- Record mistakes and weak points instead of only collecting solutions.
- Be able to explain important concepts without relying on the notes.
- Revisit fundamentals regularly.

## Usage

Clone the repository:

```bash
git clone https://github.com/xihao-yang/Interview_Knowledge.git
cd Interview_Knowledge
```

Most executable notebooks can be opened with Jupyter:

```bash
pip install numpy matplotlib jupyter nbclient
jupyter notebook
```

Some notebooks additionally use libraries such as `scikit-learn` and `torch`.

## Notes

This repository is maintained primarily as my personal study and interview-preparation workspace, so the structure and content may continue to evolve as I learn and review new topics.

Some materials in this repository are based on or adapted from third-party open-source resources. Applicable copyright and license notices are retained with those materials.

## License

See [LICENSE](LICENSE) and the license files contained in individual material directories where applicable.
