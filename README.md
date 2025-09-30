# E-Commerce-Platform-Development-with-Linear-Regression
A simple machine learning project applying Linear Regression to predict sales for an e-commerce platform

Project Overview:

This project analyzes customer behavior for an E-commerce clothing company based in New York City.
The company sells clothing both online (via mobile app and website) and offers in-store style sessions with personal stylists.

The main business question:
Should the company focus more on improving their mobile app or their website experience?

Using Exploratory Data Analysis (EDA), Linear Regression, and evaluation metrics, we identify which platform contributes more to yearly customer spending.

Dataset:

The dataset includes customer information such as:

Email

Address

Avg. Session Length

Time on App

Time on Website

Length of Membership

Yearly Amount Spent (Target Variable)

Project Workflow:

Exploratory Data Analysis (EDA)

Scatter plots, jointplots, and heatmaps to visualize relationships.

Correlation analysis to find the most predictive features.

Modeling with Linear Regression

Train-test split using train_test_split.

Fitting a Multiple Linear Regression model with Scikit-learn.

Analyzing model coefficients to understand feature importance.

Evaluation

Residuals Analysis to check normality and model assumptions.

Metrics used:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

RMSE (Root Mean Squared Error)

R² Score (Model performance)

Technologies Used:

Python 

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Key Insights:

Time on App had a stronger impact on Yearly Amount Spent than Time on Website.

The regression model achieved a high R² score, indicating a good fit.

Recommendation: The company should prioritize improving the mobile app experience.

Conclusion:

This project demonstrates how Linear Regression and evaluation metrics can guide business strategy.
The results show that the mobile app experience contributes more to customer spending than the website, providing actionable insights for resource allocation.
