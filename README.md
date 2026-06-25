# CV Classification using Machine Learning & NLP

An AI-powered resume classification system that automatically predicts the most suitable job category from resume text using Natural Language Processing (NLP), Machine Learning, and Fairness Analysis.

---

# Project Overview

Recruiters often receive hundreds of resumes for each job opening, making manual screening slow, inconsistent, and prone to bias.

This project automates resume classification by transforming resume text into semantic representations and predicting job categories using Machine Learning models while evaluating fairness across experience levels.

---

# Project Objectives

- Automate CV classification
- Reduce manual screening time
- Improve recruitment efficiency
- Reduce bias in hiring decisions
- Evaluate fairness across experience groups

---

# Dataset

The dataset contains resumes labeled with multiple job categories.
Each record includes:

- Resume text
- Experience information
- Target job category

The dataset is multi-class and contains class imbalance, which was addressed using SMOTE oversampling.

---

# Technologies Used

- Python
- Scikit-learn
- Sentence-BERT (SBERT)
- TF-IDF
- Logistic Regression
- Linear SVM
- Fairlearn
- SMOTE
- Pandas
- NumPy
- Matplotlib
- NLTK

---

# Project Pipeline

# Pipeline A — Resume Classification

- Data Cleaning
- Text Preprocessing
- Sentence-BERT Embeddings
- SMOTE Oversampling
- Logistic Regression
- Performance Evaluation

# Pipeline B — Fairness Analysis

- TF-IDF Representation
- Linear SVM
- Fairlearn
- Demographic Parity
- Equalized Odds
- Group-wise Evaluation

---

# Model Performance

# Resume Classification

- Accuracy ≈ 73%
- Macro F1-score ≈ 0.66
- ROC-AUC ≈ 0.97

# Fairness Evaluation

The project evaluates:

- Demographic Parity Difference
- Demographic Parity Ratio
- Equalized Odds Difference
- Group-wise Precision
- Group-wise Recall
- Group-wise F1-score

---

# Repository Structure

```
├── README.md
├── project_ML_final.ipynb
├── PROJECT_ML_Report.pdf
```

---

# Future Improvements

- Larger and more balanced datasets
- Deep Learning models
- BERT fine-tuning
- Multi-language resume support
- Resume-to-Job matching
- Web deployment

---

# Team

- Noran Abdullah Aljodi
- Rema Saed Althqfi
- Reema Salem Alharbi
- Toleen Fadi Dahlawi
- Ilaf Ahmed Bashawri

---

# Supervisor

Dr. Afaf M. Almehmadi
