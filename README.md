**SENTIMENT ANALYSIS ON RESTAURANT REVIEWS**

**Project Overview**

This project focuses on developing sentiment analysis models to classify restaurant reviews as positive or negative. The models used include Logistic Regression, Naive Bayes, and VADER. The workflow involves text preprocessing, feature extraction, model training, and evaluation.

**Introduction**

Sentiment analysis is a natural language processing (NLP) technique used to determine whether data is positive, negative, or neutral. In this project, we analyze restaurant reviews to classify the sentiments expressed in them.

**Data**

The dataset consists of restaurant reviews labeled as positive or negative. The reviews are provided in a CSV file.

**Preprocessing**

Preprocessing steps include:

**Text Cleaning**: Remove punctuation and numbers.

**Lowercasing**: Convert text to lowercase.

**Tokenization**: Split text into words.

**Stopwords Removal**: Remove common words that do not contribute to sentiment.

**Models**

We use the following machine learning models:

**Logistic Regression**: A simple yet effective model for binary classification tasks.

**Naive Bayes**: A probabilistic classifier based on applying Bayes' theorem with strong independence assumptions between the features.

**VADER (Valence Aware Dictionary and sentiment Reasoner)**: A lexicon and rule-based sentiment analysis tool specifically attuned to sentiments expressed in social media.

**Feature Extraction**
We use TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert text data into numerical features for Logistic Regression and Naive Bayes models. 
VADER operates directly on the text data without the need for vectorization.

**Evaluation**
The model's performance is evaluated using:
Accuracy: The ratio of correctly predicted instances to the total instances.
Confusion Matrix: A summary of prediction results on the classification problem.
Classification Report: Provides precision, recall, and F1-score for each class.

**Results**
Achieved 76% accuracy in classifying the sentiment of restaurant reviews across Logistic Regression, Naive Bayes, and VADER models.
Confusion Matrix and Classification Report: Provided detailed insights into model performance.

