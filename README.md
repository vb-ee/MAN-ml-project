# MAN ML Project

## Introduction

This project aims to build the best performing model for predicting the amplitudes for MAN company's truck engines. The dataset consists of 88 features and approximately 27 thousand rows. Please note that the data is confidential and cannot be publicly distributed, so only the implementation details are presented in this Jupyter Notebook.

## All the necessary libraries are included in the `requirements.txt` file. To install them run:

`pip install -r requirements.txt`

## Data Preprocessing

To ensure data integrity, the dataset was split into a 70-30 train-test split before processing and feature selection to avoid data leakage and keep the test dataset unseed. The following preprocessing steps were performed:

- Encoding of string features
- Scaling of numerical features

## Feature Selection

To improve the accuracy of the model, 2 feature selection methods were applied. These methods help identify the most relevant features for the prediction task.

## Model Training

The following models were implemented for training:

- Linear Regression
- Decision Trees Regressor
- Neural Networks

Hyperparameter tuning was performed to optimize the models' performance considering the computational limitiations.

## Evaluation

The performance of the models was evaluated using the test dataset. Mean Squared Error (MSE) was computed as the evaluation metric. The results were compared to determine the best performing model.

### The implementation details and evaluation results are presented in Notebook.
