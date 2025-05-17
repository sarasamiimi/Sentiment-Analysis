# Sentiment Analysis on Airline Tweets

This project performs sentiment analysis on tweets related to airlines.  
Using a logistic regression model and TF-IDF features, the goal is to classify tweets as **positive**, **neutral**, or **negative**.

##  Dataset

The dataset used is [`Tweets.csv`](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment) from CrowdFlower, which contains over 14,000 tweets about major U.S. airlines.

## What the model does

- Preprocesses tweet text
- Converts text to TF-IDF vectors
- Trains a Logistic Regression classifier
- Evaluates performance using a classification report and confusion matrix
- Displays sentiment predictions on real tweet samples
