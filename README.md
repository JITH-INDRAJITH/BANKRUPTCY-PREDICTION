# BANKRUPTCY-PREDICTION
Overview
Bankruptcy due to business failure can have severe repercussions on both enterprises and the global economy. Understanding and predicting the symptoms of potential bankruptcy is crucial for early intervention and appropriate decision-making. This project aims to develop a predictive model that can determine whether a company is at risk of bankruptcy based on various financial and operational aspects. The prediction model will facilitate timely interventions to mitigate the risk of bankruptcy.

# Problem Statement
The primary goal of this project is to develop a binary classification model to predict whether a company will go bankrupt (1) or not (0). This model will analyze different distress indicators in a company, helping stakeholders make informed decisions to prevent potential bankruptcies.

# Dataset Description
The dataset consists of several features that capture various aspects of a company's financial health and operational performance. Key features include:

There are total 6819 samples in dataset and 96 features , Out of these 6819, 6599 are negative class and only 220 are positive class.
This dataset is highly imbalanced. It makes this problem very challenging to generalise well for final predictions.
All the features in the datset are normalized in the range 0 to 1.
The target column is “Bankrupt” which has two values ‘0’ and ‘1’ for Not Bankrupt and Yes Bankrupt respectively.
 It is important to predict the positive class(1) with very high accuracy even if we are not able to predict the negative class. For example, there are total 100 companies out of which 90 are safe and 10 are going to get bankrupt. We should be focused on finding those 10.

# Objectives
Data Preprocessing: Handle missing values, normalize and scale features.
Exploratory Data Analysis: Understand the data distribution, identify correlations, and visualize patterns.
Model Building: Develop and compare various machine learning models to predict bankruptcy risk.
Evaluation: Assess model performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

# Results
The results and analysis of the predictive models will be documented in detail, including the performance metrics and insights gained from the study.


