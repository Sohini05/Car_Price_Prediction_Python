# Car Price Prediction using Multiple Linear Regression

## Project Overview

This project focuses on predicting the price of used cars using Multiple Linear Regression. The objective is to analyze how different car attributes such as age, mileage, engine capacity, power, and weight influence the selling price and to evaluate the effectiveness and limitations of a linear regression model on real-world data.

The project emphasizes exploratory data analysis, model building, performance evaluation, and cross-validation to understand model behavior.

## Dataset

The dataset contains information about used cars, including:

* Age of the car
* Kilometers driven
* Engine capacity (CC)
* Horsepower (HP)
* Weight
* Fuel type and other categorical features

Target Variable: Car Price

Basic data cleaning and preprocessing were performed before model training.

## Exploratory Data Analysis (EDA)

* Analyzed distributions of numerical features
* Studied relationships between predictors and car price
* Visualized linear trends such as Age vs Price

EDA supported the use of Multiple Linear Regression by identifying linear relationships between predictors and the target variable.

## Model Used

Multiple Linear Regression

The model predicts car prices as a linear combination of multiple independent variables.

Steps involved:

* Feature selection
* Train-test split
* Model training using LinearRegression from scikit-learn

## Model Evaluation

The model was evaluated using the following metrics:

* R-squared (R²)
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

## Test Data Results

* R²: 0.86
* MAE: ~952
* RMSE: ~1327

## Cross-Validation

K-Fold Cross-Validation was applied using R² as the evaluation metric.

* Average cross-validated R²: ~0.12

This shows that although the model performs well on a single test split, performance varies across different data partitions.

## Limitations

* Multicollinearity among predictors
* Sensitivity to data splits
* Lower stability across cross-validation folds

## Future Improvements

* Apply Ridge or Lasso regression
* Perform advanced feature engineering
* Experiment with non-linear models
* Improve scaling and feature transformations

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

## Conclusion

This project demonstrates the application of Multiple Linear Regression for car price prediction. While test performance is strong, cross-validation highlights generalization challenges, emphasizing the need for robust model evaluation.

## Author

Sohini Mandal
