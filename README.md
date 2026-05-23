# Smart Stock Finder V1

## About the Project

This is my first stock market analysis project built using Python.

The purpose of this project is to analyze stocks using real market data and rank them based on return and risk. The project uses data from Yahoo Finance and applies basic financial metrics to compare stock performance.

## What I Learned

While building this project, I learned:

- Working with real-world financial data
- Data analysis using Pandas
- Numerical calculations using NumPy
- Data visualization using Matplotlib and Seaborn
- Calculating stock returns and risk
- Building a simple stock ranking system

## Stocks Analyzed

- TCS
- Infosys
- Reliance

## Metrics Used

### Total Return

Measures how much a stock has grown during the selected period.

### Risk (Volatility)

Calculated using the standard deviation of daily returns.

### Score

Score = Return / Risk

A higher score indicates better return relative to risk.

## Project Workflow

1. Download stock data using yfinance
2. Calculate daily returns
3. Calculate stock risk (volatility)
4. Calculate total return
5. Create a risk-adjusted score
6. Rank stocks based on score
7. Visualize results using charts

## Results

Based on the current scoring system:
Rank Stock 
1    Reliance 
2    Infosys 
3    TCS 

Reliance achieved the highest score because it generated significantly higher returns while maintaining a comparable level of risk.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance

## Future Improvements

This is Version 1 of the project.

Future versions may include:

- Analysis of 10+ stocks
- Maximum Drawdown
- CAGR
- Sharpe Ratio
- Improved ranking methodology
- Machine Learning based stock analysis

## Author

Vihan Pandya
