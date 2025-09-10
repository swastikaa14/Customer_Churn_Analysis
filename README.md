Customer Churn Analysis

This project focuses on Customer Churn Analysis, a critical task for businesses in sectors like telecommunications, banking, and subscription services where customer retention is as important as acquisition. The objective is to analyze historical customer data, identify patterns leading to churn, and build predictive models that help businesses take proactive retention measures.Using Python, I performed data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning modeling (Logistic Regression, Random Forest, XGBoost) to predict the likelihood of churn. Key insights were derived using visualization libraries such as Matplotlib and Seaborn.Additionally, the results were integrated into Power BI, creating an interactive dashboard to track KPIs such as Churn Rate, Churned Customers, and Lost MRR. The dashboard allows stakeholders to monitor churn trends across customer segments (e.g., tenure bands, payment method, contract type) and make data-driven business decisions.

Project Workflow

1. Data Collection & Preparation
Imported the churn dataset.Cleaned missing values, standardized data types, and engineered new features (e.g., tenure bands, Lost MRR).

2. Exploratory Data Analysis (EDA)
Analyzed churn distribution across demographics, contracts, and payment methods.Created visualizations (heatmaps, bar charts, histograms) to identify correlations.

3. Feature Engineering & Modeling
Applied encoding and scaling techniques.Trained ML models (Logistic Regression, Random Forest, XGBoost).Evaluated models using accuracy, precision, recall, F1-score, and ROC-AUC.

4. Prediction & Interpretation
Generated churn probability scores for each customer.Identified top drivers of churn using feature importance.

5. Business Intelligence Dashboard (Power BI)
Imported cleaned + scored dataset into Power BI.Built interactive visuals: Churn Rate, Total Customers, Lost MRR, churn trends by segments.Applied conditional formatting for KPIs.

6. Insights & Recommendations
Highlighted high-risk customer groups.Suggested retention strategies (contract upgrades, loyalty programs, targeted offers).

Tech Stack & Tools
Programming & Data Analysis: Python (Pandas, NumPy, Scikit-learn)
Visualization & EDA: Matplotlib, Seaborn
Machine Learning Models: Logistic Regression, Random Forest, XGBoost
Data Preprocessing: Label Encoding, Feature Scaling, Handling Missing Data
Business Intelligence: Power BI (Power Query, DAX, KPI Cards, Interactive Dashboards)
Version Control & Collaboration: Git, GitHub
Other Tools: Jupyter Notebook, Power BI Desktop

Key Insights & Results
Overall Churn Rate: ~26% of customers were identified as churned.
High-Risk Segments:
Month-to-month contracts showed the highest churn.
Customers paying via electronic check churned more often.
Customers with tenure < 12 months were most likely to leave.

Model Performance:
Best-performing model: XGBoost with ~82% accuracy and ROC-AUC ~0.85.
Logistic Regression was most interpretable, while ensemble methods captured complex patterns.
Business Impact Metrics (via Power BI Dashboard):
KPI Cards: Total Customers, Churned Customers, Churn Rate, Lost MRR.
Visuals showed churn patterns by tenure, contract type, and payment method.

Conditional formatting highlighted areas of highest churn risk.



These insights help businesses predict at-risk customers, prioritize retention strategies, and reduce potential revenue loss.
