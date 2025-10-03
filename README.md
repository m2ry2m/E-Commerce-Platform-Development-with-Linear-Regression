E-Commerce Platform Development with Linear Regression
A simple machine learning project applying Linear Regression to predict yearly customer spending for an e-commerce clothing company.
Project Overview
The company operates in New York City, selling clothing through:
- Online platforms (mobile app, website)
- In-store style sessions with personal stylists

Business Question:
Should the company focus more on improving the mobile app or the website experience?

Using EDA, Linear Regression, and evaluation metrics, we determine which platform contributes more to yearly customer spending.
Dataset
Includes customer information such as:
- Avg. Session Length
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent (Target)
Workflow
1. Exploratory Data Analysis (EDA)
   - Scatterplots, jointplots, heatmaps
   - Correlation analysis
2. Modeling
   - Train-test split
   - Multiple Linear Regression with Scikit-learn
   - Coefficient analysis for feature importance
3. Evaluation
   - Residual analysis
   - Metrics: MAE, MSE, RMSE, R²
Technologies
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Key Findings
- Time on App has a stronger impact on yearly spending compared to Time on Website.
- Model achieved a high R² score, indicating a strong fit.
- Recommendation: Prioritize improving the mobile app experience
