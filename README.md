# Google-Play-Reviews-Sentiment-Analysis

## Objective
Analyze player feedback by performing sentiment classification on Google Play Store reviews using text mining and machine learning.

## Dataset
- Source: Google Play Store reviews (scraped for the game _Infinity_ _Nikki_)
- Size: 1,000 reviews
- Fields used: `content`, `score`

## Methods
- Text preprocessing (case folding, stopword removal, stemming)
- Vectorization using TF-IDF and Word2Vec
- Trained multiple machine learning models (Naive Bayes, Logistic Regression, LinearSVC)
- Selected best-performing model for sentiment classification

## Files
- `Google Play Reviews Sentiment Analysis.ipynb`: full text mining and sentiment analysis workflow
- `infinity_nikki_1000_reviews`: review dataset

## Results
- Best model accuracy: ~82% using LinearSVC with TF-IDF
