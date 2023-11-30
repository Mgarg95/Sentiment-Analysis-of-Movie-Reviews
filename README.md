# Sentiment Analysis of Movies
This project performs a sentiment analysis on Movie ratings from the IMDB website. The data contains 25k highly-polar (good or bad) movie reviews for training and testing. The objective is to predict whether a given movie review has an overall positive or negative sentiment.

The codes are generated using ML libraries *keras* and *Tensorflow*.
The above code generates a *sequence-to-sequence autoencoder* from the vectorized review of maximum length 'max_review_length' containing only the top 'top_words' most frequent words. The embedding generated is then used to classify the review as good or bad using a simple Deep Learning model to train a Neural Network.
The code hasn't been optimized so it has only 55% accuracy but it can be used to develop better classifier and increasing the epochs.
