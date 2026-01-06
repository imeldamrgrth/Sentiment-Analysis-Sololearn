# **Sentiment Analysis of Sololearn Reviews**

## Overview
This project is a practical application of sentiment analysis using natural language processing (NLP) and machine learning techniques.
It demonstrates the end-to-end workflow of analyzing textual data:
- Data cleaning and preprocessing
- Sentiment labeling with both lexicon-based and ML methods
- Feature extraction (TF-IDF, Word2Vec)
- Model training, evaluation, and comparison
- Visualization and insights extraction

The goal is to extract actionable insights from user reviews, understand user satisfaction, and identify common pain points in the application.

---

## Dataset
- Source: sololearn_raw.csv
- Size: ~20,000 reviews
- Columns:
  - content: User review text
  - score: Original rating score
  - sentiment: Label assigned (positive, neutral, negative)
- Distribution:
  - Positive: 12,400 reviews (majority)
  - Neutral: 7,200 reviews
  - Negative: 400 reviews (minority)
 
---

## Workflow
The project follows an end-to-end sentiment analysis workflow:
Data Collection – Raw user reviews are collected in sololearn_raw.csv.
Data Cleaning & Preprocessing – Text is cleaned by removing noise, normalizing words, and preparing for analysis.
Sentiment Labeling – Reviews are labeled as positive, neutral, or negative using:
Lexicon-based approach (custom positive/negative/neutral word lists)
VADER sentiment scoring (pre-built NLP lexicon)
Combination of both for more robust labeling
Feature Extraction – Text is transformed into numerical features using:
TF-IDF (Term Frequency–Inverse Document Frequency)
Word2Vec embeddings (vector representation of words capturing context)
Model Training & Evaluation – Models are trained to classify sentiment:
Logistic Regression
Random Forest
Models are evaluated and compared for performance (accuracy, classification metrics)
Visualization & Insights – Data and sentiment patterns are visualized using:
Bar plots (sentiment distribution)
Boxplots (review length per sentiment)
Wordclouds (most frequent words per sentiment)

---
