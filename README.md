# E-commerce User Preference Prediction

This project develops predictive models to analyze user preferences in an e-commerce setting. The primary goal is to predict user ratings as binary values: 1 for "like" and 0 for "dislike". Through this classification problem, we explore data preprocessing, feature engineering, and model development with techniques like Logistic Regression and K-Nearest Neighbors (KNN).

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Overview](#dataset-overview)
3. [Project Workflow](#project-workflow)
4. [Models and Techniques](#models-and-techniques)
5. [Evaluation Metrics](#evaluation-metrics)
6. [Results and Insights](#results-and-insights)
7. [Requirements](#requirements)
8. [Usage](#usage)
9. [Citations](#citations)

## Introduction
The project involves predicting user preferences for an e-commerce platform by analyzing features and their relationship with user ratings. The target variable, rating, is converted into binary outcomes for simplified classification.

## Dataset Overview
The dataset used contains e-commerce user interaction data, including various features that may influence user preferences (e.g., product type, price, user demographics). The rating column serves as the target variable, transformed into binary categories for "like" and "dislike."

## Project Workflow
1. **Data Exploration and Cleaning**  
   - Initial dataset inspection to identify anomalies or missing values.  
   - Data cleaning includes removing abnormal instances and handling missing data.  

2. **Feature Encoding**  
   - Conversion of categorical features to numerical using encoding techniques to prepare data for machine learning models.  

3. **Correlation Analysis**  
   - Analysis of feature relationships and their potential impact on the target variable (rating).  

4. **Model Development**  
   - **Logistic Regression:**  
     - Splitting the dataset into training and testing sets.  
     - Training and evaluating a Logistic Regression model for prediction accuracy.  
   - **K-Nearest Neighbors (KNN):**  
     - Training and evaluating a KNN model with an initial arbitrary K value.  
     - Hyperparameter tuning for optimal K value using grid search or cross-validation.  

5. **Performance Comparison**  
   - Evaluation of both models to determine strengths and weaknesses.  

## Models and Techniques
- **Logistic Regression:**  
  A linear model for binary classification problems.  
- **K-Nearest Neighbors (KNN):**  
  A non-parametric algorithm that predicts outcomes based on the closest data points in feature space.  

## Evaluation Metrics
- **Accuracy Score:** Measures the proportion of correct predictions.  
- **Confusion Matrix (optional):** Provides insight into prediction errors for both classes.  

## Results and Insights
The notebook documents findings from both models, including performance comparisons, strengths, and limitations of each technique.

## Requirements
**Python Libraries:**  
- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

## Usage
1. Clone this repository:  
   ```bash
   git clone https://github.com/benymean/ecomm-user-preference-prediction.git
