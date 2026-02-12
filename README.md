# Portfolio Optimization & Efficient Frontier (Python)

This project applies **Modern Portfolio Theory (MPT)** to build and optimize a stock portfolio using Python.  
The main objective is to **maximize the Sharpe Ratio** and visualize the **Efficient Frontier**.

---

## Pipeline

- Download historical stock data
- Compute expected annual returns
- Compute the covariance matrix (risk)
- Optimize portfolio weights
- Maximize the Sharpe Ratio
- Plot the Efficient Frontier
- Compare individual stocks vs. the optimal portfolio

---

## Key Concepts Used

- Expected Return  
- Volatility (Standard Deviation)  
- Covariance & Correlation  
- Efficient Frontier  
- Sharpe Ratio  
- Diversification  

Sharpe Ratio formula:

\[
Sharpe = \frac{R_p - R_f}{\sigma_p}
\]

Where:
- \( R_p \) = Portfolio return  
- \( R_f \) = Risk-free rate  
- \( \sigma_p \) = Portfolio volatility  

---

## Tools & Libraries

- `yfinance` – download stock data  
- `pandas` – data handling  
- `numpy` – numerical calculations  
- `PyPortfolioOpt` – portfolio optimization  
- `matplotlib` – visualization  

---

## Results

The optimizer selected weights that maximize risk-adjusted return.  
In this case, the optimal portfolio concentrated on the assets that provided:

- Higher expected returns
- Lower volatility
- Better diversification benefits

The final output included:

- Optimal weights
- Expected annual return
- Annual volatility
- Sharpe ratio
- Efficient frontier visualization

---

## Visualization

The Efficient Frontier graph shows:

- Black dots → Individual stocks  
- Blue curve → Efficient portfolios  
- Red star → Optimal (Max Sharpe) portfolio  

This demonstrates how combining assets can achieve **better risk-return trade-offs** than holding individual stocks alone.

---

## Conclusion

This project shows how quantitative methods can be used to:

- Improve portfolio allocation decisions
- Reduce risk through diversification
- Maximize risk-adjusted performance

It is a practical implementation of portfolio optimization used in quantitative finance and asset management.

