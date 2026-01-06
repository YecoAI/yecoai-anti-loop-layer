<div align="center">

# 🧠 YecoAI Mini-LLM Cognitive Layer

### Lightweight cognitive protection for Large Language Models

**Anti-loop • Amnesia detection • Semantic stability**

<br/>

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-experimental-orange.svg)]
[![RAM](https://img.shields.io/badge/avg%20RAM-~39MB-success.svg)]

<br/>

Developed by **[YecoAI](https://www.yecoai.com)**

</div>

---

## ✨ What is this?

**YecoAI Mini-LLM Cognitive Layer** is a **lightweight, modular guard layer** designed to sit *on top of* any LLM.

It does **not** replace the model.  
It **observes, evaluates, and stabilizes** the model’s output in real time.

Built to solve **real production problems**:
- Infinite loops
- Context loss (amnesia)
- Semantic collapse in long conversations
- Unstable autonomous agents

---

## 🧩 Core Capabilities

- 🔁 **Loop Detection**  
  Identifies structural and semantic repetition patterns.

- 🧠 **Amnesia Detection**  
  Detects loss of contextual continuity across turns.

- 🧯 **Semantic Degradation Guard**  
  Protects against meaning collapse over time.

- ⚡ **Ultra-Low Resource Usage**  
  Designed for embedded systems and edge deployments.

---

## 📊 Benchmark Results (v1.0)

> Real stress tests. No synthetic demos.

**Test Suite**
- 142 extreme stress scenarios
- Multilingual semantic traps
- Long-context degradation
- Loop-inducing prompts

```

Total Accuracy:         76.06%
Loop Detection (F1):    0.90
Normal Detection (F1):  0.71
Amnesia Detection (F1): 0.63
Average RAM Usage:     38.85 MB

```

✅ Loop detection is currently the strongest and near production-ready.  
⚠️ Amnesia detection is functional but still evolving.

Detailed reports are available in `/benchmarks`.

---

## 🏗️ High-Level Architecture

```

LLM Output
↓
Cognitive Evaluation Layer
├── Loop Detector
├── Amnesia Detector
└── Semantic Stability Guard
↓
Validated / Flagged Output

```

---

## 🚀 Use Cases

- Autonomous AI agents
- Long-running chat systems
- AI copilots & assistants
- Embedded / edge AI
- Guard layers for SaaS AI products
- LLM research & experimentation

---

## 🧪 Project Status

- **Version:** v3.0 (Stress-Tested Edition)
- **Maturity:** Experimental / Research-grade
- **Focus:** Stability, efficiency, interpretability

This repository is part of the **YecoAI Cognitive Systems stack**.

---

## 🏷️ Attribution & Credits (Required)

This project is developed and maintained by **YecoAI**.

**Attribution is REQUIRED** in **any usage**, including:
- Modified versions
- Commercial products
- SaaS platforms
- Research publications
- Closed-source integrations

You must retain:
- This README attribution
- The `LICENSE` file
- The `NOTICE` file

---

## 📄 License

Licensed under the **Apache License 2.0**.

✔ Commercial use  
✔ Modification  
✔ Redistribution  
✔ Closed-source integration  

**Attribution and preservation of notices are mandatory.**

See `LICENSE` and `NOTICE` for details.

---

## 🌐 About YecoAI

**YecoAI** builds next-generation cognitive systems focused on:

- AI stability & safety
- Autonomous agents
- Real-world deployability
- Low-overhead intelligent layers

Website : https://www.yecoai.com
Discord : https://discord.gg/rBZscZtMvX
GitHub : https://github.com/YecoAI

---

<div align="center">

© 2026 **[YecoAI](https://www.yecoai.com)**  
Original author: **Marco (HighMark / YecoAI)**

</div>

