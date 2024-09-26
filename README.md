
## Project: Twitter Sentiment Analysis Using Logistic Regression

# Overview:
Developed a machine learning pipeline to perform sentiment analysis on Twitter data using Logistic Regression. The model was built to classify tweets into positive, negative, or neutral sentiment, providing valuable insights for understanding public opinion on various topics.

# Key Contributions:
Data Collection: Scraped over 1.6 million tweets using the Tweepy API based on specific keywords and hashtags.

Data Preprocessing: Cleaned and preprocessed text data by removing stopwords, URLs, and special characters. Performed tokenization, stemming, and TF-IDF vectorization to convert the text into numerical features for model training.

Sentiment Classification: Built a Logistic Regression classifier to categorize tweets into three classes: positive, negative, and neutral.

Model Evaluation: Achieved an accuracy of 77% on test data.

Deployment: Deployed the model as a web application using Flask, allowing users to input a keyword or hashtag and see sentiment analysis results in real-time.

# Technical Stack:
Data Collection:

Tools: kaggle (for fetching tweets), Pandas (for data manipulation)

Text Preprocessing:

Libraries: NLTK for text cleaning.

Techniques: Removed stopwords, URLs, and punctuations; applied stemming; transformed text using TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction.

Modeling:

Algorithm: Logistic Regression.


# Challenges and Solutions:
Challenge: Handling noisy, unstructured text data in tweets.

Solution: Applied comprehensive text preprocessing, including stopword removal, stemming, and normalization to ensure clean input data for the model.

Challenge: Balancing the dataset and dealing with class imbalance (more neutral tweets).

Solution: Applied oversampling techniques like SMOTE and class weighting to balance positive, negative, and neutral classes.

Results:
Performance: Achieved 81% accuracy with traing data and  0.77 in test data.
