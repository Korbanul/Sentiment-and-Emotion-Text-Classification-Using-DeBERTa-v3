# Sentiment-and-Emotion-Text-Classification-Using-DeBERTa-v3

https://github.com/user-attachments/assets/7456d032-02a0-4384-b708-401726619046
This repository contains an end-to-end implementation of fine-tuning a DeBERTa-v3 model for multi-class text classification using the Hugging Face Transformers ecosystem.
The project is designed with research best practices, reproducibility, and scalability in mind.
## 📌 Key Features

- ✅ Uses **DeBERTa-v3** 
- ✅ Supports **multi-class classification**
- ✅ Compatible with **Google Colab, local GPU, and CPU**
- ✅ Efficient training on **subset datasets (e.g., 5,000 samples)**
- ✅ Model saving & loading for future inference
- ✅ Clean and modular training pipeline
  ## 🧠 Model Overview

- **Base Model:** `microsoft/deberta-v3-base`
- **Architecture:** Transformer with disentangled attention
- **Task:** Multi-class text classification
- **Loss Function:** Cross-Entropy Loss 
- **Optimizer:** adamW
- **Framework:** PyTorch + Hugging Face Transformers

> DeBERTa improves over BERT by decoupling content and positional information, leading to better contextual understanding.
** Dataset: https://www.kaggle.com/datasets/kushagra3204/sentiment-and-emotion-analysis-dataset**


