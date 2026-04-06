# naive_bayes
This project applies Naive Bayes Classification to detect spam messages in text data. The workflow includes Exploratory Data Analysis (EDA), data preprocessing, domain-specific analysis, model creation, evaluation &amp; validation, and visualization using Orange.

# Email Spam Detection using Naive Bayes

## Project Overview
This project focuses on building a machine learning model to classify emails as Spam or Ham (Not Spam) using the Naive Bayes classification algorithm. The objective is to automatically detect unwanted spam messages using Natural Language Processing (NLP) techniques.

## Problem Statement
Spam emails are a major issue in communication systems. The goal of this project is to build a classification model that can automatically detect whether an email is spam or legitimate.

## Dataset Information

Dataset contains:

Total Records: 5572  
Columns: 2

Features:

type → Target variable (spam / ham)  
email → Email message text  

Example:

| type | email |
|------|-------|
| ham | Go until jurong point |
| spam | Free entry in contest |

## Technologies Used

Python  
Pandas  
NumPy  
Scikit-learn  
NLTK  
Matplotlib  
Seaborn  

## Machine Learning Algorithm Used

Naive Bayes Classifier (MultinomialNB)

Reason:
Naive Bayes works very well for text classification problems because it uses probability based classification.
