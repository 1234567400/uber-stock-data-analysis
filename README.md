# Uber Stock Price Analysis & Forecasting (BDA Final Project)

## Project Overview
This project focuses on a comprehensive financial data analysis and time-series forecasting study of **Uber Technologies, Inc. (NYSE: UBER)** spanning a five-year period from January 2020 to January 2025. By leveraging Python and quantitative financial techniques, the project cleans, visualizes, and models stock behavior to derive actionable market insights.

## Key Features & Workflow
1. **Data Collection**: Real-time programmatic extraction of daily historical stock metrics (Open, High, Low, Close, Volume) using the `yfinance` API.
2. **Data Processing & EDA**: Statistical summarization, cleaning, and structural assessment using `pandas` and `numpy`.
3. **Data Visualization**: Trend analysis and volatility plotting using `matplotlib`.
4. **Time Series Modeling**: Statistical forecasting using ARIMA models, alongside an evaluative analysis of linear vs. non-linear assumptions in highly volatile financial markets.

## Technologies Used
- **Language**: Python
- **Libraries**: `yfinance`, `pandas`, `numpy`, `matplotlib`

## Key Insights & Discussion
The analysis evaluates the strengths and boundaries of classic autoregressive models like ARIMA in modern tech equity environments. It addresses real-world constraints such as:
- **Linearity vs. Market Dynamics**: Accounting for non-linear shifts driven by macroeconomic factors.
- **External Variables**: Discussing how news cycles, interest rates, and earnings releases impact structural price jumps beyond pure lag historical data.
- **Volatility Clustering**: Evaluating structural alternatives like GARCH for periods of high market turbulence.

