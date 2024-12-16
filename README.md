# prophet-challenge
# Mercado Libre Growth Analysis

## Project Overview
As a growth analyst at Mercado Libre, Latin America's leading e-commerce platform with over 200 million users, you are tasked with using data analysis to drive company growth. This project focuses on investigating whether predictive analysis of Google search traffic can provide actionable insights for trading the company's stock. The analysis is broken into four key steps:

1. **Find unusual patterns in hourly Google search traffic.**
2. **Mine the search traffic data for seasonality.**
3. **Relate the search traffic to stock price patterns.**
4. **Create a time series model using Prophet.**

## Steps in Detail

### Step 1: Find Unusual Patterns in Hourly Google Search Traffic
The goal of this step is to identify anomalies or spikes in Google search trends that might correlate with changes in Mercado Libre's business or market performance. Tasks include:
- Aggregating hourly Google search traffic data.
- Using statistical techniques or visualization tools to highlight irregular patterns.
- Hypothesizing potential causes of these anomalies, such as marketing campaigns or external news events.

### Step 2: Mine the Search Traffic Data for Seasonality
Analyze the search traffic data for recurring patterns:
- Identify daily, weekly, or monthly trends.
- Use decomposition methods (e.g., additive or multiplicative) to separate the data into trend, seasonal, and residual components.
- Determine key seasonal factors influencing user interest in Mercado Libre.

### Step 3: Relate the Search Traffic to Stock Price Patterns
Explore whether variations in Google search traffic can explain or predict changes in Mercado Libre's stock price:
- Merge search traffic data with stock price data.
- Calculate correlations and perform lag analysis to find time delays between search interest and stock movements.
- Test for causality using statistical tests such as Granger causality.

### Step 4: Create a Time Series Model with Prophet
Develop a predictive model using the Prophet library to forecast future trends:
- Build and validate a time series model for Google search traffic.
- Incorporate external regressors, such as stock prices or macroeconomic indicators, if applicable.
- Use the model to make actionable predictions and assess its performance.

## Tools and Technologies
- **Python Libraries**: pandas, NumPy, matplotlib, seaborn, statsmodels, and scikit-learn.
- **Prophet**: A powerful library for time series forecasting.
- **Data Sources**: Google Trends, stock market data (e.g., Yahoo Finance or Alpha Vantage).

## Deliverables
1. **Visualizations**: Charts highlighting anomalies, seasonality, and correlations.
2. **Statistical Insights**: Summary of findings from pattern analysis and tests.
3. **Forecast Model**: A Prophet-based model to predict search traffic and its implications.
4. **Actionable Recommendations**: Insights on how search trends can be used to inform stock trading strategies or operational decisions.

## Conclusion
This project aims to demonstrate how analyzing and forecasting search traffic can yield strategic insights for Mercado Libre, from better understanding user behavior to potentially leveraging stock market opportunities.

## Acknowledgments

This project was developed with the assistance of ChatGPT, an AI language model created by OpenAI. The model helped in generating ideas, code snippets, and documentation to enhance the overall development process.
