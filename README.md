# Ride Hailing Platform Trip Prices
This project, "Ride Hailing Platform Trips," is part of my Hacktiv8 coursework on regression. It serves as both a requirement for my Hacktiv8 studies and a component of my personal portfolio in Data Science. I created this project with a fictional background, made solely for the purpose of the project. You can find my other personal projects on [Richard Edgina Virgo](https://github.com/REV04).

#### -- Project Status: Finished

## Project Intro/Objective

The purpose of this project is to predict taxi fares based on the provided information. I developed a model to make these predictions. This model will be trained and evaluated to ensure its accuracy and will then be used to predict taxi prices.

### Methods Used
- Linear Regression
- Data Visualization
- Data Analysis
### Technologies

- Python

## Project Description

The dataset used for creating this model is sourced from Kaggle and contains information about a Rideshare Platform. I performed Exploratory Data Analysis (EDA) to understand the data better. Following EDA, I applied feature engineering to enhance the model's performance. I used a linear regression model and proceeded with model training and evaluation using mean absolute error (MAE) and R² score. Additionally, I analyzed the assumptions of linear regression.

The results from the model are as follows:

- MAE - Train Set: 1.7999
- MAE - Test Set: 1.8390
- R² Score - Train Set: 0.9257
- R² Score - Test Set: 0.9220
- The relationship between features and the target variable is not linear.

In predicting taxi fares, the machine learning model uses linear regression. The analysis shows that the relationship between features and the target variable in the regression model is not linear, violating the assumption that the correlation between features and the target variable should be high while the correlation between features should be low or non-existent. Residual analysis reveals issues such as non-linearity, heteroscedasticity, and non-normally distributed data. Therefore, this model needs further refinement to improve prediction accuracy and ensure that regression assumptions are met. This could involve using alternative regression algorithms, such as Polynomial Regression.

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Exploratory Data Analysis (EDA), Model Training, Model Evaluation, summary, and inference are being kept in Python/Ride-Hailing-Platform-Trip-Places.ipynb
3. Model like list categorical column, list numerical column, model encoder, linear regression model, scaler model, and one hot encoder are being kept in Model folder

## Contact

- If you have any question or want to contribute with this project, feel free to ask me in [linkedln](https://www.linkedin.com/in/richard-edgina-virgo-a7435319b/).