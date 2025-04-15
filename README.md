# 📊 Stock Portfolio Optimization

## 🔍 Project Overview
This project explores the application of Modern Portfolio Theory to optimize a portfolio composed of selected technology and consumer stocks. It identifies the optimal asset allocation that maximizes return for a given level of risk using historical price data.

## Tools and Techniques Used
- **Programming Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` – data manipulation  
  - `matplotlib`, `seaborn` – visualization  
  - `scipy.optimize` – optimization  
- **Techniques:**  
  - Log returns & covariance matrix  
  - Monte Carlo simulation of portfolios  
  - Sharpe ratio maximization  
  - Efficient frontier plotting  
  - Portfolio optimization via `scipy.optimize.minimize`

## Key Insights
- Thousands of portfolios were simulated to visualize the risk-return trade-off.
- Optimal portfolio was identified by maximizing the Sharpe ratio, however there is a tradeoff where the high return comes with higher risk as expected.
- Diversification shown to improve risk-adjusted returns.

## Skills Demonstrated
- Financial data retrieval and preprocessing
- Quantitative analysis with return and volatility metrics
- Optimization techniques for real-world financial modeling
- Data visualization for risk-return interpretation
