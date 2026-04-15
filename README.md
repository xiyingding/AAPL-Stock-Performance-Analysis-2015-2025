# AAPL-Stock-Performance-Analysis-2015-2025
ACC102 Python Data Product: AAPL Stock Performance Analysis (2015-2025)
# AAPL Stock Performance Analysis (2015–2025)
## ACC102 Python Data Product Assignment

### Project Overview
This Python-based data product conducts a comprehensive quantitative analysis of Apple Inc. (AAPL) stock performance from 2015 to 2025, leveraging daily market data from the WRDS CRSP database. The project follows a complete data analysis pipeline, from data extraction to visualization, to evaluate AAPL's long-term investment value, risk-return characteristics, and growth potential.

### Dataset
- **Source**: WRDS CRSP (Center for Research in Security Prices)
- **Time Period**: January 1, 2015 – December 31, 2025
- **Data Fields**: Daily stock price (`prc`), daily return (`ret`), trading volume (`vol`)

### Key Python Methods & Tools
- **Data Extraction**: `wrds` library (connect to WRDS database)
- **Data Cleaning**: Handle missing values, remove duplicates, standardize column names
- **Financial Analysis**: Calculate annualized return, annualized volatility, Sharpe ratio, max drawdown
- **Visualization**: `matplotlib` / `seaborn` (stock price trend, daily return distribution, cumulative return curve)
- **Summary**: Generate key performance metrics table

### Key Outputs
1.  **Stock Price Trend Chart**: 10-year AAPL price movement visualization
2.  **Daily Return Distribution**: Volatility and return pattern analysis
3.  **Cumulative Return Curve**: Long-term compound growth demonstration
4.  **Performance Metrics Table**: Consolidated summary of return, risk, and risk-adjusted performance

### Conclusion
AAPL demonstrates strong long-term growth (27.31% annualized return), moderate volatility (28.46% annualized), and a favorable risk-adjusted return (Sharpe ratio 0.96) over the 10-year period. The stock shows resilience during market downturns (e.g., 2020 COVID crash) and is suitable for long-term investment portfolios.

### Target Audience
Individual investors, financial students, and junior analysts seeking data-driven insights for AAPL stock investment decisions.
