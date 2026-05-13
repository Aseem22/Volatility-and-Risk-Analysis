# Volatility-and-Risk-Analysis

This project focuses on forecasting market volatility and estimating financial risk for the S&P 500 using Python-based financial econometric models.

The notebook implements:
- EWMA volatility model
- GARCH(1,1) model
- 95% and 99% Value at Risk (VaR)
- Basic VaR backtesting
- Volatility comparison during stressed market conditions

---

## Workflow

### 1. Data Collection
Historical S&P 500 data was downloaded using Yahoo Finance.

### 2. Return Calculation
Daily log returns were calculated for volatility modeling and risk analysis.

### 3. Volatility Modeling
Implemented:
- EWMA model
- GARCH(1,1) model

to estimate conditional volatility over time.

### 4. Value at Risk (VaR)
Estimated:
- 95% VaR
- 99% VaR

using volatility forecasts from both models.

### 5. Backtesting
Performed basic VaR backtesting by comparing expected and actual VaR violations.

### 6. Market Stress Analysis
Compared EWMA and GARCH model behavior during periods of elevated market volatility, including the COVID-19 market crash.

---

# Results & Visualizations

## S&P 500 Price Data

<img width="994" height="451" alt="image" src="https://github.com/user-attachments/assets/19bad181-f1d2-4f08-b1d7-d674ec23bcfe" />

---

## S&P 500 Log Return Data

<img width="988" height="451" alt="image" src="https://github.com/user-attachments/assets/fe02abff-bf47-48e8-9d49-62dbbbb8bd3f" />

---

## Volatility Clustering

<img width="968" height="451" alt="image" src="https://github.com/user-attachments/assets/a0ec107a-c542-4955-93b0-dbbaa5bb8e1b" />


---

## EWMA vs GARCH Volatility

<img width="968" height="451" alt="image" src="https://github.com/user-attachments/assets/b2036eb7-8233-40f9-b0ae-db5e32ab9311" />


---

## VaR Backtesting

<img width="1008" height="547" alt="image" src="https://github.com/user-attachments/assets/f0ab8e23-7bd3-4cdd-bc64-51173fa37292" />


---

