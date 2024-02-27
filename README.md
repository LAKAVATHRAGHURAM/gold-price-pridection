# gold-price-pridection
The dataset encompasses key financial metrics for each trading day, including the opening and closing prices, trading volume, as well as the highest and lowest prices recorded during the day.

# Gold  Price Prediction
Overview

This project aims to predict the high price of gold stocks using machine learning techniques. 

We analyze historical data of gold stock prices to train several regression models and evaluate their performance in predicting the high price accurately.

# Dataset

The dataset used in this project is sourced from 'goldstock.csv', which contains various attributes such as 'Date', 'Low', 'High', 'Volume', 'Open', and 'Close' of gold stock prices over a period.

# Exploratory Data Analysis (EDA)

We performed exploratory data analysis to understand the distribution of features, detect outliers, and explore correlations among numeric attributes. The EDA included:

Visualizations of histograms, kernel density estimations, and box plots for each feature.

Heatmap to visualize the correlation matrix of numeric features.

# Data Preprocessing

We preprocessed the data by:

Converting the 'Date' column to datetime format.

Handling missing values.

Scaling numeric features using MinMaxScaler.

Selecting relevant features using SelectKBest.

# Model Selection and Evaluation

We trained several regression models including:

Linear Regression

KNearest Neighbors

Decision Tree

Bayesian Ridge

Elastic Net

Gradient Boosting

Huber

Support Vector Machine

XGBoost

Random Forest

Extra Tree

We evaluated the models using the R2 score metric and selected the best-performing model based on the test set.

# Hyperparameter Tuning
We applied hyperparameter tuning using RandomizedSearchCV to optimize the parameters of the Extra Trees Regressor, one of the best-performing models.

# Results
The performance of the models was evaluated based on the R2 score. The results are as follows:
# Accuracy:  99.95340472366145

# Baseline Model: 
Model after Hyperparameter Tuning: R2 score = [99.95]

# Conclusion
The project demonstrates the application of machine learning techniques in predicting gold stock prices. The optimized Extra Trees Regressor showed improved performance compared to the baseline model.
