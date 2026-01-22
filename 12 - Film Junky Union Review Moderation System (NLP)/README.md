# 🎬 Film Junky Union Review Moderation System (NLP)

## 📌 Overview
This project builds a natural language processing (NLP) system to automatically classify movie reviews as positive or negative. The goal is to help the Film Junky Union community filter and moderate negative reviews using machine learning models trained on IMDB review data.

The model was required to achieve an F1-score of at least **0.85**, ensuring reliable sentiment classification for real-world moderation use.

---

## ✨ Features
- Text preprocessing and cleaning (tokenization, lemmatization, stopword removal)
- Exploratory data analysis (EDA) on review sentiment distribution
- Feature engineering using Bag-of-Words and TF-IDF
- Machine learning model training (Logistic Regression, Gradient Boosting, etc.)
- Optional BERT embeddings for advanced text representation
- Model evaluation using F1-score, accuracy, and confusion matrix
- Custom review testing to compare model predictions

---

## 🛠 Tech Stack
- Python 3.10+
- Pandas, NumPy
- Scikit-learn
- NLTK / spaCy
- TensorFlow / Transformers (for BERT embeddings)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📊 Key Results
- Achieved F1-score ≥ 0.85 on the test dataset
- Logistic Regression and Gradient Boosting performed strongly on TF-IDF features
- BERT embeddings improved semantic understanding but required higher computational resources
- The system successfully classified custom-written reviews
