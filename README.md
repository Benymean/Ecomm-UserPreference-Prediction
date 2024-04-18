# E-commerce User Preference Prediction

This repository delves into the prediction of user preferences within an e-commerce dataset, specifically focusing on whether users 'like' or 'dislike' products.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Exploration & Cleaning](#data-exploration--cleaning)
3. [Feature Encoding](#feature-encoding)
4. [Feature Correlations](#feature-correlations)
5. [Logistic Regression Model](#logistic-regression-model)
6. [KNN Model & Hyperparameter Tuning](#knn-model--hyperparameter-tuning)
7. [Conclusion & Model Comparisons](#conclusion--model-comparisons)
8. [License](#license)

## Introduction

Building upon previous analyses, this notebook concentrates on an e-commerce dataset where user ratings are now binary: 'like' (score 1) or 'dislike' (score 0). The challenge lies in using classification models to predict these binary ratings from other dataset features.

## Data Exploration & Cleaning

The initial steps involve a deep dive into the dataset, understanding its nuances, and ensuring data cleanliness by removing anomalies and handling missing values.

## Feature Encoding

For a more streamlined modeling process, object features in the dataset are encoded into digit features.

## Feature Correlations

This section delves into the relationships between different dataset features, aiding in understanding which might be most influential in predicting user ratings.

## Logistic Regression Model

A logistic regression model is trained and evaluated to predict user preferences, offering insights into its performance on the dataset.

## KNN Model & Hyperparameter Tuning

In addition to logistic regression, a KNN model is also employed. This section also delves into the effects of different hyperparameters on the model's performance, ensuring optimal configuration for prediction.

## Conclusion & Model Comparisons

A comprehensive comparison between the Logistic Regression and KNN models is provided, focusing on their performance metrics and suitability for this specific dataset.

## Dependencies

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

