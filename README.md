# 🚗 Car Price Prediction

 Predicting used car prices using machine learning to empower smarter buying and selling decisions.

 ![A View of car price](https://storage.googleapis.com/pod_public/1300/121017.jpg)


---

# ⚠️ Disclaimer
All datasets, information, and reports within this repository are fictional and created solely for illustrative purposes to showcase advanced predictive machine learning techniques. They do not include any real proprietary, confidential, or sensitive information related to any company, organization, or individual.


## 📑 Table of Contents

1. [Problem Statement](#problem-statement)  
2. [Objective](#objective)  
3. [Introduction](#introduction)  
4. [Dataset](#dataset)  
5. [Data Preprocessing](#data-preprocessing)  
6. [Model Training](#model-training)  
7. [Evaluation](#evaluation)  
8. [Contacts](#contacts)

---

## ❓ Problem Statement

In the used car market, determining a fair and accurate price is challenging due to the wide range of factors that influence value — such as mileage, engine size, model year, and brand. Buyers often overpay, while sellers risk undervaluing their vehicles due to poor pricing knowledge. This project addresses that gap by building a robust model to predict car prices using machine learning techniques.

---

## 🎯 Objective

The goal of this project is to develop a machine learning model that can:

- Predict the selling price of a car based on its attributes.
- Handle noisy and inconsistent data with outliers.
- Assist users in making data-driven car purchasing and selling decisions.

---

## 📘 Introduction

This project leverages historical car data to train a model that predicts the **selling price** of cars based on various features. It is particularly useful for consumers, dealerships, and price comparison platforms.

By using machine learning algorithms like **Random Forest Regressor**, the model learns the relationship between car attributes and their market price.

---

## 📊 Dataset

The dataset contains features that influence a car’s price, including:

- `Selling Price` (Target Variable)
- `Model`
- `Year`
- `Mileage`
- `Engine Size`
- `Fuel Type`
- `Transmission`
- ...and potentially more

These features are cleaned, encoded, and scaled during the preprocessing phase to ensure the model gets quality inputs.

---

## 🧹 Data Preprocessing

To prepare the data for modeling:

- Missing values are handled through imputation or removal.
- Categorical variables (e.g., fuel type, transmission) are encoded using Label or One-Hot Encoding.
- **Robust Scaler** is used instead of StandardScaler or MinMaxScaler due to the presence of **outliers** in mileage, engine size, and price:

## 🛠️ Model Training

The model of choice for this project is:

### ✅ Random Forest Regressor

**Random Forest** is an ensemble learning method that builds multiple decision trees and combines their outputs to improve prediction accuracy and control overfitting.

It was selected for the following reasons:

- ✅ **Handles both categorical and numerical data**  
- ✅ **Robust to outliers and noise in the dataset**  
- ✅ **Reduces overfitting** by averaging multiple decision trees  
- ✅ **Captures complex feature interactions** automatically  
- ✅ **Provides feature importance scores** for interpretability  

## 📈 Evaluation

The model’s performance is evaluated using the following regression metrics:

### 📌 Mean Absolute Error (MAE)

- Measures the average magnitude of the prediction errors, without considering their direction.
- It gives a linear score, meaning all individual differences are weighted equally in the average.

- Penalizes larger errors more than MAE by squaring the differences.
- Useful when you want your model to avoid large mistakes.

  ### 📌 R-squared Score (R²)

- Indicates the proportion of the variance in the target variable that is predictable from the features.
- Values range from 0 to 1. Higher is better.

  ### 📌 Mean Squared Error (MSE)

- Penalizes larger errors more than MAE by squaring the differences.
- Useful when you want your model to avoid large mistakes.

  ## 📬 Contacts

For any questions, feedback, or collaboration opportunities, feel free to reach out:

- 📧 **Email**: [njerisharon611@gmail.com](njerisharon611@gmail.com)  
- 🌐 **GitHub**: [car-price-predictor](https://github.com/8Sharon/Car-Price-Prediction)




