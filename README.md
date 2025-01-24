# Gold-Price-Analysis-and-Prediction-Using-Statistical-and-Machine-Learning-Models
Objective:
The project aims to analyze the dynamics of gold prices and build predictive models using regression analysis, ARIMA, and statistical methods to understand factors influencing gold prices and forecast future trends. This includes investigating the price elasticity of gold, identifying major event impacts, and deriving actionable insights using advanced visualization and statistical techniques.

Scope of the Project:
Data Analysis and Preprocessing:

Loading and cleaning historical gold price data (Excel sheet).
Converting date formats and performing necessary data transformations.
Price Elasticity of Demand:

Calculating the price elasticity of gold based on European market data.
Testing the significance of price elasticity and determining its impact on volume changes.
Granger Causality Test:

Performing Granger Causality to analyze the relationship between the opening price of Standard & Poor's index (SP_open) and gold prices (EU_Price).
Impact of Major Events:

Investigating the effect of specific historical events on gold prices.
Conducting linear regression to test the impact and derive statistical conclusions.
Principal Component Analysis (PCA):

Applying PCA to analyze the variance explained by features such as SP_open, DJ_open, and others.
Visualizing the contribution of the principal components.
Seasonal Decomposition:

Using time series decomposition to extract seasonal patterns in gold prices.
Identifying whether seasonality significantly impacts gold price trends.
Predictive Modeling:

Building regression models to predict gold closing prices based on historical factors such as opening prices, high, low, and volume.
Evaluating model performance using error metrics (MAE, MSE, RMSE).
Goodness-of-Fit Testing:

Conducting chi-square tests to validate the distribution of predicted gold prices.
Currency Conversion and Visualization:

Adding USD equivalent prices based on exchange rates.
Plotting EU vs. USD price trends over time.
Advanced Predictive Modeling:

Building ARIMA models to forecast gold prices over a specific horizon.
Comparing ARIMA results with linear regression models to identify the best forecasting approach.
Visualization:

Using ggplot2 to create detailed plots for actual vs. predicted prices.
Comparing historical trends, linear regression predictions, and ARIMA forecasts.
Technologies and Libraries Used:
Languages: R
Libraries:
Data handling: openxlsx, dplyr
Statistical analysis: forecast, lmtest
Visualization: ggplot2
Time series modeling: auto.arima, forecast
Key Insights:
Price elasticity analysis reveals how changes in volume affect gold prices.
Granger causality establishes whether external factors (like S&P index) influence gold price movements.
PCA highlights key market variables contributing to price variability.
Seasonal decomposition uncovers predictable patterns in gold pricing.
Predictive models help accurately forecast future trends, aiding in decision-making for investments.
Expected Outcomes:
Statistical understanding of the factors influencing gold prices.
Accurate forecasting models for short-term price prediction.
Insights into the historical impact of events on gold pricing.
Comprehensive data visualization for clear communication of trends and predictions.
