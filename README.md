#Team: Clone this repo using git clone and then run on colab


# SRDC: Semantics-Based Ransomware Detection and Classification with LLM-Assisted Pre-Training

## 🛡 Category
Cybersecurity

---

## 📌 Problem Statement

Traditional ransomware detection systems fail to capture the hidden intent (internal semantics) behind API calls and ignore domain-level security expertise (external semantics). As a result, they struggle to detect zero-day ransomware threats that lack known signatures or fingerprints.

Existing AI-based detection systems typically require massive labeled datasets to achieve high accuracy, making them less adaptable to evolving threats.

---

## 🚀 Proposed Solution: SRDC Framework

We propose the **SRDC (Semantics-based Ransomware Detection and Classification)** framework, which introduces a novel:

> **LLM-Assisted Task-Adaptive Pre-Training (LATAP)** procedure.

The approach works by:

- Pre-training a GPT-2 model on expert cybersecurity knowledge
- Reconstructing raw execution logs into structured natural language representations
- Enabling the model to understand the semantic meaning of software behavior

This semantic-aware modeling allows SRDC to:

- Detect previously unseen ransomware families
- Improve generalization to zero-day attacks
- Reduce dependency on large labeled datasets

---

## 🧠 Key Innovation

- LLM-assisted semantic reconstruction of execution traces
- Task-adaptive pre-training using domain knowledge
- Transformer-decoder architecture for behavioral modeling
- Cybersecurity expert knowledge injection

---

## ⚙️ Tech Stack

- GPT-2
- Transformer Decoder Architecture
- PyTorch
- Hugging Face Transformers
- Python

---

## 🏗 Architecture Overview

1. Raw system logs collected from software behavior
2. Logs converted into semantic natural language phrases
3. GPT-2 pre-trained using LATAP methodology
4. Fine-tuned for ransomware classification
5. Evaluation using loss and perplexity metrics

---

## 📊 Model Performance

- Evaluation Loss: ~0.27
- Perplexity: ~1.31
- Successfully generalized across ransomware patterns

---

## 🔬 Future Improvements

- Cross-family validation on real-world ransomware datasets
- Integration with real-time monitoring systems
- Deployment as a security intelligence API
- Integration with SIEM pipelines

---

## 👨‍💻 Author
Keshav Rathi
