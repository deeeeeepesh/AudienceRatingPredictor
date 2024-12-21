This repository contains a comprehensive machine learning project aimed at predicting audience ratings for movies using data from Rotten Tomatoes. The project explores multiple regression models, including Linear Regression, Random Forest, XGBoost, CatBoost, and a hyperparameter-tuned Stacking Regressor. It also features a neural network model for improved performance. The project includes robust data preprocessing, feature engineering, hyperparameter tuning, and cross-validation to ensure accuracy. The code is well-documented and structured for reproducibility.
# Audience Rating Prediction: A Comprehensive Machine Learning Project

This repository contains an end-to-end machine learning project focused on predicting audience ratings for movies using data from Rotten Tomatoes. The project involves robust preprocessing, feature engineering, and implementation of various machine learning models, including:

- **Linear Regression (Tuned)**
- **Random Forest**
- **XGBoost**
- **CatBoost**
- **Hyperparameterized Stacking Regressor**
- **Neural Network**

## Dataset

The dataset is sourced from Rotten Tomatoes, containing information about movies such as genres, cast, runtime, tomatometer ratings, audience ratings, and more.

## Key Features of the Project

1. **Data Preprocessing**:
   - Handling missing values
   - One-hot encoding for categorical features
   - Scaling for numerical features

2. **Feature Engineering**:
   - Extracted primary genres and release years
   - Calculated additional features like cast size and runtime-to-rating ratios

3. **Models Implemented**:
   - Linear Regression with hyperparameter tuning
   - Random Forest, XGBoost, and CatBoost
   - A hyperparameter-tuned Stacking Regressor combining XGBoost and CatBoost
   - Neural Network implementation for enhanced accuracy

4. **Evaluation Metrics**:
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score

## Results
- **MAE**: 4.669
- **RMSE**: 8.303
- **R²**: 0.829

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/username/AudienceRatingPredictor.git
  
