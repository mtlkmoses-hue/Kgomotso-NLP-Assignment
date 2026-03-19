# Kgomotso-NLP-Sentiment140
Natural Language Processing (NLP) is a critical field within artificial intelligence that focuses on enabling computers to understand, interpret, and analyze human language. These data provide valuable insights into user opinions, making them ideal for sentiment analysis tasks (Sentiment140 dataset), available on Kaggle, is a widely used.This project implements an end-to-end Machine Learning pipeline to classify the sentiment of social media posts. Using a 50,000-sample subset of the Sentiment140 dataset, we built a model capable of distinguishing between positive and negative emotions in short-form text.

Dataset can be downloaded here: https://www.kaggle.com/datasets/kazanova/sentiment140

# Technical Stack
Language: Python 3.x
Libraries: * Pandas & NumPy (Data Manipulation)
NLTK & Regex (Text Preprocessing)
Scikit-Learn (TF-IDF Vectorization & Logistic Regression)
Matplotlib & Seaborn (Data Visualization)

# The Pipeline
The project follows a standard Data Science lifecycle:
Data Sampling: Loading and balancing the dataset.
Text Cleaning: * Lowercasing and punctuation removal.
Stripping URLs, @mentions, and hashtags using Regex.
Removing English stop words via NLTK.
Feature Extraction: Converting cleaned text into numerical vectors using TF-IDF Vectorization (5,000 features).
Model Training: Training a Logistic Regression classifier on an 80/20 train-test split.
Evaluation: Measuring performance using Accuracy, Precision, Recall, and a Confusion Matrix.

# Key Results
Overall Accuracy: 75.49%]
Insights: The model successfully identified high-impact sentiment markers, de-prioritizing generic "noise" words to focus on emotionally charged vocabulary.

# How to Run
Install dependencies: Bash
pip install pandas nltk scikit-learn matplotlib seaborn

# Execute the Notebook:
Open Sentiment_Analysis_Code.ipynb in Jupyter Notebook or Google Colab and run all cells sequentially.

Test New Reviews:
Use the predict_sentiment function at the end of the notebook to test the model on custom sentences.
