# IMDB Movie Review Sentiment Analysis Using Machine Learning

This project demonstrates how to build a machine learning model to classify IMDB movie reviews as **positive** or **negative** based on the text content of the reviews.

---

## Dataset

- The IMDB Large Movie Review Dataset contains 50,000 reviews split evenly into 25,000 training and 25,000 test samples.
- Reviews are labeled as **positive** or **negative**.
- Source: [IMDB Dataset by Stanford AI](https://ai.stanford.edu/~amaas/data/sentiment/)

---

## Features & Approach

- Text preprocessing using **TF-IDF Vectorization** to convert reviews into numerical features.
- Classification using machine learning algorithms such as:
  - Support Vector Machine (SVM)
  - Logistic Regression (optional)
- Train/test split to evaluate model performance.
- Ability to predict sentiment on new user-input reviews.

---

## Requirements

- Python 3.x
- pandas
- scikit-learn

Install dependencies via pip:
```bash
pip install pandas scikit-learn
