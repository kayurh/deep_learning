# 🧠 Deep Learning vs Classical ML — Breast Cancer Classification

## 📌 Project Overview

This project compares the performance of a **classical machine learning model** and a **deep neural network** on the Breast Cancer Wisconsin (Diagnostic) dataset.

The goal is to analyze how different approaches perform on structured tabular data and to evaluate whether deep learning provides advantages over traditional methods.

---

## 📊 Dataset

**Breast Cancer Wisconsin (Diagnostic)**

- Samples: 569
- Features: 30 (continuous)
- Task: Binary classification
- Labels:
  - Malignant (M)
  - Benign (B)
- Missing values: None

The dataset contains features extracted from digitized images of breast cell nuclei.

---

## 🎯 Objectives

- Implement a **baseline model** (SVM or Logistic Regression)
- Implement a **deep neural network (MLP)**
- Compare performance in terms of:
  - Accuracy
  - Overfitting
  - Training time
- Analyze strengths and weaknesses of each approach

---

## 🛠️ Technologies Used

- Python
- NumPy, Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib / Seaborn

---

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Removed irrelevant features (ID)
- Encoded labels (M → 1, B → 0)
- Normalized features
- Split into train/validation/test sets

---

### 2. Baseline Model
- Support Vector Machine (SVM) or Logistic Regression
- Achieves high accuracy due to structured data

---

### 3. Deep Learning Model
- Multi-Layer Perceptron (MLP)
- Fully connected layers with ReLU activation
- Sigmoid output layer for binary classification

---

### 4. Model Optimization
- Dropout
- L2 regularization
- Optimizer comparison (SGD vs Adam)

---

## 📈 Results (Expected)

| Model | Accuracy | Notes |
|------|--------|------|
| SVM / Logistic Regression | ~95–98% | Strong baseline |
| MLP | ~95–98% | Comparable performance |

---

## 🧠 Key Insight

Deep learning does not significantly outperform classical machine learning on small tabular datasets, but provides flexibility and scalability for more complex problems.

---

## 🚀 How to Run

pip install -r requirements.txt

---



