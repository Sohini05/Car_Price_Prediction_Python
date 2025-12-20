# 🚗 Car Price Prediction using Multiple Linear Regression

## 📌 Project Overview

This project focuses on predicting the price of used cars using **Multiple Linear Regression**. The objective is to analyze how different car attributes—such as age, mileage, engine capacity, power and weight—affect the selling price and to evaluate the effectiveness and limitations of a linear regression model on real-world data.['Age','KM','Weight','HP', 'MetColor', 'CC', 'Doors']

The project emphasizes **Exploratory Data Analysis (EDA)**, model building, performance evaluation and **cross-validation** to gain a clear understanding of model behavior.

---

## 📂 Dataset

The dataset contains information about used cars, including:

* Age of the car
* Kilometers driven
* Engine capacity (CC)
* Horsepower (HP)
* Weight
* Fuel type and other categorical features

**Target Variable:** Car Price

Basic data cleaning and preprocessing were performed before model training.

---

## 🔍 Exploratory Data Analysis (EDA)

* Analyzed distributions of numerical features
* Studied relationships between predictors and car price
* Visualized linear trends such as *Age vs Price*

EDA helped justify the use of Multiple Linear Regression by identifying linear relationships between key predictors and the target variable.

---

## 🧠 Model Used

### Multiple Linear Regression

The model predicts car prices as a linear combination of multiple independent variables.

**Key steps involved:**

* Feature selection
* Train–test split
* Model training using `LinearRegression` from **scikit-learn**

---

## 📊 Model Evaluation

The model was evaluated using standard regression metrics:

* **R² Score** – Measures the proportion of variance explained by the model
* **MAE (Mean Absolute Error)** – Average absolute difference between actual and predicted prices
* **RMSE (Root Mean Squared Error)** – Penalizes larger prediction errors

---

## 📈 Test Data Results

* **R²:** 0.86
* **MAE:** ~952
* **RMSE:** ~1327

---

## 🔁 Cross-Validation

To assess model generalization, **K-Fold Cross-Validation** was performed using R² as the scoring metric.

* **Average Cross-Validated R²:** ~0.12

This indicates that although the model performs well on a single test split, its performance varies across different data partitions, highlighting generalization limitations.

---

## ⚠️ Limitations

* Presence of multicollinearity among predictors
* Sensitivity to data splits
* Lower stability across cross-validation folds

---

## 🚀 Future Improvements

* Apply regularization techniques such as **Ridge** or **Lasso Regression**
* Perform advanced feature engineering
* Try non-linear models for comparison
* Improve data scaling and feature transformations

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 📌 Conclusion

This project demonstrates the practical application of Multiple Linear Regression for car price prediction. While the model shows strong performance on test data, cross-validation reveals generalization challenges, emphasizing the importance of robust evaluation techniques in machine learning workflows.

---

## 👩‍💻 Author

**Sohini Mandal**

⭐ If you found this project useful, feel free to star the repository!
