# Towards Scene Text Recognition in Rainy Weather Conditions
ICDAR2025 — Conference Paper

This repository contains the datasets, code, fine-tuned models, and evaluation scripts for my ICDAR2025 paper *"Towards Scene Text Recognition in Rainy Weather Conditions"*.

---

## 📄 Contents
- `data/` — Generated rainy dataset and real rainy dataset (links & instructions)
- `benchmarks/` — Results of existing STR models evaluated on the datasets
- `finetuning/` — Fine-tuning code + checkpoints of best-performing STR models
- `evaluation/` — Jupyter/Colab notebooks for computing WER, CER, Precision, Recall, F1-Score

---

## 🌧️ Datasets
🌧️ Datasets

- **Generated Rainy Dataset** — created using our rain synthesis pipeline  
  - [Train (Google Drive link)](https://drive.google.com/xxxx)  
  - [Validation (Google Drive link)](https://drive.google.com/yyyy)  
  - [Test (Google Drive link)](https://drive.google.com/zzzz)  

- **Real Rainy Dataset** — collected from real driving scenarios  
  - [Train (Google Drive link)](https://drive.google.com/aaaa)  
  - [Validation (Google Drive link)](https://drive.google.com/bbbb)  
  - [Test (Google Drive link)](https://drive.google.com/cccc)  

---

## 📊 Benchmarking
We benchmarked multiple existing STR models on both datasets.  
- Benchmark results are in `benchmarks/`.  
- Models tested include [PARSeq](https://github.com/baudm/parseq) and others.  

---

## 🧩 Fine-Tuning
- The best-performing STR model was further fine-tuned on our datasets.  
- Fine-tuning code and training scripts are provided in `finetuning/`.  
- Fine-tuned model checkpoints are available here: [Google Drive link]() *(to be added)*.  

---

## 📈 Evaluation Metrics
- Evaluation metrics include **WER, CER, Precision, Recall, and F1-Score**.  
- Notebook: `metrics.ipynb`  
- Can be run directly in Google Colab.  

---

## 🚀 How to Use
1. Download datasets and checkpoints
-Generated Rainy Dataset
-Real Rainy Dataset
-Finetuned Checkpoints
2. Run fine-tuning on STR models
-Open finetuning/model_finetuning.ipynb in Colab
-Train using the provided datasets
-Reproduce results with checkpoints
-Load the fine-tuned checkpoints from the provided links
3. Run evaluation notebook
-Open evaluation/metrics.ipynb in Colab
-Evaluate recognition performance using:
--WER (Word Error Rate)
--CER (Character Error Rate)
--Precision, Recall, and F1-Score


