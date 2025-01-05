# Practice of Basic NLP methods:

# Exploratory Data Analysis (EDA)

This project involves performing Exploratory Data Analysis (EDA) on a given dataset to uncover patterns, trends, and insights. The analysis includes data cleaning, visualization, and statistical exploration using Python libraries.

## Objective

The goal is to:
- Understand the dataset's structure and content.
- Identify missing or duplicate data.
- Perform basic statistical analysis.
- Visualize relationships and distributions of data variables.

## Features

### 1. Data Import and Overview
- Load the dataset using `pandas`.
- Inspect the dataset for column names, data types, and missing values.

### 2. Data Cleaning
- Handle missing values through imputation or removal.
- Remove duplicates to ensure data integrity.

### 3. Exploratory Analysis
- Summary statistics for numerical and categorical columns.
- Visualizations using:
  - **Matplotlib** and **Seaborn** for histograms, boxplots, and pairplots.
  - **WordCloud** for text data insights.

### 4. Advanced Visualization
- Correlation heatmaps to identify relationships between variables.
- Distribution and trend analysis for continuous variables.


# Text Classifier

This repository contains a Jupyter Notebook for building a text classification system. The project leverages libraries such as `scikit-learn` and `vaderSentiment` to process, analyze, and classify text data.

## Features

- **TF-IDF Vectorization**: Converts text data into numerical features for machine learning.
- **Sentiment Analysis**: Utilizes the `vaderSentiment` library for sentiment analysis.
- **Sample Data**: Includes basic examples for demonstration purposes.

# Sentiment Analysis on Drug Review Dataset
This repository contains a project focused on sentiment analysis of drug reviews using GloVe embeddings and LSTM implemented with PyTorch.

## Dataset
The dataset used is the Drug Reviews (Druglib.com), which can be found here.

## Overview
The project uses the following key components:
- GloVe Embedding for text representation.
- LSTM (Long Short-Term Memory) for sentiment classification.
- PyTorch as the framework for building and training the model.
  
## Key Steps

- Data Loading and Preprocessing: The drug review dataset is loaded and prepared for analysis.
- Exploratory Data Analysis (EDA): Analyze the data distribution and visualize patterns using tools like word clouds.
- Model Building and Training: Use GloVe embeddings with LSTM to predict sentiment.

# Fine-Tuning and Evaluating RoBERTa for Yelp Review Classification
This repository contains a project focused on fine-tuning a pre-trained RoBERTa model for sentiment analysis of Yelp reviews.

## Objective
The goal is to fine-tune a RoBERTa model on the Yelp review dataset, evaluate its performance, and visualize the results. The project covers:

## Data preprocessing.
Model training and evaluation.
Visualizations such as a confusion matrix.

## Dataset
The dataset used is the Yelp Review Dataset, which is loaded using the datasets library. Reviews are converted into binary sentiment labels:
- Negative: Ratings 1, 2, 3.
- Positive: Ratings 4, 5.

## Key Steps
### Dataset Loading:

### Load the Yelp review dataset using the datasets library.
Shuffle and select a subset of the dataset for experimentation.

### Data Splitting:
Create training, validation, and test sets.

### Fine-Tuning RoBERTa:
Use a pre-trained RoBERTa model.
Fine-tune on the Yelp dataset for binary sentiment classification.

### Evaluation and Visualization:
Evaluate the model's performance on the test set.
Visualize results using tools like a confusion matrix.
