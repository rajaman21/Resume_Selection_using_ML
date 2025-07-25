# 📄 Resume Selection using Machine Learning

This project automates resume screening by classifying resumes into two categories: **"flagged"** and **"not_flagged"** using machine learning and natural language processing (NLP) techniques. It's a powerful tool for recruiters and HR teams to efficiently filter candidates based on the textual content of their resumes.

---

## 🚀 Project Overview

Manual resume screening is time-consuming and inefficient, especially when dealing with a large applicant pool. This project leverages machine learning models to analyze and classify resumes, significantly reducing manual effort and enabling smart filtering based on predefined patterns or keywords.

---

## 🧠 Key Features

- **🧹 Data Preprocessing**: 
  - Clean and normalize resume text (lowercase, remove punctuation, stopwords, special characters)
  - Tokenization and lemmatization using `nltk` and `gensim`

- **📊 Exploratory Data Analysis (EDA)**:
  - Understand the distribution of flagged vs. not_flagged resumes
  - Visualize word frequency and resume lengths

- **🔎 Machine Learning Pipeline** *(structure available)*:
  - Ready for model implementation (Logistic Regression, Random Forest, Neural Networks, etc.)

---

## 🧰 Tech Stack / Libraries Used

- `pandas` – Data manipulation  
- `numpy` – Numerical operations  
- `matplotlib`, `seaborn` – Data visualization  
- `nltk`, `gensim` – NLP preprocessing  
- `scikit-learn` – ML models and evaluation tools  

---

## 📁 Dataset

- **Total Records**: 125 resumes  
- **Format**: CSV  
- **Columns**:
  - `resume_id`: Unique identifier
  - `class`: Label – `flagged` or `not_flagged`
  - `resume_text`: The resume content (raw text)

---
