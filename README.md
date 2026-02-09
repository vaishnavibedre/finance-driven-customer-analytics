# E-Commerce Customer Analytics: Segmentation & Propensity Modeling
Integrating Financial Analysis with Machine Learning to Drive Marketing ROI
This project utilizes K-Means clustering for portfolio-style customer segmentation and Random Forest classification to predict high-value propensity. Includes hyperparameter tuning and feature importance analysis to drive data-driven business strategy.

Project Overview
This project applies unsupervised and supervised machine learning to an e-commerce dataset to identify high-value customer segments and predict future purchasing behavior. Leveraging my background in Finance, I treated customer acquisition and retention as a capital allocation problem, focusing on maximizing the "Return on Ad Spend" (ROAS) through precise targeting.

Key Objectives:
Portfolio Segmentation: Use K-Means clustering to categorize customers based on transaction velocity and spend magnitude.

Predictive Modeling: Build a classification pipeline to identify "High-Value Customers" before they reach peak spend.

Financial Optimization: Analyze feature importance to understand which metrics (e.g., discount sensitivity) most impact the bottom line.

Technical Stack
Language: Python

Libraries: Pandas, NumPy (Data Engineering); Matplotlib, Seaborn (Visual Analytics); Scikit-Learn (Machine Learning & Scaling).

Financial Metrics: Margin Analysis, Spend-per-Visit, Discount Sensitivity.

Workflow & Methodology

1. Exploratory Data Analysis (EDA) & Data Integrity
Handled missing values and duplicates to ensure "Clean Ledger" data.
Financial Insight: Analyzed total_spend distributions and membership_type variance to identify revenue concentration.

2. Customer Segmentation (Unsupervised Learning)
Applied StandardScaler to normalize features, ensuring age and spend were weighted equally.
Utilized the Elbow Method (WCSS) to determine the optimal cluster count.
Segment Profiling: Identified specific cohorts, such as "High-Velocity/Low-Margin" (frequent visitors using heavy discounts) vs. "Loyalists."

3. Predictive Propensity Model
Feature Engineering: Developed custom metrics like discount_percentage to measure price elasticity.
Model Selection: Implemented Random Forest to handle non-linear relationships between demographics and spend.
Optimization: Conducted GridSearchCV for hyperparameter tuning, focusing on the F1-Score to balance precision and recall—critical for minimizing "Wasted Marketing Spend."
