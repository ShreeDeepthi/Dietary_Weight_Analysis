Overview

This project presents an Explainable AI (XAI)-driven regression framework designed to analyze and predict human body weight using dietary, lifestyle, and physiological factors.
The study leverages machine learning regression models combined with interpretability techniques to ensure transparency, reliability, and real-world applicability in healthcare and personalized nutrition systems.

Authors

S. Vairachilai
School of Computer Science & Artificial Intelligence
SR University, Warangal, Telangana – 506371, India
vairachilai@sru.edu.in

Addagudi Shruthi
School of Computer Science & Artificial Intelligence
SR University, Warangal, Telangana – 506371, India
shruthiaddagudi046@gmail.com

Abstract

The complex interactions between diet, sleep, stress, metabolism, and behavioral factors make accurate weight prediction a challenging task. While traditional calorie-based models lack flexibility, machine learning offers data-driven alternatives—yet often lacks interpretability.

This project introduces an Explainable Machine Learning (XAI) regression pipeline using a publicly available Comprehensive Weight Change Prediction Dataset. The dataset includes demographic, dietary, lifestyle, physical activity, and baseline weight attributes.

Multiple regression models were evaluated using metrics such as MAE, MSE, RMSE, and R², along with residual and learning curve analysis. To ensure interpretability, SHAP, LIME, PDP, and ICE techniques were applied to uncover feature importance and behavioral influence.

Among all models, Lasso Regression demonstrated superior performance, achieving:

RMSE: 0.0213

High R² score, indicating strong predictive reliability

The findings confirm that lightweight, regularized, and explainable models can provide clinically meaningful insights, supporting personalized nutrition and digital healthcare systems.

Key Features

Explainable AI–based regression framework

Robust preprocessing pipeline

Multiple regression models comparison

Transparent model interpretation using XAI

Clinically meaningful insights for health analytics

Machine Learning Models Used

Linear Regression

Ridge Regression

Lasso Regression (Best Performing)

ElasticNet

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Explainability Techniques (XAI)

SHAP (SHapley Additive exPlanations)

LIME (Local Interpretable Model-Agnostic Explanations)

Partial Dependence Plots (PDP)

Individual Conditional Expectation (ICE)

These techniques help identify:

Impact of caloric intake

Macronutrient influence

Sleep quality contribution

Stress and behavioral effects

Dataset

Source: Publicly available Comprehensive Weight Change Prediction Dataset

Features include:

Demographics

Dietary intake

Lifestyle habits

Physical activity

Baseline weight

Methodology

Data Cleaning & Imputation

Feature Encoding & Normalization

Train–Test Split (80/20)

Model Training & Evaluation

Interpretability using XAI tools

Comparative Performance Analysis

Evaluation Metrics

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Residual Analysis

Key Findings

Baseline weight, caloric intake, sleep quality, and stress were the strongest predictors.

Lasso Regression achieved optimal balance between accuracy and interpretability.

XAI significantly improved trust and transparency in predictions.

The framework is suitable for personalized nutrition systems and digital healthcare applications.

Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Explainability: SHAP, LIME

Environment: Google Colab / Jupyter Notebook

Future Enhancements

Integration with wearable health data

Real-time prediction dashboards

Deep learning–based hybrid models

Deployment using cloud-based ML services

Conclusion

This project demonstrates how explainable machine learning can bridge the gap between predictive performance and interpretability in healthcare. The proposed framework provides a scalable, transparent, and clinically meaningful solution for personalized weight prediction.

License

This project is intended for academic and research purposes only.
