# Iron-Ore-Price-Prediction

# Project Overview
This project focuses on predicting the future prices of iron ore using machine learning techniques. The aim was to develop a reliable model that could assist in understanding price trends and making informed decisions in the commodities market. The primary models used in this project were XGBoost and Linear Regression, with significant performance improvements achieved through optimization of the XGBoost model.

# Objectives
To predict iron ore prices based on historical data.
To improve model performance by optimizing hyperparameters and applying effective data preprocessing techniques.
To compare the performance of different machine learning algorithms.

# Key Features
Models Used: Linear Regression and XGBoost.
Performance Improvement: R² score improved from 65% to 89% through XGBoost optimization.
Tools & Libraries: Python, Pandas, Scikit-learn, XGBoost, Matplotlib, NumPy.
Data Preprocessing
Handling Missing Values: Filled missing data points using statistical techniques such as mean and median imputation.
Feature Engineering: Created new features such as moving averages and lags to capture price trends and seasonality.
Outlier Detection and Removal: Identified and removed data points with abnormal price fluctuations using Z-scores and IQR methods.
Data Normalization: Applied Min-Max scaling to ensure the features were on a similar scale, improving model convergence.

# Model Building and Optimization
Linear Regression: Initially implemented a simple linear regression model to establish a baseline for prediction accuracy.
XGBoost: Used the XGBoost algorithm to capture non-linear patterns in the data. Performed hyperparameter tuning using grid search and cross-validation to enhance model performance.
Hyperparameters Tuned:
Learning rate
Max depth
Number of estimators
Subsample ratio
Resulted in a significant improvement in R² score from 65% to 89%.

# Evaluation Metrics
R² Score: Used as the primary evaluation metric to measure the proportion of variance in iron ore prices explained by the model.
Mean Absolute Error (MAE) and Mean Squared Error (MSE) were also calculated to assess model performance.
Key Insights
The XGBoost model outperformed Linear Regression, demonstrating the importance of non-linear algorithms for capturing complex patterns in the data.
Feature engineering played a critical role in improving model accuracy, especially the use of lagged features and moving averages.

# Results
The optimized XGBoost model achieved an R² score of 89%, significantly outperforming the initial Linear Regression model, which had an R² score of 65%.
The model can effectively predict iron ore prices, providing valuable insights for market forecasting and decision-making.

# Future Work
Explore additional machine learning models such as Random Forest and LSTM for time series analysis.
Incorporate more advanced techniques for feature selection and dimensionality reduction, such as Principal Component Analysis (PCA).
Integrate external factors such as economic indicators and market sentiment data to enhance prediction accuracy.
