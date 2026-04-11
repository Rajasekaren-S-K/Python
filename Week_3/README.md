# Week 3 - Regression Analysis

## 12 Week AI Engineering Journey

This folder contains the Week 3 assignment focused on Regression techniques applied to an insurance charges dataset.

## Assignment: Insurance Charges Prediction

### Dataset
- **File:** `insurance_pre.csv`
- - **Target:** `charges` (insurance cost prediction)
  - - **Features:** `age`, `sex`, `bmi`, `children`, `smoker`
   
    - ### What's Covered
    - - Exploratory Data Analysis (EDA)
      - - Outlier detection and removal using IQR method
        - - Label encoding for categorical features
          - - Feature scaling with StandardScaler
            - - Train/Test split (70/30)
             
              - ### Models Trained & Compared
              - | Model | Type |
              - |---|---|
              - | Linear Regression | Baseline |
              - | Decision Tree Regressor | Tree-based |
              - | Random Forest Regressor | Ensemble |
              - | Gradient Boosting Regressor | Boosting |
              - | AdaBoost Regressor | Boosting |
              - | XGBoost Regressor | Boosting |
             
              - ### Evaluation Metric
              - - **R2 Score** used to compare all models
               
                - ### Files
                - - `Assignment-Regression.ipynb` - Main notebook with full analysis and model comparison
