# Crypto RSI ETL Pipeline

A data engineering project that extracts live cryptocurrency trading indicator 
data from a financial API, transforms the raw JSON, and loads it into a MySQL database.

## What it does
- **Extracts** RSI (Relative Strength Index) data for BTC, ETH, and SOL 
  from the Crypto Trading Indicators API via RapidAPI
- **Transforms** the raw JSON response into a clean structured DataFrame
- **Loads** 1,461 rows of data into a local MySQL database

## Tools & Technologies
- Python, Pandas, Matplotlib
- MySQL, mysql-connector-python
- Jupyter Notebook, Anaconda
- RapidAPI (Crypto Trading Indicators API)

## Key Findings
- Bitcoin hit an extreme RSI low of 15.8 on February 4, 2026 — a strong oversold signal
- All three coins showed high correlation, moving in and out of overbought/oversold zones together
- Current RSI for BTC, ETH, and SOL all sit in the neutral range (39-41) as of March 2026

## How to run it
1. Clone this repo
2. Install dependencies: `pip install requests pandas mysql-connector-python jupyter`
3. Add your RapidAPI key to the headers in Cell 2
4. Run each cell top to bottom in Jupyter Notebook

## Author
Lans Odidi — Entry level Data Analyst based in Dallas-Fort Worth, TX  
[LinkedIn]((https://www.linkedin.com/in/lans-odidi/))
