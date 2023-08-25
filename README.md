# Sentiment_Analysis_Logistic_Regression
Understand emotions behind a sentence via supervised ML

# Sentiment Analysis Project

This project focuses on sentiment analysis, a natural language processing task that involves determining the sentiment or emotional tone of a given text. The goal is to classify text data into positive or negative sentiment categories.

This project can be easily adapted to various significant applications of Sentiment Analysis, such as categorising discriminatory/offensive social media posts or tweets, favorable/unfavorable product reviews, or even detecting spam emails.

## Overview

Sentiment analysis is performed using two approaches in this project:

1. **Logistic Regression "by Hand"**: In this approach, logistic regression is implemented manually without relying on external libraries. The core logistic regression algorithm is coded from scratch using Python and NumPy.

2. **Logistic Regression with Scikit-Learn**: This approach utilizes the popular machine learning library, Scikit-Learn, to perform sentiment analysis using logistic regression. Scikit-Learn provides efficient implementations of various machine learning algorithms, including logistic regression.

Both the manual and Scikit-Learn implementations yield similar results for sentiment analysis. While the manual implementation offers a deeper understanding of the algorithm's inner workings, the Scikit-Learn implementation provides a more efficient and convenient way to leverage logistic regression for sentiment analysis.

## Dataset

The sentiment analysis is conducted on a dataset containing movie reviews, where each review is labeled with its corresponding sentiment: positive or negative. The dataset, sourced from [Piero Savastano](https://github.com/pieroit) free ML course - [view raw dataset](https://raw.githubusercontent.com/pieroit/corso_ml_python_youtube_pollo/master/movie_review.csv), is preprocessed to remove noise and ensure clean data.
