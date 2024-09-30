## Regression of used Car Prices

![car_prediction](https://github.com/user-attachments/assets/61741b06-0cf9-4481-b2d5-3af43678ce0d)

## Objective

The goal of this competition is to develop a machine learning model to accurately predict the price of used cars based on various features such as brand, model, model year, mileage, fuel type, engine and other relevant factors. The goal is to assist buyers and sellers in determining fair market value and improving pricing strategies in the used car market.

## Data Collection

I have sourced the "Used Car Prices" dataset from Kaggle.

https://www.kaggle.com/competitions/playground-series-s4e9/data

The dataset contains 3,14,223 details of used cars for this hackathon.

## Data Cleaning and Preprocessing

- Dummy Encoded Categorical Variables.
- Bucketed Categorical Variables based on their counts to reduce Dimensions.
- Bucketed Null values and encoded them.

## Model

- Tried various models and did Hyperparameter tuning and got best results by XG-Boost Regressor.
