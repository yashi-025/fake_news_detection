Title: Fake News Detection with Logistic Regression

Description:
This repository contains code for a machine learning model designed to classify news articles as either real or fake. The model is built using logistic regression and utilizes natural language processing techniques for text preprocessing and feature extraction.

Contents:

Dataset: Includes a CSV file containing news articles with columns for unique ID, title, author, text, and label indicating whether the news is real (0) or fake (1).
Dependencies: Lists the necessary libraries and packages required to run the code, such as NumPy, pandas, NLTK, and scikit-learn.
Data Pre-processing: Code for loading the dataset, handling missing values, merging author names with titles, and performing text preprocessing steps like stemming and converting textual data into numerical data using TF-IDF vectorization.
Training the Model: Implementation of logistic regression for training the classification model using the preprocessed data.
Evaluation: Calculation of accuracy scores on both training and test data to evaluate the performance of the trained model.
Predictive System: Code for making predictions on new data instances using the trained model, along with an example prediction.

This projects serves as a basic example of using logistics regression for binary classification of news articles. 
Here the data with values above than 0.5(threshold value) are fake news and data with values below threshold value are real news.
