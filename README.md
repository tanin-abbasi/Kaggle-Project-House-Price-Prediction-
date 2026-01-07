# Kaggle-Project-House-Price-Prediction-
This is a Kaggle-style regression project predicting house sale prices.
## Dataset
- Source: [Kaggle House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- Goal: Predict the sale price for each house using various features.
- File format: `Id` and `SalePrice` columns for submission.

## Skills & Techniques
- **Data Preprocessing / Feature Engineering**
  - Handling missing values for numeric and categorical features
  - Transforming skewed target variable (`log1p`)
  - One-hot encoding for categorical features
    
- **Regression Models**
  - Linear models: Ridge, LASSO, ElasticNet
  - Tree-based models: Random Forest, XGBoost
    
- **Model Evaluation**
  - Cross-Validation (5-fold)
  - RMSE as evaluation metric
    
- **Ensemble**
  - Weighted average of multiple models for final prediction

## Visualizations
- Missing data heatmap
- Feature distributions and correlations
- RMSE comparison between models

## Results
- Evaluation Metric: RMSE
- Best Kaggle Public Score: 0.12998

## Notes
- This project is **for learning and practice purposes** using the Kaggle dataset.
- The pipeline and models are implemented from scratch, inspired by Kaggle competition workflow.
