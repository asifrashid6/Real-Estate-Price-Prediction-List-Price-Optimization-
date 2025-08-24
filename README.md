🏡 Real Estate Analytics – Chicago Housing Market
📌 Overview

This project explores the Chicago housing market using regression and classification models to predict housing prices and optimize listing strategies. By combining data preprocessing, feature engineering, and machine learning, we demonstrate how analytics can guide price prediction and list price optimization.

📊 Data & Preprocessing

Cleaned and structured housing data including features such as:

Square Feet, Bedrooms, Bathrooms, Lot Size, Year Built

Zip Code, Walk/Transit/Bike Scores

Neighborhood Ratings

Engineered new variables:

Days_on_Market (time between listing and sale)

Sell_Fast (binary target: 1 if faster than 70% of listings, else 0)

🔎 Methods
1. Regression Models (Price Prediction)

Simple Linear Regression: Used square footage to predict house prices.

Multiple Linear Regression: Added bedrooms, bathrooms, and other features.

Extended Model: Incorporated property type, lot size, year built, neighborhood, and walkability scores.

📈 Result: R² = 0.51 → ~51% of variation in housing prices explained.

2. Classification Models (List Price Optimization)

Defined Sell_Fast to classify fast vs. slow selling properties.

Built Logistic Regression and Decision Tree models.

Decision Tree selected as best performer (~71% accuracy).

Identified ~$19,500 as the key threshold where homes are more likely to sell quickly.

⚠️ Challenge: Class imbalance (518 fast sells vs. 208 slow sells).

Addressed using resampling techniques and feature scaling.

✅ Key Results

Regression models provided reliable price estimates with moderate accuracy.

Classification models achieved 71% accuracy in predicting fast-sell outcomes.

Decision Tree revealed pricing thresholds critical for list price strategies.

🚀 Next Steps

Incorporate additional data (e.g., school ratings, crime rates, economic indicators).

Test advanced models (Random Forest, Gradient Boosting, XGBoost).

Deploy a pricing recommendation tool for real estate professionals.

🛠️ Tech Stack

Languages: Python (Pandas, NumPy, Scikit-learn)

Visualization: Matplotlib, Seaborn

Modeling: Linear Regression, Logistic Regression, Decision Trees
