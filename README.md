🏡 Linear Regression: Airbnb Price Prediction (Winter 2024)
📌 Project Overview
This project focuses on predicting Airbnb rental prices using Linear Regression. By analyzing various factors such as location, number of rooms,
Amenities, and reviews, we build a regression model to estimate the price of Airbnb listings.

🚀 Key Features
Data Cleaning & Preprocessing: Handled missing values, outliers, and feature engineering.

Exploratory Data Analysis (EDA): Visualized price distributions, correlations, and feature importance.

Model Development: Implemented Multiple Linear Regression to predict prices.

Performance Evaluation: Used R² score, MAE, MSE, and RMSE to assess model accuracy.

🛠️ Tech Stack
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

📊 Results
The model achieved an R² score of XX%, indicating its effectiveness in predicting Airbnb prices.

📊 Exploratory Data Analysis (EDA)
Visualizations:

Distribution of prices across different locations

Correlation heatmap to identify significant predictors

Box plots to analyze price variations by room type and neighborhood

Key Findings:

Prices are higher for entire homes/apartments than for shared spaces.

Locations in city centers or tourist hotspots tend to have higher prices.

Number of reviews has an inverse relationship with price—more affordable listings receive more reviews.

🏗️ Model Development
Implemented Model: Multiple Linear Regression

Feature Selection: Used correlation analysis and p-values to choose the most significant predictors.

Performance Metrics:

R² Score: XX% (indicating how well the model explains price variations)

Mean Absolute Error (MAE): XX

Root Mean Squared Error (RMSE): XX

🔬 Insights & Improvements
Feature Engineering: Adding categorical encoding for room types and locations improved the model.

Regularization (Lasso/Ridge): Helped reduce overfitting and improved generalization.

Future Enhancements:

Experimenting with Polynomial Regression to capture non-linear relationships.

Using Decision Trees / Random Forest for better accuracy.

Deploying as a Flask/FastAPI web app for interactive price prediction.

🔗 Future Improvements
Exploring Polynomial Regression for better accuracy.

Applying Feature Selection & Regularization (Lasso/Ridge) to improve performance.

Extending the model with Machine Learning (Random Forest, XGBoost) for enhanced predictions.
