# IMDB Movie Review Sentiment Analysis Using LSTM in TensorFlow

# Project Overview:
This project focuses on performing sentiment analysis on a large dataset of IMDB movie reviews. Using natural language processing (NLP) techniques and a Long Short-Term Memory (LSTM) neural network, the goal is to classify reviews as either positive or negative. The project involves data preprocessing, model building, and evaluation.

# Key Steps:

**Data Preprocessing:**

Loading and extracting the dataset.

Tokenizing and padding text sequences to prepare the data for the LSTM model.

**Model Construction:**

Building a Sequential model with an Embedding layer and LSTM layer.

Output layer with a sigmoid activation function for binary classification.

**Training and Evaluation:**

Compiling the model using the Adam optimizer and binary crossentropy loss.

Training the model on the training dataset and validating it on a separate test dataset.

**Prediction:**

Using the trained model to predict the sentiment of new movie reviews.
