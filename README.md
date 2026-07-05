# 🤖 AI Resume Screening Using NLP

An AI-powered Resume Screening System that automatically classifies resumes into different job categories using Natural Language Processing (NLP) and Machine Learning.

This project demonstrates how AI can assist recruiters by reducing manual resume screening and improving candidate classification.

---

## 📌 Project Overview

Recruiters often receive thousands of resumes for different job roles. Manually sorting these resumes is time-consuming.

This project uses NLP techniques and Machine Learning models to automatically classify resumes into their respective job categories.

---

## 🚀 Features

- Resume Dataset Analysis
- Data Cleaning & Text Preprocessing
- TF-IDF Feature Extraction
- Resume Category Classification
- Model Comparison
- Resume Category Prediction
- Confusion Matrix
- Classification Report
- Accuracy Comparison Visualization
- Model Saving using Joblib

---

## 📂 Dataset

- Total Resumes: **2484**
- Job Categories: **24**

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- NLP
- TF-IDF Vectorizer
- Joblib

---

## 🤖 Machine Learning Models

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 65.79% |
| Random Forest | 70.82% |
| Linear SVM | **71.62% ✅** |

**Best Performing Model:** Linear SVM

---

## 📊 Project Workflow

Dataset → Data Cleaning → NLP Preprocessing → TF-IDF Vectorization → Train-Test Split → Model Training → Model Evaluation → Resume Prediction → Model Saving

---

## 📈 Visualizations

- Resume Category Distribution
- Model Accuracy Comparison
- Confusion Matrix

---

## 📁 Project Structure

```
AI-Resume-Screening-Using-NLP/
│
├── AI_Resume_Screening.ipynb
├── Resume.csv
├── resume_classifier.pkl
├── tfidf_vectorizer.pkl
├── README.md
└── requirements.txt
```

---

## 🎯 Sample Prediction

Input Resume Skills:

```
Python
Machine Learning
Data Science
SQL
Pandas
TensorFlow
NLP
Power BI
```

Output:

```
Predicted Category:
Data Science
```

---

## 📌 Future Improvements

- Resume PDF Upload
- Skill Extraction
- Job Description Matching
- Resume Ranking
- Streamlit Web Application
- Deep Learning Models
- BERT-based Resume Classification

---

## 📚 Learning Outcomes

- Natural Language Processing
- Text Vectorization using TF-IDF
- Machine Learning Classification
- Model Evaluation
- Data Visualization
- AI-based Resume Screening

---

## ⭐ If you found this project useful, don't forget to Star this repository!
