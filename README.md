# COMP-606-ML-Course-Project
A machine learning project to predict Airbnb listing prices in New York City using attributes such as neighbourhood_group, room_type, number_of_reviews, and more. The project employs various regression models to evaluate their performance on predicting prices.

## Table of Content 
1. Dataset
2. Project Workflow
3. Models Trained
4. Evaluation Metrics
5. Installation
6. Usage
7. Results

## Dataset
The project uses the New York City Airbnb Dataset, containing the following features:

*  neighbourhood_group: The borough (e.g., Manhattan, Brooklyn).
*  room_type: Type of listing (e.g., Entire home, Private room).
*  price: The target variable to predict.
*  minimum_nights: Minimum stay required.
*  number_of_reviews: Total reviews for the listing.
*  availability_365: Number of days available in a year.

## Data Preprocessing:
* Missing values: Handled using median imputation for numerical columns and mode imputation for categorical columns.
*  Outliers: Addressed using the IQR method.
*  Feature engineering: Created new attributes and standardized numerical features.
*  Encoding: One-hot encoding for categorical variables.

## Project Workflow

####  1. Data Cleaning:
*  Handled missing values and removed outliers.
#### 2. Exploratory Data Analysis (EDA):
*  Visualized data distributions and relationships.
*  Identified correlations between features and price.
#### 3. Feature Engineering:
*  Engineered new features like distance_from_center.
*  Encoded categorical variables using one-hot encoding.
#### 4. Model Training:
*  Trained multiple regression models.
#### 5. Model Evaluation:
*  Evaluated models using MSE, RMSE, MAE, and R² Score.

## Models Trained
1. Linear Regression: A baseline linear model for prediction.
2. Gradient Boosting Regressor: A powerful boosting algorithm.
3. Support Vector Regressor (SVR): Suitable for non-linear relationships.

## Evaluation Metrics:
The following metrics were used to evaluate the models:

1. Mean Squared Error (MSE): Average squared difference between actual and predicted prices.
2. Root Mean Squared Error (RMSE): The square root of MSE, in the same unit as the target.
3. Mean Absolute Error (MAE): Average absolute error in predictions.
4. R² Score: Proportion of variance explained by the model (
𝑅
2
∈
[
0
,
1
]
R 
2
 ∈[0,1]).

