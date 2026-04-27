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

## MLP Results

- Test Accuracy: ~0.96 – 0.99
- Performance is comparable to SVM baseline (98.8%)

### Key Observations:
- No significant improvement over SVM
- Slight fluctuations due to small dataset size
- Dropout helps reduce overfitting

---
## Model Comparison

| Model | Accuracy | Notes |
|------|--------|------|
| SVM | 98.84% | Strong baseline |
| MLP | ~97–99% | Comparable performance |

### Interpretation

The deep neural network does not significantly outperform the classical SVM model. This is expected because:

- The dataset is small (569 samples)
- Features are already well-structured
- No spatial relationships exist

Thus, classical machine learning methods remain highly effective.

---
