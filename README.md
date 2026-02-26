# U.S. Blue-Chip & Index Fund Portfolio Optimization

## Overview
The project I have built largely implements **Modern Portfolio Theory (MPT)** to architect optimal investment strategies for high-performing U.S. large-cap stocks and the SPY ETF. By processing historical data via the `yfinance` API, the tool calculates key financial metrics—such as expected returns and volatility—to map the Efficient Frontier, providing a mathematical foundation for asset allocation.

## Core Features & Methodology
- **10,000+ Monte Carlo Simulations:** Generates a vast distribution of random portfolio weights to visualize the spectrum of possible risk-return outcomes, ensuring a robust statistical foundation.
- **Optimization Models:** - **Maximum Sharpe Ratio:** Pinpoints the "Tangency Portfolio" that offers the highest excess return per unit of risk, given a 10-year Treasury yield risk-free rate.
  - **Global Minimum Variance (GMV):** Identifies the specific asset combination that yields the lowest possible volatility for risk-averse investors.
- **Interactive Financial Visuals:** Utilizes Plotly to create dynamic scatter plots and heatmaps, allowing users to hover over data points to see specific asset weights and performance metrics.
- **Multi-Horizon Analysis:** Conducts comparative testing across 3-year and 5-year historical windows to evaluate how different market regimes impact portfolio stability and diversification benefits.

## Tech Stack & Dependencies
- **Data Handling:** Pandas, NumPy
- **Optimization:** SciPy (Optimize)
- **Visualization:** Plotly (for interactive charts)
- **Financial API:** yfinance (Yahoo Finance)

## Author's Note
This project is a labor of love. I started as a 'what if' and evolved into a tool that I am proud to share with the world :)

Thank you for checking out my work.
