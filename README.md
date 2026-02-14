# 📰 BBC News Classification — NLP Machine Learning Project


## Project Overview

This project builds a supervised machine learning pipeline to classify BBC news articles into predefined categories based solely on article text.

The objective is to demonstrate practical, production-style NLP workflow including:

- Text preprocessing and normalization
- Feature engineering using TF-IDF
- Model training and evaluation
- Comparative model analysis
- Reproducible experimentation in Jupyter

This project showcases applied machine learning skills relevant to AI/ML engineering roles.

---

## Problem Statement

Automatically categorizing news content enables:

- Content recommendation systems
- News aggregation platforms
- Automated tagging pipelines
- Scalable text analytics

The model classifies articles into one of the following categories:

- Business
- Entertainment
- Politics
- Sport
- Tech

---

## Dataset

- Source: BBC News Dataset (Kaggle)
- Total Articles: 2,225
- Number of Classes: 5
- Balanced multi-class classification problem

Each article consists of raw text and a corresponding label.

---

## Classification

### Text Preprocessing

- Lowercasing
- Stopword removal
- Tokenization
- Cleaning punctuation and noise

### 2️⃣ Feature Engineering

- Bag-of-Words (CountVectorizer)
- TF-IDF Vectorization

### 3️⃣ Model Training

Models evaluated:

- Multinomial Naïve Bayes
- Support Vector Machine (SVM)
- Random Forest Classifier

### 4️⃣ Evaluation Metrics

- Accuracy
- Precision / Recall / F1-score
- Confusion Matrix
- Model comparison analysis

---

## 📊 Results

TF-IDF combined with linear classifiers (e.g., SVM) demonstrated strong performance for high-dimensional sparse text data.

Key insights:

- Linear models perform well on structured text features
- TF-IDF improves discrimination of informative terms
- Balanced dataset supports stable multi-class evaluation


---

## Tech Stack

- Python
- scikit-learn
- pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

