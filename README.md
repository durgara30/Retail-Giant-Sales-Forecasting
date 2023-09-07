# Retail-Giant-Sales-Forecasting
 Predicting the product sales for the upcoming six months is essential for Global Mart, a sizable international e-commerce platform. This sales projection holds significant importance as it enables effective inventory management and provides valuable insights for well-informed business strategies.
 
To identify the most consistently profitable market segment, we will employ the coefficient of variation (CoV), which measures the relative variability of data compared to its mean. This analysis is structured into two primary problem statements:

# Project Objective I I - Data Preparation:
In this phase, we focus on data preprocessing and identifying the most profitable market segment:

Identify 21 unique market segments.
Calculate the CoV for each market segment.
Determine the most profitable market segment based on CoV values.
Convert the order date into a standardized month-year format and construct a time series dataset by combining market and segment data. This dataset is then split into training and test sets, with the test data spanning a six-month period.

# Project Objective II - Model Building & Evaluation:
After pinpointing the most profitable market segment, our next objective is to forecast sales and quantity for that segment using suitable techniques:

Examine sales variations within the chosen market segment, considering trends and seasonality.
Apply smoothing techniques, including:
Simple exponential smoothing
Holt's exponential smoothing
Holt-Winters' exponential smoothing (both additive and multiplicative approaches)
Compare forecasted values with actual values, computing the Mean Absolute Percentage Error (MAPE) for each technique.
Implement various ARIMA models (with parameters p=1, q=1, d=1):
AR model
MA model
ARMA model
ARIMA model
ARIMAX model (incorporating exogenous variables)
SARIMA model
SARIMAX model (factoring in exogenous variables)
Once again, compare forecasted values with actual values and calculate the MAPE for each technique.
Repeat the preceding steps for quantity forecasting within the same market segment utilized for sales forecasting.

# Insights:
Following analysis, the Seasonal AutoRegressive Integrated Moving Average (SARIMA) model stands out as the most accurate, yielding a Root Mean Square Error (RMSE) of 9617.98 and a Mean Absolute Percentage Error (MAPE) of 12.88. These metrics underscore the SARIMA model's precision in predicting sales for the forthcoming six months.

For a comprehensive reference, encompassing CoV values, forecasting methodologies, trends, and insights, please consult the provided Jupyter notebook or presentation materials.





