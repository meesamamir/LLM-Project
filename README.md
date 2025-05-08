# LLM-Project

# 🗞️ News Headline Classification using Traditional & Transformer-based LLMs

## 🚀 Overview

This repository demonstrates a unified pipeline for news headline classification across two phases:

* **Phase 01**: Traditional ML & Deep Learning (bag‑of‑words, logistic regression, neural nets, LSTM, XGBoost, Random Forest)
* **Phase 02**: Transformer-based LLMs (BERT, DistilBERT, RoBERTa) with **LoRA** and **Prompt Tuning**

Targets four categories: **World**, **Sports**, **Business**, **Sci/Tech**.

---

## 📊 Dataset

Using the **AG News** dataset:

* 120 000 training samples
* 7 600 test samples
* Balanced across 4 classes

---

## ⚙️ Phase 01 — Traditional ML & Deep Learning

| Model                    | Test Accuracy |
| ------------------------ | ------------: |
| Logistic Regression (L2) |        91.64% |
| LSTM Classifier          |        90.12% |
| Deep Neural Network      |        74.96% |
| Random Forest            |        85.79% |
| XGBoost                  |        87.93% |

---

## 🤖 Phase 02 — Transformer-based LLMs

| Model                | Test Accuracy |
| -------------------- | ------------: |
| BERT                 |        94.72% |
| DistilBERT           |        94.75% |
| RoBERTa              |        94.82% |
| BERT + LoRA          |        94.54% |
| DistilBERT + LoRA    |        94.60% |
| RoBERTa + LoRA       |        94.95% |
| BERT + Prompt Tuning |        94.36% |

---

## 📌 Key Features

* Single codebase for classical and transformer models
* **LoRA** for parameter‑efficient fine‑tuning
* **Prompt Tuning** with virtual tokens for fast adaptation
* Comprehensive visualizations (confusion matrices, loss curves, Zipf’s law, confidence histograms)
* Manual headline prediction with seven models

---

## 🧪 Getting Started

Clone the repo and run the Colab notebook:

```bash
git clone https://github.com/meesamamir/LLM-Project.git
```

👉 [Open in Colab](https://colab.research.google.com/github/meesamamir/LLM-Project/blob/main/LLM_Project.ipynb)

---

## 📈 Results Summary

Transformer models outperform classical baselines. **RoBERTa + LoRA** achieved the highest F1 (94.95%), and **Prompt Tuning** offers quick adaptation with minimal parameters.

---

## 🧠 Lessons Learned

* Contextualized LLMs generalize without manual feature engineering
* LoRA cuts training cost with little performance loss
* Prompt tuning enables flexible task specification using text prompts

---

## 🙋‍♂️ Authors

Nitin Nagarkar (https://github.com/nitinnagarkar25)

Meesam Amir Syed (https://github.com/meesamamir)

---

## 📄 License

