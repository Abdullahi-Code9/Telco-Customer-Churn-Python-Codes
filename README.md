**📊 Customer Churn Prediction & Revenue Impact**

This project analyzes customer churn, builds predictive models, and visualizes lost revenue using Python (scikit-learn, XGBoost) and Tableau Public.

**🚀 Project Overview**

Customer churn is a major cost driver in subscription-based businesses. The goal of this project is to:

    1. Understand churn patterns through exploratory data analysis (EDA).

    2. Build predictive models to identify customers at high risk of churn.

    3. Estimate revenue impact from churn and visualize insights with an interactive dashboard.

**🛠️ Tech Stack**

    1. **Python:** pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost

    2. **SQL:** basic queries for data cleaning & exploration

    3. **Tableau:** interactive dashboard for churn & lost revenue

**📈 Key Results**

    1. Logistic Regression: Recall = 0.53 (AUC = 0.85)
  
    2. Random Forest: Recall = 0.50 (AUC = 0.84)

    3. XGBoost: Recall = 0.67 (AUC = 0.82) → Best performer

    4. Adjusting threshold (0.63) improved recall to 0.74 at a tradeoff with precision.

    5. Tableau dashboard shows 27% lost revenue risk concentrated in specific customer segments.

**📊 Deliverables**

       EDA Notebook (data exploration & churn patterns)

       Machine Learning Models (Logistic Regression, Random Forest, XGBoost)

       Evaluation Metrics (Confusion Matrices, ROC & PR Curves)

       Tableau Dashboard (interactive churn & revenue analysis)

**🔗 Resources**

    🐍 Python Code (GitHub Repo) → (You are here)

    📊 Interactive Dashboard (Tableau Public) → [View Dashboard]([url](https://public.tableau.com/app/profile/abdullahi.abubakar.sadiq/vizzes))

**📌 Recommendations**

    1. Target at-risk customers early (XGBoost flags 74% of churners with adjusted threshold).

    2. Focus retention campaigns on high-revenue segments identified in the dashboard.

    3. Use churn predictions as inputs for personalized offers & loyalty programs.
