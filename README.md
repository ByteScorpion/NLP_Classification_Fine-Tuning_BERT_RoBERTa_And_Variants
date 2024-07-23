# NLP Classification Fine-Tuning BERT,RoBERTa And Variants
##  Opinion Spam Detection Datathon Challenge : 

This repository contains the code and resources used for the Opinion Spam Detection Datathon Challenge. The task was to develop machine learning models to accurately classify reviews from Chicago hotels and restaurants as either spam or non-spam (genuine).

## Overview
In this challenge, I fine-tuned a RoBERTa model to classify reviews based on their content and metadata. The goal was to achieve high categorization accuracy, measured by the number of correct predictions divided by the total number of predictions.

## Dataset
The dataset consists of reviews and metadata. Each review is labeled as either spam (Y) or non-spam (N). The dataset is split into training and testing sets, and participants are required to submit their predictions in the specified format.

## Evaluation
The evaluation metric is categorization accuracy, calculated as follows:

Accuracy = (Number of Correct Predictions / Total Number of Predictions) * 100
