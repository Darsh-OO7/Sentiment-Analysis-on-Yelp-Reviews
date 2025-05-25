# Sentiment Analysis on Yelp Reviews

## Overview
This project aims to perform sentiment analysis on Yelp reviews using a variety of machine learning (ML) and deep learning (DL) models. The objective is to predict the sentiment (positive or negative) of Yelp reviews based on their textual content. This repository contains the implementation of different ML and DL models, the datasets used, and the results obtained from the experiments.

## Features
### Machine Learning Models
- Logistic Regression
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Trees (DT)
- Support Vector Machine (SVM)
- Random Forest (RF)

### Deep Learning Models
- Bidirectional Encoder Representations from Transformers (BERT)
- Recurrent Neural Networks (RNN)
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
- Bidirectional LSTM with Attention Mechanism

### Feature Sets
- Bag of Words
- TF-IDF (Term Frequency-Inverse Document Frequency)
- Word2Vec
- N-grams
- Graph Embedding

## Data
The dataset consists of Yelp reviews related to pizza businesses. Each review is labeled with a sentiment indicator, either positive or negative. The data includes the textual content of the reviews and their corresponding sentiment labels.

## Models and Techniques
### ML Models
Trained and evaluated several ML models, including Logistic Regression, Naive Bayes, KNN, DT, SVM, and RF, using different feature sets.

### DL Models
Utilized DL techniques, including BERT with and without fine-tuning, BERT with LORA (Low-Rank Adaptation), RNN, LSTM, GRU, and Bidirectional LSTM with Attention Mechanism. These models were trained to understand the sequence and context of the text in the reviews.

## Results
The performance of each model was evaluated using common metrics such as accuracy, precision, recall, and F1-score. Confusion matrices and classification reports were generated to provide detailed insights into model performance.

## Future Work
- Experiment with additional DL architectures and pre-trained models to improve performance.
- Explore ensemble learning techniques to increase robustness and accuracy.
- Conduct hyperparameter tuning to optimize model configurations.

## Contributors
- Aayush Sangani
- Darsh Shetty
- Pavan Antala
- Sheroz Shaikh
