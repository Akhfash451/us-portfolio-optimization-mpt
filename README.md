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
This project is a labor of love. I started as a 'what if' and evolved into a tool that I am proud to share with the world.

To test the interactive visualizations of the project, please download the file **us_portfolio_optimization_ad** in your computer storage and run it in Jupyter Notebook or VS Code. Thank you for checking out my work :)

## Screenshots (Visualizations)
<img width="1103" height="600" alt="daily_log_returns_distribution" src="https://github.com/user-attachments/assets/53531cfe-3dc9-420b-a00d-ec1313289937" />
<img width="1103" height="600" alt="corr_matrix_daily_log_returns" src="https://github.com/user-attachments/assets/c3a25d4b-abcc-42e6-88c4-4985b2db2149" />
<img width="1103" height="700" alt="efficient_frontier_visualization" src="https://github.com/user-attachments/assets/46063a9b-d63f-4702-8190-8b5d7b6258e1" />
<img width="700" height="500" alt="allocation_pie_charts" src="https://github.com/user-attachments/assets/bd73db48-25c2-4c66-a93a-04c8973814e2" />
<img width="1103" height="600" alt="comparison_efficient_frontier" src="https://github.com/user-attachments/assets/8b88ae8a-cf96-48fb-bcab-7b4c1015c9a3" />
