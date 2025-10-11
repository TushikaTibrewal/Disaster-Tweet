# Disaster-Tweet
Project Overview
This project aims to classify tweets as disaster or non-disaster using machine learning techniques. We perform data cleaning, exploratory analysis, text vectorization (TF-IDF), train multiple classifiers (Logistic Regression, Multinomial Naive Bayes, Support Vector Machine), and evaluate their performance.
Workflow
Data Preprocessing
Remove punctuation, mentions, URLs, hashtags, HTML tags, and stopwords from the tweet text.
Handle missing values and duplicates.

Exploratory Data Analysis
Visualize disaster/non-disaster tweet distribution.
Generate word clouds for each class.
Explore tweet length, most frequent words, and sentiment patterns.

Feature Engineering
Convert text data into numerical form using TF-IDF vectorization (unigram, bigram, trigram options).

Model Training & Comparison
Split data into train and test sets.
Train Logistic Regression, Multinomial Naive Bayes, and Support Vector Machine.
Evaluate each using accuracy, precision, recall, F1-score, and confusion matrix.
Print comparison and detailed classification reports.

Prediction
Each model is used to predict disaster/non-disaster for the test set.
