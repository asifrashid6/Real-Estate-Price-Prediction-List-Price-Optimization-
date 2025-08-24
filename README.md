Real Estate Analytics – Chicago Housing Market

This project applied regression and classification models to analyze and predict housing prices in Chicago, IL.

Regression Models:

Built a simple linear regression using square footage to predict housing prices.

Extended to a multiple linear regression with features such as bedrooms, bathrooms, and square footage, achieving an R² of 0.51.

Further improved the model by incorporating property type, lot size, year built, zip code, and neighborhood scores.

Classification Models (List Price Optimization):

Engineered a binary variable Sell Fast (1 if property sold faster than 70% of listings).

Tested logistic regression and decision trees; selected the Decision Tree model, which identified ~$19,500 as the key threshold influencing fast sales.

Addressed class imbalance in the dataset (518 fast sells vs. 208 slow sells) with resampling and feature engineering.

Key Results:

Regression models explained ~51% of price variation.

Classification achieved ~71% accuracy in predicting “fast sell” outcomes.

This project demonstrates the use of data preprocessing, feature engineering, and supervised machine learning for real estate analytics.
