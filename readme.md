# 📩 Spam Detection Model using Machine Learning

## 📌 Project Overview

This project is a Machine Learning based Spam Detection System that classifies SMS messages as **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP) techniques.

The model is built using:

- Python
- Scikit-learn
- TF-IDF Vectorization
- Multinomial Naive Bayes

This project was developed as part of my learning journey in Artificial Intelligence and Machine Learning (AIML).

---

## 🚀 Problem Statement

Spam messages are a major issue in digital communication.  
The goal of this project is to build a machine learning model that can automatically detect whether a message is spam or not.

---

## 📂 Dataset

The dataset used is the **SMS Spam Collection Dataset**, which contains labeled SMS messages as:

- `ham` → Not Spam
- `spam` → Spam

Each row contains:
- Label
- Message text

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorizer
- Multinomial Naive Bayes

---

## 🔄 Project Workflow

1. Data Loading
2. Data Cleaning
3. Label Encoding (Ham → 0, Spam → 1)
4. Train-Test Split
5. Text Vectorization using TF-IDF
6. Model Training using Naive Bayes
7. Model Evaluation
8. Custom Prediction Function

---

## 🧠 Machine Learning Concepts Used

### 1️⃣ TF-IDF Vectorization
Converts text data into numerical feature vectors based on word importance.

### 2️⃣ Multinomial Naive Bayes
A probabilistic classifier based on Bayes' Theorem, widely used for text classification problems.

---

## 📊 Model Performance

- Accuracy: ~95% – 98%
- High precision and recall for spam classification
- Evaluated using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

## 🧪 Example Prediction

```python
predict_spam("Congratulations! You won a free iPhone")