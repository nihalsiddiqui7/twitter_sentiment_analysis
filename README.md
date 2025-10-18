# Twitter Sentiment Analysis

A machine learning project that performs **sentiment analysis** on Twitter data using NLP. This project analyzes tweets to classify them as **positive** or **negative**, demonstrating preprocessing, modeling, and visualization techniques for natural language processing (NLP).

---

## 🔹 Project Overview

- **Dataset:** 1.6M tweets (subset of 80k tweets used for faster training)
- **Problem:** Binary sentiment classification (Positive / Negative)
- **Goal:** Build a model that can predict sentiment from tweet text with good accuracy.
- **Techniques Used:**  
  - Text cleaning and preprocessing  
  - Tokenization and sequence padding  
  - Evaluation using accuracy, confusion matrix, and classification report  
  - Word clouds for visual analysis of positive vs negative words  

---

## 🔹 Key Features

- **Data preprocessing:** Handles noisy Twitter data including emojis, URLs, mentions, and special characters.
- **Evaluation:** Confusion matrix and classification report to understand model performance.
- **Visualizations:** Word clouds for positive and negative tweets to show common words.

---

## 🔹 Technologies & Libraries

- Python 3  
- Pandas, NumPy  
- Scikit-learn   
- Matplotlib  
- WordCloud  

---

## 🔹 Model Performance

| Model                         | Accuracy |
|--------------------------------|---------|
| TF-IDF + Logistic Regression   | 76%     |


> Future work: Implement **DistilBERT or other Transformer models** to improve accuracy to ~85–88%.

