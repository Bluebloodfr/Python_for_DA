# Drug Consumption Prediction Using Machine Learning
## Project Overview
This project involves the development of a machine learning model to predict drug consumption patterns based on personality traits and demographic information. The data set used includes measurements of personality traits such as neuroticism, extraversion, openness to experience, agreeableness, conscientiousness, impulsivity, and sensation seeking. Additional attributes include education level, age, gender, country of residence, and ethnicity.
### Objective
The primary objective is to analyze the dataset, preprocess it, and apply machine learning models to predict the probability of drug consumption for various substances. The project aims to understand the influence of personality and demographic factors on drug use.
### Data Preprocessing
The dataset underwent several preprocessing steps including:
•	Conversion of categorical data into numerical format.
•	Normalization of continuous variables.
•	One-hot encoding of categorical variables.
## Machine Learning Models
Three different machine learning models were explored:
1.	Logistic Regression: Served as a baseline model with variable performance across different drugs.
2.	Random Forest: Provided robust predictions with high accuracy for certain drugs.
3.	Support Vector Machine (SVM): Demonstrated balanced performance, especially effective in high-dimensional spaces.
Hyperparameter tuning was conducted for each model to optimize their performance.
## Model Evaluation
The models were evaluated based on their precision scores, and their performance varied significantly across different drugs. This variation highlighted the need for tailored model configurations for each drug, considering the unique influences on usage patterns.
## Flask Web Application
A Flask web application was developed to allow users to input personality and demographic data and receive predictions on their drug consumption patterns. The application integrated the logistic regression model for making predictions.
# Conclusion
The analysis revealed significant variations in drug consumption patterns based on personality and demographic factors. The machine learning models provided valuable insights, with each model showing strengths in predicting certain drugs over others. The Flask application serves as an interactive tool for predicting drug use based on individual characteristics.

