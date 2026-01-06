# **Sentiment Analysis of Sololearn Reviews**

## Overview
This project demonstrates a complete sentiment analysis workflow using natural language processing (NLP) and machine learning techniques. It focuses on analyzing user reviews of the Sololearn application and categorizing them into positive, neutral, and negative sentiments.
The workflow covers:
1. Data preprocessing and cleaning
2. Sentiment labeling using lexicon-based and VADER methods
3. Feature extraction (TF-IDF, Word2Vec embeddings)
4. Model training and evaluation using Logistic Regression and Random Forest
5. Visualization and insights extraction

This project showcasing an end-to-end NLP/ML pipeline, from raw textual data to actionable insights about user feedback.

---

## Dataset
The dataset contains user reviews of the Sololearn app, including text content and ratings. Key features include:

| Feature     | Description                                  |
| ----------- | -------------------------------------------- |
| `content`   | Text of the user review                      |
| `score`     | Original rating score provided by the user   |
| `sentiment` | Label assigned (positive, neutral, negative) |

**Dataset size**: ~20,000 reviews

**Sentiment distribution**: Positive (12,400), Neutral (7,200), Negative (400)

**Data source**: sololearn_raw.csv

---

## Technologies Used
- Python 3.12
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - nltk
  - gensim
  - wordcloud
  - vaderSentiment

---
