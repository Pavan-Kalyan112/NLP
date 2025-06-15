# 🧠 NLP Practice Projects with NLTK

Welcome to my **NLP (Natural Language Processing) Practice Repository**!  
This repository contains foundational NLP projects implemented using Python and the NLTK library. It’s a hands-on learning space focusing on text preprocessing and building a simple spam detection model using classical NLP techniques.

---

## 📂 Projects Included

### 1. 🔤 Text Preprocessing with NLTK

This notebook demonstrates the most common and essential preprocessing steps applied to raw text:

- Lowercasing
- Tokenization
- Stopword Removal
- Stemming (Porter Stemmer)
- Lemmatization (WordNet Lemmatizer)
- Text Normalization

📎 **Libraries Used:**  
`nltk`, `re`, `string`, `pandas`

---

### 2. ✉️ Spam or Ham Classifier (SMS Spam Detection)

A classic machine learning classification task on SMS text data. This project uses **TF-IDF Vectorization** and **Logistic Regression** to predict whether an incoming message is spam or not.

#### ✅ Workflow:
- Load and clean the SMS dataset
- Preprocess text using NLTK
- Convert text to numerical features using `TfidfVectorizer`
- Train a classifier (Logistic Regression)
- Evaluate accuracy, precision, recall
- (Optional) Streamlit app for real-time prediction

📎 **Libraries Used:**  
`nltk`, `sklearn`, `pandas`, `streamlit`

🗂 **Dataset Source:**  
[SMS Spam Collection Dataset (UCI Repository)](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---
