# 🎥 YouTube Comment Analysis — Sentiment, Emotion & Hate Speech Detection

---

## 🧠 Overview
This project analyzes **YouTube comments** related to civic and protest-related discussions in Kenya using **Natural Language Processing (NLP)** techniques. The goal is to extract insights about **public sentiment**, **emotional tone**, and **hate speech prevalence** from large volumes of user-generated content.

The project contributes to understanding **digital civic discourse** and aligns with **UN SDG 16 (Peace, Justice, and Strong Institutions)** by promoting responsible online expression and civic engagement.

---

## 📊 Features
- **Text Preprocessing**: Tokenization, lowercasing, stopword removal, lemmatization.  
- **Sentiment Analysis**: Using Transformer-based pipelines (Hugging Face).  
- **Emotion Detection**: Classifies comments into emotional categories (e.g., joy, anger, sadness).  
- **Hate Speech Detection**: Identifies harmful or toxic content in civic conversations.  
- **Visualization**: Word clouds, sentiment distributions, and comparative analysis before and after text cleaning.

---

## 🧩 Methods
- **Models Used**:
  - `transformers` sentiment and emotion classification pipelines
  - Fine-tuned hate speech detection model
- **Data Processing**:
  - Cleaned dataset of civic-related YouTube comments
  - Comparative results of pre-cleaning vs. post-cleaning sentiment
- **Libraries**:
  - `transformers`, `pandas`, `numpy`, `matplotlib`, `wordcloud`, `tqdm`



