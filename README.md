Introduction:

Brief description of the project, explaining that it involves sales forecasting using various statistical and machine learning techniques.

Dataset Overview:

Information about the dataset used (e.g., columns like Order Date, Sales, Profit, etc.).
Brief description of the data preprocessing steps, such as handling missing values, duplicates, and outliers.

Data Preprocessing:

Conversion of date columns (Order Date, Ship Date) to datetime format.
Feature extraction (e.g., year, month, weekday from Order Date).
Calculation of Shipping Lead Time.

Exploratory Data Analysis (EDA):

Visualizations such as sales distribution, sales vs profit, sales by category, region, discount, and ship mode.
Outlier detection using box plots and histograms.

Sales Forecasting:

List of forecasting methods used:
Naive Method
Simple Average Method
Simple Moving Average (SMA) Method
Exponential Smoothing
Holt's Exponential Smoothing (with trend)
Holt-Winters (Additive and Multiplicative)
Model Evaluation:

Comparison of models based on RMSE and MAPE.
Conclusion that Simple Average performed best in terms of RMSE and MAPE, but higher MAPE values indicate room for improvement.

Libraries Used:
numpy, pandas, matplotlib, seaborn, plotly, statsmodels, etc.

