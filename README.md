# 🧠 Banknote Authentication Classification
**Name:** Adeyemi Toba  
**Date:** 2025-03-26  

## 📌 Project Overview
This project demonstrates a binary classification approach using the Banknote Authentication dataset. The goal is to predict whether a banknote is **genuine** or **fake** based on numerical features derived from wavelet-transformed images.

Models used:
- Logistic Regression
- Random Forest Classifier

Performance is evaluated using accuracy, precision, recall, F1-score, and confusion matrix.

---

## 📁 Dataset
**Source**: [UCI Machine Learning Repository – Banknote Authentication](https://archive.ics.uci.edu/ml/datasets/banknote+authentication)

**Features:**
- `variance`
- `skewness`
- `kurtosis`
- `entropy`

**Target:**
- `class`:  
  - 0 = Genuine  
  - 1 = Fake

---

## 🔍 Notebook Preview
📓 **Notebook Link**: [classification_Toba.ipynb]

📄 **Peer Review**: [peer_review.md]

---

## 🛠️ Setup Instructions

### ▶️ To Run Locally:
1. Clone the repo:
   ```bash
   git clone https://github.com/Adeyemitoba/ml_classification_Toba.git
   cd ml_classification_Toba

## Create and activate virtual environment:
python -m venv venv
.\venv\Scripts\activate     # On Windows
source venv/bin/activate   # On macOS/Linux

## Install dependencies:
pip install -r requirements.txt

## Launch Jupyter Notebook:
jupyter notebook

## ✅ Key Results Comparison

| Model               | Accuracy | Precision (Avg) | Recall (Avg) | F1-Score (Avg) | Errors |
|---------------------|----------|------------------|--------------|----------------|--------|
| Logistic Regression | 98%      | 0.98             | 0.98         | 0.98           | 6      |
| Random Forest       | 99%      | 0.99             | 0.99         | 0.99           | 2      |

📊 **Observation**:  
Random Forest slightly outperformed Logistic Regression in all key metrics and made fewer prediction errors. It was especially strong in identifying genuine notes with perfect recall.
