# Spaceship Titanic Kaggle Challenge

## Table of Contents
- [Introduction](#introduction)
- [Team Members](#team-members)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Development](#model-development)
- [Model Evaluation](#model-evaluation)
- [Explainable AI (XAI)](#explainable-ai-xai)

## Introduction
This repository contains the work of our team for the Spaceship Titanic Kaggle Challenge. Our task was to develop a statistical/machine learning model to predict which passengers are transported to an alternate dimension. We used various data science techniques including data preprocessing, exploratory data analysis (EDA), model development, and evaluation.

## Team Members
- 22030006 - Saikamal Govada
- 22024306 - Nalla Sathvika
- 22033605 - Molugu Sandeep
- 22032127 - Battula Abhishek
- 22010044 - Faisal Zulfiqar
- 21069608 - Muhammad Ali

## Dataset
The dataset for this challenge can be found on the [Spaceship Titanic Kaggle page](https://www.kaggle.com/competitions/spaceship-titanic/data). It consists of three files:
- `train.csv`: Training data
- `test.csv`: Test data
- `sample_submission.csv`: Sample submission file

## Exploratory Data Analysis (EDA)
Our EDA notebook explores the dataset, providing insights and visualizations that guided our feature engineering and model selection. Key steps include:
- Handling missing values
- Understanding distributions of features
- Visualizing correlations

## Model Development
We developed several models to predict the target variable, including:
- Logistic Regression
- Random Forest

The final model was chosen based on its performance on the validation set.

## Model Evaluation
We evaluated our models using various metrics including accuracy, precision, recall, and F1 score. The evaluation results are documented in the Model_Evaluation notebook.

## Explainable AI (XAI)
We used feature importance from our Random Forest model to understand which features contributed most to our predictions. A bar plot of feature importances is saved as `model_explainability.png`.
