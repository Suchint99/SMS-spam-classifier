This project is a Spam SMS Classification System built using Natural Language Processing (NLP) and Machine Learning. It takes raw SMS text messages, processes them with advanced text-cleaning techniques, and classifies each message as either Spam (unwanted/advertising) or Ham (legitimate).
The project uses datasets in both .txt (sms.txt) and .xlsx (Example_NLP.xlsx) formats. The core implementation is in the Jupyter Notebook (spam_dataset_nagendra.ipynb), where different ML models are trained, tested, and compared.

What It Does
Loads SMS Dataset (spam/ham labeled).
Preprocesses Text → cleaning, tokenization, stopword removal, lemmatization.
Feature Extraction → converts SMS text into numerical vectors using TF-IDF.
Model Training → applies algorithms like Naive Bayes, Logistic Regression, Random Forest, etc.
Evaluation → generates accuracy, precision, recall, F1-score, and confusion matrix.
Prediction → classifies new/unseen SMS as Spam or Ham.

Key Features
Handles datasets from .txt and .xlsx.
Implements text preprocessing pipeline for clean inputs.
Uses multiple ML models for training and comparison.
Provides clear evaluation metrics and visualizations.
Can be extended into a real-world SMS spam filter.
