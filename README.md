# Life-habits-and-productivity
regression analysis about predictiing productivity of people
# Lifestyle Habits and Personal Productivity: A Machine Learning Analysis

## Project Overview
This project investigates the relationship between lifestyle habits and personal productivity using 30,000 simulated observations obtained from Kaggle. It explores how sleep patterns, stress levels, work habits, social media usage, and job satisfaction relate to actual productivity.

## Objectives
- Explore relationships between lifestyle factors and productivity.
- Handle missing values and assess data quality.
- Identify influential predictors using statistical analysis and feature importance.
- Compare regression and machine learning models.
- Select a model balancing predictive performance and interpretability.

## Methodology
- **Data preprocessing:** Data quality assessment, outlier detection, and missing-value imputation using Median, MICE, MissForest, Bayesian MICE, KNN, and Predictive Mean Matching (PMM).
- **Exploratory analysis:** Mutual Information, correlation analysis, feature binning, interaction effects, and nonlinear relationship checks.
- **Clustering:** K-Prototypes and DBSCAN to investigate potential behavioral groups.
- **Modeling:** Linear Regression, Ridge, Lasso, Elastic Net, KNN, Random Forest, Gradient Boosting, XGBoost, LightGBM, CatBoost, and Generalized Additive Models (GAM).
- **Evaluation:** Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²).

## Key Findings
- Job satisfaction was the strongest predictive feature identified.
- Most other lifestyle variables showed relatively weak predictive relationships with productivity.
- Clustering did not meaningfully improve predictive performance.
- The tuned GAM achieved the best reported test performance, with an R² of **0.6529**, MAE of **0.8241**, and RMSE of **1.1181**.
- CatBoost also achieved competitive predictive performance.

## Technologies Used
Python · Pandas · NumPy · Scikit-learn · CatBoost · XGBoost · LightGBM · Matplotlib · Seaborn

## Dataset
The dataset contains 30,000 simulated observations representing lifestyle habits, behavioral characteristics, job satisfaction, and productivity. The target variable is `actual_productivity_score`.

## Project Files
This repository contains the analysis notebooks, data preprocessing workflows, model comparisons, visualizations, and project report.

Note: Since the dataset is simulated, the findings should not be interpreted as causal conclusions about real-world productivity.
This repository contains the analysis notebooks, data preprocessing workflows, model comparisons, visualizations, and project report.

**Note:** Since the dataset is simulated, the findings should not be interpreted as causal conclusions about real-world productivity.
