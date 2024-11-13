# Identifying Stress from Mental Health Conditions in Subreddit Posts Using NLP and Machine Learning

## Why We Did This
Mental health diagnoses often rely on subjective observation, varying across different providers and environments. This study explores whether Natural Language Processing (NLP) and Machine Learning (ML) techniques can provide a more objective approach to identifying stress indicators in mental health contexts by analyzing subreddit posts.

## How We Did This
Using a dataset of subreddit posts labeled as "stressed" or "not stressed," we applied three NLP word embedding techniques—ELMo, BERT, and Bag of Words (BoW)—combined with machine learning models (Logistic Regression, SVM, XGBoost) to classify the text. The pipeline included preprocessing, word embedding, model training, hyperparameter tuning, and evaluation with accuracy, recall, precision, and F1-score metrics.

## What We Found
The BERT embeddings, paired with Logistic Regression and SVM, demonstrated the highest accuracy and precision in identifying stress indicators. This suggests that transformer-based embeddings, especially when combined with linear models, enhance classification performance in mental health applications.

[Link to the final report report](./)
