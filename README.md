# Fake_news_prediction

## Overview

This project aims to build a machine learning model that predicts whether a news article is real or fake using Python and various natural language processing techniques. The model utilizes logistic regression for classification based on features extracted from the article's title, author, and content.

## Dataset

The dataset used for this project contains news articles labeled as either real (0) or fake (1). It can be found at the following link:
- [Fake News Dataset](https://www.kaggle.com/c/fake-news/data)

 Steps Involved

## Data Preprocessing

Load the dataset into a pandas DataFrame.
Handle missing values by replacing them with empty strings.
Merge the author and title columns to create a new content column.
Clean the text data by removing non-alphabetic characters and applying stemming.

## Feature Extraction

Convert the cleaned textual data into numerical format using TF-IDF Vectorization.

## Model Training

Split the dataset into training and test sets (80/20).
Train a Logistic Regression model on the training data.

## Evaluation

Evaluate the model's performance using accuracy scores and a classification report, which includes precision, recall, and F1-score.

## Conclusion
This project showcases the application of machine learning in identifying fake news articles, contributing to the fight against misinformation in the digital age.

Feel free to fork the repository, contribute, or reach out for collaboration!

## Libraries Required

- `numpy`
- `pandas`
- `re`
- `nltk`
- `sklearn`

  


## Model Results Snapshot

![fake news prediction](https://github.com/user-attachments/assets/8df2bbc4-0787-46b0-befd-3ad1953e57df)



You can install the necessary libraries using pip:

```bash
pip install numpy pandas nltk scikit-learn

