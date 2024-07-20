# Sentiment-Analysis-using-Hugging-Face-Transformers

##Overview
This project aims to perform sentiment analysis on a dataset using a pre-trained BERT model from the Hugging Face Transformers library. The sentiment analysis determines whether the text expresses positive, negative, or neutral sentiment.

##Project Structure

#Data Loading:

The dataset "smile-annotations-final.csv" is loaded using Pandas.

#Model Initialization:

A BERT model (Bidirectional Encoder Representations from Transformers) is initialized for sentiment analysis.
The model used is "distilbert-base-uncased-finetuned-sst-2-english" from Hugging Face Transformers.

#Sentiment Analysis:

Text data is extracted from the second column (611857364396965889) of the dataset.
The pre-trained sentiment analysis model analyzes the sentiment of the text.

#Prediction and Display:
The sentiment analysis model predicts the sentiment for each text entry in the dataset.
The results, including the text, predicted sentiment, and confidence score, are displayed.
