# Improving Airline Service via Twitter Sentiment

## Introduction

Customer satisfaction and service quality are critical for success in the airline industry. This project aims to improve airline service by analyzing sentiment from Twitter data. Specifically, we classify tweets about airlines as positive, negative or neutral. These predictions allow airlines to better understand customer pain points and dissatisfaction.

## Data 

The tweet dataset contains 30,000 tweets related to major US airlines. It includes text data and sentiment labels (positive, negative, neutral). The data is split 80/20 into training and test sets.

## Methods

We use neural networks and deep learning approaches for text classification. The steps include:

- Data cleaning and preprocessing
- Tokenization and padding sequences  
- Word embeddings with word2vec
- LSTM and CNN models for sentiment classification 
- Parameter tuning and model optimization

Key libraries used are Keras, Tensorflow, Gensim, and scikit-learn. 

## Results  

The LSTM model achieves the best performance, with 88% accuracy on the test set. Precision and recall for negative sentiment are 82% and 76% respectively.

## Impact

These results allow airlines to automatically analyze a large sample of tweets. By identifying negative customer feedback, they can investigate pain points and target service improvements. For example, they may discover delays at certain airports are leading to highly negative sentiment. The airline could allot more time for those routes. 

## How This Project Works

- The first step is collecting a dataset of tweets related to airlines and labeling sentiment. Next, text preprocessing is done - cleaning, tokenizing, padding sequences, etc. 

- After preprocessing, word embeddings are created using word2vec. These vector representations capture semantic meaning.

- The embedded sequences are fed into LSTM and CNN models for classification. The models learn patterns associating certain words/phrases with positive or 
  negative sentiment. 

- Model hyperparameters like layer sizes, dropout, learning rate, etc. are tuned. Evaluation metrics identify the best model.

- Finally, the model is applied to new unlabeled tweets. It predicts if the sentiment is positive, negative or neutral. These predictions give airlines 
  insights into customer satisfaction.

## Conclusion

This project demonstrates how deep learning can automatically analyze airline tweets to improve customer service. The high accuracy for detecting negative sentiment shows this approach's promise. With more data and model optimization, airlines can derive greater benefits from mining social media data.

