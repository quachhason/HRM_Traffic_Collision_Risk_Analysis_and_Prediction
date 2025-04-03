# HRM Traffic Collision Risk Analysis & Prediction

[![Project Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)](https://github.com/quachhason/HRM_Traffic_Collision_Risk_Analysis_and_Prediction)

## Overview

This project focuses on analyzing and predicting traffic collision risk within the Halifax Regional Municipality (HRM).  By leveraging machine learning techniques, the project aims to identify key factors contributing to traffic collisions and develop models to forecast collision risk levels.  This analysis provides valuable insights for urban planning, traffic safety initiatives, and resource allocation to reduce traffic incidents.

[Link Tableau Public Dasboard](https://public.tableau.com/app/profile/sonquach/viz/HalifaxTrafficCollisionsPatternsandInsights2018-2024/Dashboard1)

## Key Features

*   **Risk Factor Analysis:** Identification of significant factors influencing traffic collision severity using Random Forest classification and feature importance analysis.
*   **Categorical Feature Importance:**  Focus on the impact of categorical variables (road conditions, light conditions, etc.) on collision severity for stakeholder understanding.
*   **Risk Score Forecasting:** Development of a Random Forest Regressor and SARIMA model to forecast monthly traffic collision risk scores.
*   **Comparative Model Evaluation:**  Benchmarking of Random Forest Regressor against SARIMA for time-series forecasting, providing insights into model selection based on performance metrics (MAE, RMSE).
*   **Visualizations:**  Includes confusion matrices, feature importance charts, and time-series plots of actual vs. predicted risk scores and forecasted risk scores.

## Technologies Used

*   **Python:** Primary programming language for data analysis, preprocessing, modeling, and evaluation.
*   **Pandas:** Data manipulation and analysis.
*   **NumPy:** Numerical computing.
*   **Scikit-learn:** Machine learning algorithms (Random Forest), model evaluation metrics, and data splitting.
*   **Statsmodels:** SARIMA time-series modeling.
*   **Matplotlib & Seaborn:** Data visualization.
*   **Google Colab:** Cloud-based environment for development and execution.
*   **Tableau:** Main descriptive analysis and Visualization Dashboard.

## Data Sources

*   **Processed Traffic Collision Data:**  Dataset used for analysis (likely derived from public HRM data sources, specify if possible).  *(**Note:** In your actual README, please add details about the specific data source if it's publicly available or if you can provide a general description without violating any data privacy rules.)*

## Methodology

1.  **Data Preparation:** Loading, cleaning, and preprocessing of traffic collision data. Encoding categorical features and handling missing values.
2.  **Classification Model (Random Forest):** Training a Random Forest Classifier to predict Collision Severity, incorporating class weights to address class imbalance.
3.  **Risk Score Calculation:** Defining and calculating a Risk Score based on Collision Severity.
4.  **Forecasting Models (Random Forest Regressor & SARIMA):**
    *   Random Forest Regressor:  Utilizing lagged and rolling features for monthly Risk Score forecasting.
    *   SARIMA Model: Applying SARIMA for time-series forecasting of monthly Risk Scores.
5.  **Model Evaluation:**  Evaluating classification and regression models using relevant metrics (Classification Report, Confusion Matrix, MAE, RMSE).
6.  **Feature Importance Analysis:** Determining and visualizing key factors influencing Collision Severity.

## Key Findings

*   Random Forest Classifier demonstrates effective performance in predicting Collision Severity, particularly with class weights to address imbalanced classes.
*   Categorical features related to road and environmental conditions are significant predictors of collision severity.
*   Random Forest Regressor and SARIMA models provide different approaches to forecasting monthly traffic collision risk scores, with Random Forest showing slightly better performance based on MAE and RMSE in this specific context.

## Repository Contents

*   `Notebooks`: Jupyter Notebook containing the main code for data analysis, classification, regression, and forecasting.
*   `data`:  Original dataset and processed dataset.
*   `README.md`: This README file.

## How to Run

1.  Open `Processing & EDA.ipynb` in Google Colab or Jupyter Notebook.
2.  Ensure the `Traffic_Collision.csv (file raw)`or `Processed_Traffic_Collision.csv` file is accessible in the specified path within the notebook or adjust the file path accordingly.
3.  Run the notebook cells sequentially to reproduce the analysis and models.

## Author

*   [Son Quach]
*   [My Contact Information](quachhason.96@gmail.com)
*   [LinkedIn Profile URL](https://www.linkedin.com/in/quachhason/)
