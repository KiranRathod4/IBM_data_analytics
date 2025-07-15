# IBM_data_analytics

IBM HR Employee Attrition Analysis
Project Overview

This project aims to analyze the factors influencing employee attrition at IBM. Using the provided dataset, we explore various employee attributes and train a machine learning model to predict attrition and identify key factors contributing to it.
Steps Taken

    Setup: Installed necessary libraries including pandas, numpy, matplotlib, seaborn, and scikit-learn.
    
    Data Loading & Initial Exploration: Loaded the WA_Fn-UseC_-HR-Employee-Attrition.csv dataset and performed initial data inspection using head() and info().
    
    Feature Engineering: Dropped irrelevant columns (EmployeeNumber, StandardHours, Over18, EmployeeCount) and converted categorical features into numerical representations using one-hot encoding.
    
    Train-Test Split: Split the data into training and testing sets (80/20 split) for model development and evaluation, using stratification to maintain the proportion of attrition in both sets.
    
    Model Training & Evaluation: Trained a RandomForestClassifier model on the processed data. Evaluated the model's performance using a confusion matrix and classification report.
    
    Feature Importance & Insights: Calculated and visualized the top 15 most important features influencing employee attrition based on the trained RandomForest model.

Files

    WA_Fn-UseC_-HR-Employee-Attrition.csv: The dataset used for this analysis.
    This notebook: Contains the code and analysis steps.

Conclusion

Based on the analysis, the Random Forest model was trained and evaluated, revealing the top 15 features influencing employee attrition through their importance scores. Further analysis can be done to understand the relationship of these features with attrition and propose strategies to mitigate it.
