# CDS6344-SOCIAL-MEDIA-COMPUTING-Assignment

# Restaurant Review Sentiment Analysis and Ranking

## 1. Project Overview

This project analyses restaurant reviews collected from Google Reviews and Tripadvisor using Natural Language Processing (NLP) techniques.

The main objective is to analyse customer opinions beyond traditional star ratings by applying different sentiment analysis approaches and aspect-level opinion mining. The project also compares the performance of different sentiment analysis methods and uses the results to support a restaurant ranking system.

The project focuses on:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Sentiment analysis
- Aspect-Based Sentiment Analysis (ABSA)
- Opinion mining
- Restaurant ranking
- Comparison between Google Reviews and Tripadvisor

---

## 2. Project Objectives

The objectives of this project are to:

1. Collect and preprocess restaurant reviews from Google Reviews and Tripadvisor.
2. Explore review patterns, ratings, and frequently discussed topics.
3. Apply different sentiment analysis approaches to classify customer reviews.
4. Compare sentiment analysis results across different methods and platforms.
5. Identify important restaurant aspects such as food, service, price, and ambience.
6. Analyse customer opinions towards different restaurant aspects.
7. Develop a restaurant ranking approach based on customer sentiment and aspect-level opinions.

---

## 3. Data Sources

The project uses restaurant reviews collected from:

- Google Reviews
- Tripadvisor

The datasets contain restaurant review information such as:

- Restaurant name
- Review text
- Rating
- Location
- Platform

The original datasets are separated by platform and location before being combined into platform-level datasets.

## 4. Required Packages

pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud emoji contractions spacy transformers torch accelerate sentencepiece vaderSentiment scipy joblib jupyter

## 5. Required NLTK Resources

After installing NLTK, download the required resources:

nltk.download("punkt")
nltk.download("punkt_tab")
nltk.download("stopwords")
nltk.download("wordnet")
nltk.download("omw-1.4")
nltk.download("averaged_perceptron_tagger")
nltk.download("averaged_perceptron_tagger_eng")