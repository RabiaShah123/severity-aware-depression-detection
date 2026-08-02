# severity-aware-depression-detection
Severity-aware depression detection using Machine Learning, Deep Learning, ModernBERT, and Explainable AI (SHAP &amp; LIME
# 🧠 Severity-Aware Depression Detection Using ModernBERT

## 📖 Project Overview

This repository contains my MRes Artificial Intelligence research project on **severity-aware depression detection using social media text**. The project investigates and compares Traditional Machine Learning, Deep Learning, and Transformer-based models for multi-class depression classification, with a particular focus on **ModernBERT**.

A corrected machine learning pipeline was implemented to prevent data leakage by removing duplicate samples, performing a stratified train-test split, and applying oversampling only to the training data. The project also incorporates Explainable Artificial Intelligence (XAI) techniques, including **SHAP** and **LIME**, to improve model transparency and interpretability.

> **Note:** This repository is currently private while my dissertation is under examination. It will be made public after submission.

---

## 🎯 Research Objectives

- Develop an AI-based framework for early depression detection.
- Compare Machine Learning, Deep Learning, and Transformer-based models.
- Fine-tune ModernBERT for multi-class depression classification.
- Interpret model predictions using SHAP and LIME.
- Evaluate models using comprehensive performance metrics.

---

## 📊 Dataset

The project uses a social media text dataset containing six mental health categories:

- Atypical Depression
- Bipolar Disorder
- Major Depressive Disorder
- No Depression
- Postpartum Depression
- Psychotic Depression

The dataset underwent preprocessing, duplicate removal, stratified train-test splitting, and training-only oversampling to ensure a robust and unbiased evaluation.

---

## 🧠 Models Implemented

### Traditional Machine Learning
- Multinomial Naïve Bayes
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (Linear & RBF)
- XGBoost

### Deep Learning
- LSTM
- Bidirectional LSTM (BiLSTM)

### Transformer Model
- ModernBERT

---

## 🔍 Explainable AI (XAI)

Model predictions are interpreted using:

- SHAP (SHapley Additive exPlanations)
- LIME (Local Interpretable Model-agnostic Explanations)

These techniques help identify the textual features that influence model predictions and improve the transparency of the AI system.

---

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- Weighted F1-score
- Macro F1-score
- Confusion Matrix
- ROC-AUC

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- PyTorch
- Hugging Face Transformers
- ModernBERT
- SHAP
- LIME
- Matplotlib
- Jupyter Notebook

---

## 📂 Repository Structure

```
├── notebooks/
├── data/
├── figures/
├── models/
├── results/
├── requirements.txt
└── README.md
```

---

## 🚀 Key Features

- Severity-aware depression classification
- ModernBERT fine-tuning
- Data leakage prevention pipeline
- Explainable AI using SHAP and LIME
- Comparative evaluation of ML, DL, and Transformer models

---

## 🎓 Academic Context

This project was developed as part of the **Master of Research (MRes) in Artificial Intelligence** at the **University of Bolton**.

---

## 👩‍💻 Author

**Rabia Shah**

MRes Artificial Intelligence  
University of Bolton

---

## 📄 License

This repository is intended for academic and research purposes. Please contact the author before reproducing or redistributing any part of this work.
