# Car Price Prediction

This project predicts the selling price of used cars based on features such as year of manufacture, present price, kilometers driven, fuel type, seller type, transmission, and owner details. Various regression models are implemented and compared to find the best model for predicting car prices.

## Dataset

The dataset contains information about used cars, including details such as car name, year of manufacture, selling price, present price, kilometers driven, fuel type, seller type, transmission, and owner details.

## Project Overview

This project explores a dataset of used car information, preprocesses the data, builds, and evaluates regression models to predict car prices. It employs a range of visualization techniques for data exploration, encoding categorical variables, and model evaluation to find the most accurate prediction model.

1. Data Exploration and Visualization
 - Dataset Overview
 - Visualization

2. Data Preprocessing
 - Categorical Encoding
 - Feature Engineering
 - Train-Test Split
 - Feature Scaling

3. Model Building and Evaluation
 - Implemented various regression models:
    1. Linear Regression
    2. Decision Tree Regressor
    3. Random Forest Regressor
    4. XGBoost Regressor
    5. MLP Regressor
 - Training and Prediction
 - Model Evaluation

4.  Model Comparison and Selection
 - Comparing model performance based on MSE and R-squared scores.
 - Selecting the best performing model for car price prediction.


## Conclusion

We found that the MLP Regressor provides the best performance for predicting car prices, with the lowest Mean Squared Error (MSE) and the highest R-squared score. This indicates that the MLP Regressor model is well-suited for this task.

