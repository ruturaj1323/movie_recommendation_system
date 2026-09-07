# Amazon Customer Review Sentiment Analysis

A machine learning project that classifies Amazon customer reviews as **positive or negative** using Natural Language Processing and Logistic Regression.

## Overview

Customer reviews contain useful information about how people feel about a product. This project uses NLP techniques to convert review text into numerical features and trains a machine learning model to predict the sentiment of unseen reviews.

## Workflow

```text
Amazon Reviews
      ↓
Data Cleaning
      ↓
Text Preprocessing
      ↓
TF-IDF Vectorization
      ↓
Train/Test Split
      ↓
Logistic Regression
      ↓
Sentiment Prediction
      ↓
Model Evaluation
```

## Features

* Cleans and preprocesses review text
* Converts text into numerical features using TF-IDF
* Uses unigram and bigram features
* Trains a Logistic Regression classifier
* Predicts positive and negative sentiment
* Evaluates the model using standard classification metrics

## Model

### TF-IDF

TF-IDF (Term Frequency-Inverse Document Frequency) is used to represent review text numerically.

The project uses:

* Unigrams
* Bigrams

This allows the model to consider both individual words and short word combinations.

### Logistic Regression

Logistic Regression is used as the classification model because it works well with high-dimensional sparse text features.

## Results

The model achieved:

**93.25% Accuracy**

The model was also evaluated using:

* Precision
* Recall
* F1-score

## Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **TF-IDF**
* **Logistic Regression**
* **Jupyter Notebook / Google Colab**

## What I Learned

* Text preprocessing for machine learning
* TF-IDF feature extraction
* Working with sparse text representations
* Training classification models
* Evaluating NLP models using multiple metrics
* Understanding the effect of n-grams on text classification
