# **Sentiment Analysis of Sololearn Reviews**
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

## Visualizations
- Sentiment distribution (bar plot) – shows how many reviews fall into each sentiment category
- Review length per sentiment (boxplot) – illustrates the variation in review lengths across sentiment classes
- Wordclouds per sentiment – highlights the most frequent words in each sentiment category

---
