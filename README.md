# MyDataEngProjects

Stock Market Data Pipeline (SN)

This project downloads historical stock data using yfinance, calculates key statistics, stores the data in a SQLite database, and generates basic visualizations.

Features:
- Downloads historical stock prices from Yahoo Finance
- Calculates:
  - 20-day and 50-day moving averages
  - 20-day rolling volatility (standard deviation)
  - Daily returns and cumulative returns
- Saves processed data to a local SQLite database
- Generates visualizations for:
  - Price and moving averages
  - Volatility trend
  - Daily return distribution
  - Cumulative return over time
  - Price distribution (violin plot)
- Runs in Google Colab or Jupyter Notebook

Files:
- stock_pipeline_sn.ipynb - Full pipeline notebook
- README.md - Project info
- .gitignore - File exclusions
- data/ - Folder for output CSV and database (can be ignored in commits)

How to Run:
1. Open the notebook in Colab or Jupyter.
2. Change the ticker or date range if needed.
3. Run the notebook from top to bottom.

Requirements:
- yfinance
- pandas
- matplotlib
- seaborn
- sqlite3 (built-in)

Install with:
pip install yfinance pandas matplotlib seaborn

Author:
SN

License:
MIT
