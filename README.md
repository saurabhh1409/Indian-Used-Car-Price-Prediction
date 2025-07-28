# Indian-Used-Car-Price-Prediction

## Project Overview

This project aims to predict the price of used cars in Indian IT cities using machine learning techniques. With the increasing demand for used cars, it becomes crucial for buyers and sellers to estimate a fair price. Leveraging a detailed dataset that includes various attributes such as brand, model, fuel type, kilometers driven, and more, we build a predictive model to estimate car prices effectively.

## Data Description

The dataset used is the Indian IT Cities Used Car Dataset 2023, which contains detailed records of used car listings across multiple cities in India. This dataset includes features like car specifications, dealer information, warranty, and price.

## Data Dictionary

| Column Name         | Description                                              |
|---------------------|----------------------------------------------------------|
| ID                  | Unique ID for each listing                               |
| Company             | Name of the car manufacturer                             |
| Model               | Name of the car model                                    |
| Variant             | Name of the car variant                                  |
| Fuel Type           | Fuel type of the car                                     |
| Color               | Color of the car                                         |
| Killometer          | Number of kilometers driven by the car                  |
| Body Style          | Body style of the car                                    |
| Transmission Type   | Transmission type of the car                             |
| Manufacture Date    | Manufacture date of the car                              |
| Model Year          | Model year of the car                                    |
| CngKit              | Whether the car has a CNG kit or not                     |
| Price               | Price of the car                                         |
| Owner Type          | Number of previous owners of the car                     |
| Dealer State        | State in which the car is being sold                     |
| Dealer Name         | Name of the dealer selling the car                       |
| City                | City in which the car is being sold                      |
| Warranty            | Warranty provide by dealers                              |

## Project Workflow

Data Cleaning – Handling missing values, inconsistent formats, and outliers.
Exploratory Data Analysis (EDA) – Understanding patterns and distributions.
Feature Engineering – Creating useful features from raw data.
Model Selection – Trying various ML models (Linear Regression, XGBoost, etc.).
Model Evaluation – Measuring performance using MAE, RMSE, and R².
