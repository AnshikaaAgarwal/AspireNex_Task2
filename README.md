# AspireNex_Task2
# Spam SMS Detection


## Overview
This project focuses on detecting spam emails using machine learning techniques. The dataset used consists of labeled emails categorized as spam or non-spam (ham). Various natural language processing (NLP) techniques and classification algorithms were implemented to build and evaluate the detection system.

## Table of Contents
- [Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- UnderSampling
- TF-IDF
- Models
- Evaluation
- Results


## Dataset
The dataset comprises labeled emails with features extracted for classification into spam and ham categories. It consists of 5000 labeled emails, where each email is annotated as spam or ham based on its content and characteristics.

## Data Balancing Using UnderSampling
To address the imbalance between spam and ham emails in the dataset, undersampling was employed. This technique involves randomly sampling instances from the majority class (ham) to match the number of instances in the minority class (spam). By reducing the number of majority class instances, undersampling aims to balance the distribution of classes in the dataset, thereby improving the performance of machine learning models trained on imbalanced data.

## TF-IDF
TF-IDF (Term Frequency-Inverse Document Frequency) was employed for feature vectorization in this project. TF-IDF is a statistical measure used to evaluate how important a word is to a document in a collection or corpus. It works by multiplying two metrics: the term frequency (TF), which measures how frequently a term occurs in a document, and the inverse document frequency (IDF), which diminishes the weight of terms that occur frequently across the entire corpus.
In the context of spam detection, TF-IDF was used to transform each email into a numerical vector representation based on the frequency of terms specific to that email compared to the entire dataset. This vectorization technique helps in capturing the unique characteristics of spam and ham emails, enabling machine learning models to effectively classify them.

## Models
- Naive Bayes
- Logistic Regression
- Support Vector Machine

## Evaluation
The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The evaluation focused on the ability to correctly classify spam emails while minimizing false positives (non-spam emails classified as spam).

## Results
The performance of each model was compared, and the results were summarized to identify the most effective model for spam detection




