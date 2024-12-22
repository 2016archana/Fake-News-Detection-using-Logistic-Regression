# Fake News Detection using Logistic Regression

This project aims to detect fake news articles using Logistic Regression. The model classifies news articles into two categories: **real** (0) and **fake** (1). It preprocesses the text data using NLP techniques and evaluates the model's performance using precision, recall, F1-score, and accuracy.

## Files Included

- **tfidf_vectorizer.pkl**: Pretrained TF-IDF vectorizer used for text feature extraction.
- **news_model.pkl**: Trained Logistic Regression model for fake news classification.
- **linear_regression.ipynb**: Jupyter Notebook for training and evaluating the model.

**Note:** The dataset used for training was too large to upload, so please use your own dataset of labeled news articles (real or fake). Ensure your dataset has two columns: one for the text and one for the label (0 for real, 1 for fake).

## Results

The trained model achieved the following performance metrics:

| Parameter      | Precision | Recall | F1-Score | Support |
|----------------|-----------|--------|----------|---------|
| 0 (Real News)  | 0.99      | 0.99   | 0.99     | 5922    |
| 1 (Fake News)  | 0.99      | 0.99   | 0.99     | 5298    |
| **Accuracy**   |           |        | 0.99     | 11220   |
| **Macro avg**  | 0.99      | 0.99   | 0.99     | 11220   |
| **Weighted avg** | 0.99    | 0.99   | 0.99     | 11220   |

## Purpose

The goal of this project is to build an effective fake news detection system using machine learning. The model can be used to classify news articles, helping to identify fake news with high accuracy.

