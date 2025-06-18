# Silent-Churn-Detection-and-Explainable-AI-in-Customer-Retention
Customer Churn Prediction – Explainable Machine Learning Project

This project focuses on predicting customer churn using machine learning techniques while addressing real-world business challenges such as silent churn, lack of sentiment data, and model interpretability.

Problem Statement
Customer churn is a critical problem for subscription-based businesses. Understanding which customers are likely to leave, especially the ones who stop engaging silently (silent churners), is essential for retention strategies.

Key Challenges Addressed
Lack of Sentiment Data: Incorporated proxy features (usage frequency, complaints) and sentiment analysis to approximate customer satisfaction.
Silent Churn Detection: Engineered features such as `days_since_last_visit` to identify disengaged users who haven’t canceled explicitly.
Explainability: Used SHAP and LIME to interpret model predictions and enhance trust among business stakeholders.

Tools & Technologies
Languages/Libraries: Python, Scikit-learn, Pandas, Matplotlib, Seaborn, NLTK
Models UsedLogistic Regression, Random Forest, XGBoost, LightGBM
Explainability: SHAP (SHapley Additive Explanations), LIME
Imbalanced Learning: SMOTE (Synthetic Minority Over-sampling Technique)

Workflow Overview
1. Data Preprocessing:
    - Handled missing and categorical data.
    - Engineered features like `days_since_joining` and `days_since_last_visit`.
2. Class Balancing:
    - Applied SMOTE to handle class imbalance.
3. Model Training & Evaluation:
    - Trained multiple models and compared using accuracy, precision, recall, and ROC-AUC.
4. Explainability:
    - Visualized feature impact using SHAP and LIME plots.
5. Visualization:
    - Displayed class distributions and model outputs using Matplotlib & Seaborn.

Sample Visuals
- Class distribution before and after SMOTE
- SHAP summary plot and force plots (for individual predictions)

Results
- Achieved reliable churn predictions with explainable outputs.
- Identified high-risk segments and their contributing factors.

No Frontend
This is a backend-only machine learning project. All work was carried out in Python via Jupyter Notebook.

*For more details, please refer to the notebook file!
