# 📊 WhatsApp Chat Mood Analyzer

[![Python 3.10+](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Colab](https://img.shields.io/badge/Google-Colab-orange.svg)](https://colab.research.google.com/)

 **An AI-powered NLP system that automatically analyzes WhatsApp chat exports to detect emotional patterns and sentiment trends using Machine Learning.**

## 🎓 Project Information

**Course:** Artificial Intelligence  
**Instructor:** Sir Atif Luqman  

**Developed by:**
- Bilal Ahmed Shariff (24K-0701)
- Muhammad Umer Farooq (24K-0514)
- Fawad Noukhaiz (24K-0750)

---

## 🚀 Features

- ✅ **Dual-Model Analysis** - Combines VADER (rule-based) + Naive Bayes (ML) for accurate sentiment detection
- ✅ **Real WhatsApp Data** - Works with actual exported .txt files from WhatsApp
- ✅ **Interactive Visualizations** - 4+ charts showing mood timelines, per-person breakdowns, word clouds
- ✅ **High Accuracy** - 84% accuracy on test data
- ✅ **Privacy Focused** - All processing done locally, no data uploaded to cloud

---
## Dataset
The IMDB dataset used for training is not included in this repo due to file size.
Download it from Kaggle:
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
Place the downloaded CSV in the same directory before running the notebook.
---

## 📊 What It Does

| Feature | Description |
|---------|-------------|
| **Sentiment Classification** | Labels each message as Positive, Negative, or Neutral |
| **Mood Timeline** | Shows how sentiment changes over days/weeks |
| **Per-Person Analysis** | Compares sentiment patterns between different participants |
| **Word Cloud** | Visualizes most frequently used words in the chat |
| **Model Comparison** | Compares VADER vs Naive Bayes predictions |

🛠️ Technologies Used

Language: Python 3.10+
ML Framework: scikit-learn
NLP: NLTK, VADER
Visualization: Matplotlib, Seaborn, WordCloud
Data Processing: Pandas, NumPy
Environment: Google Colab / Local
