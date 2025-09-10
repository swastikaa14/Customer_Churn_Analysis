Customer Churn Analysis

This project focuses on Customer Churn Analysis, a critical task for businesses in sectors like telecommunications, banking, and subscription services where customer retention is as important as acquisition. The objective is to analyze historical customer data, identify patterns leading to churn, and build predictive models that help businesses take proactive retention measures.Using Python, I performed data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning modeling (Logistic Regression, Random Forest, XGBoost) to predict the likelihood of churn. Key insights were derived using visualization libraries such as Matplotlib and Seaborn.

Project Workflow

1. Data Collection & Preparation
Imported the churn dataset.Cleaned missing values, standardized data types, and engineered new features (e.g., tenure bands, Lost MRR).

2. Exploratory Data Analysis (EDA)
Analyzed churn distribution across demographics, contracts, and payment methods.Created visualizations (heatmaps, bar charts, histograms) to identify correlations.

3. Feature Engineering & Modeling
Applied encoding and scaling techniques.Trained ML models (Logistic Regression, Random Forest, XGBoost).Evaluated models using accuracy, precision, recall, F1-score, and ROC-AUC.

4. Prediction & Interpretation
Generated churn probability scores for each customer.Identified top drivers of churn using feature importance.

Tech Stack & Tools
Programming & Data Analysis: Python (Pandas, NumPy, Scikit-learn)
Visualization & EDA: Matplotlib, Seaborn
Machine Learning Models: Logistic Regression, Random Forest, XGBoost
Data Preprocessing: Label Encoding, Feature Scaling, Handling Missing Data
Version Control & Collaboration: Git, GitHub
Other Tools: Jupyter Notebook

Key Insights & Results
Overall Churn Rate: ~26% of customers were identified as churned.
High-Risk Segments:
Month-to-month contracts showed the highest churn.
Customers paying via electronic check churned more often.
Customers with tenure < 12 months were most likely to leave.

Model Performance:
Best-performing model: XGBoost with ~82% accuracy and ROC-AUC ~0.85.
Logistic Regression was most interpretable, while ensemble methods captured complex patterns.
Conditional formatting highlighted areas of highest churn risk.
These insights help businesses predict at-risk customers, prioritize retention strategies, and reduce potential revenue loss.
