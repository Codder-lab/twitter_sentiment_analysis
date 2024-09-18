# Twitter Sentiment Analysis

This repository contains a Jupyter Notebook that performs sentiment analysis on Twitter data. The dataset is sourced from Sentiment140 on Kaggle. The project focuses on classifying tweets as either positive or negative using machine learning.

## Project Overview

The notebook walk through the following steps:

1. **Data Acquisition:** Downloading the Twitter sentiment dataset from Kaggle.
2. **Data Processing:** Cleaning and preprocessing the tweet data.
3. **Feature Engineering:** Converting text data into numerical features using TF-IDF Vectorizer.
4. **Model Training:** Using logistic regression to classify the sentiments.
5. **Evaluation:** Assessing the model performance with accuracy.

## Installation

To get started, you need to have the following dependencies installed:

```bash
  pip install -r requirements.txt
```

**Required Libraries:**

- kaggle
- numpy
- pandas
- nltk
- scikit-learn

## Data Acquisition

First, you need to download the dataset from Kaggle. Ensure that you have your Kaggle API token (the kaggle.json file) in the root of your project directory.

The notebook automates the dataset download using the Kaggle API.

## Data Preprocessing

The notebook processes the raw text data by:

- Removing special characters and stopwords.
- Tokenizing and stemming the words.
- Converting the tweet text to lowercase.

## Model Training

A logistic regression model is used to classify the sentiments of the tweets.

## Results

The logistic regression model achieved an accuracy of 77.6% on the test dataset.

## How to Run the Notebook

1. Clone the repository

```bash
  git clone https://github.com/Codder-lab/twitter_sentiment_analysis.git
```

2. Install the dependencies

```bash
  pip install -r requirements.txt
```

3. Run the notebook

Open the notebook in Jupyter or VSCode and run the cells to reproduce the analysis.
