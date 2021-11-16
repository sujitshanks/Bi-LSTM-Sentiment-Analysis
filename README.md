# Bi-LSTM-Sentiment-Analysis

This is a large data set of news items and their respective social feedback on multiple platforms: Facebook, Google+ and LinkedIn.
The collected data relates to a period of 8 months, between November 2015 and July 2016, accounting for about 100,000 news items on four different topics: economy, microsoft, obama and palestine.
Title (string): Title of the news item according to the official media sources
Headline (string): Headline of the news item according to the official media sources
SentimentTitle: Sentiment score of the title, Higher the score, better is the impact or +ve sentiment and vice-versa. (Target Variable 1)
SentimentHeadline: Sentiment score of the text in the news items' headline. Higher the score, better is the impact or +ve sentiment. (Target Variable 2)

Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs.



Improvements:
Other word embeddings: word2vec or fastvec.
Transformer pipeline multi-output regressor.
Additional features: tf-idf values, word importance metrics
Should have plotted error over epoch to identify convergence or plateauing.
Hyperparameter optimization: adam takes care of gradient issues, activation function?, number of layers, play with dropout.
Train own corpus with respect to the four topics? Possible but cumbersome.

Glove embeddings:
# 1. GloVe Dataset: https://www.kaggle.com/watts2/glove6b50dtxt
# 2. Alternate bigger corpora: https://nlp.stanford.edu/data/wordvecs/glove.42B.300d.zip

