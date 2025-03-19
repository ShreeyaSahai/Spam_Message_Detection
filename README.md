# Spam Message Detection
This project detects spam messages using Machine Learning (Naive Bayes model)

Utilizing the dataset: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset?resource=download

The dataset consists of two columns: Label (ham or spam) and Message

The dataset was then preprocessed by converting all text to lowercase, removal of special characters, removal of stopwords and lemmatization (converting words to root form) using NLTK.

The data is split into training and testing sets, and the model has reported 98% accuracy in spam detection.
