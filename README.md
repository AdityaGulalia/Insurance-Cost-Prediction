Insurance Cost Prediction (Linear Regression)
Project Description

This project predicts medical insurance charges using a Linear Regression model.
It is a beginner machine learning project designed to understand the basic supervised learning pipeline.

Objective

To predict insurance charges based on:

Age

Gender

BMI

Number of children

Smoking status

Region

Dataset

The dataset contains 1338 records with the following features:

Feature	Description
age	Age of the person
sex	Male or female
bmi	Body mass index
children	Number of dependents
smoker	Smoker or non-smoker
region	Residential area
charges	Insurance cost (target)
Steps Performed

Loaded and inspected the dataset

Explored data distributions and correlations

Encoded categorical variables using one-hot encoding

Split data into training and testing sets

Trained a Linear Regression model

Evaluated the model using MAE, RMSE, and R²

Improved performance using log transformation

Model Performance

MAE: 0.27 (log scale)

RMSE: 0.42 (log scale)

R² Score: 0.80

The model explains about 80% of the variation in insurance charges.

Key Insight

Smoking status has the largest impact on insurance costs.

Tools Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

What I Learned

How to prepare data for machine learning

How to train a regression model

How to evaluate model performance

How feature transformations affect results
