# personalprojects

S&P500 Prediction Model

Features
Fetches historical market data for S&P 500, Gold (GLD), and the Volatility Index (VIX).
Prepares datasets and extracts relevant features.
Implements machine learning with RandomForestClassifier.
Evaluates the model’s performance using precision score.

Data Sources
S&P 500 (^GSPC) - Historical stock prices.
Gold ETF (GLD) - Used as an alternative investment indicator.
Volatility Index (^VIX) - Market sentiment indicator.

Model Overview
Algorithm: RandomForestClassifier
Evaluation Metric: Precision Score
Input Features: Market data from yfinance


Valuation Ratios Tool

Overview
This tool fetches real-time financial data using the Yahoo Finance API (yfinance) and calculates key valuation ratios for publicly traded companies. These ratios are essential for investors, analysts, and finance professionals to assess a company's valuation relative to its earnings, cash flow, and market value.

Features
Fetches live stock data (current price, market cap, industry).
Computes key valuation ratios, including:
Price-to-Earnings (P/E) Ratio
Enterprise Value (EV)
EV/EBITDA Ratio
EV/FCF (Free Cash Flow) Ratio
Price-to-Book (P/B) Ratio
EV/Revenue Ratio
Uses financial statements (Balance Sheet, Income Statement, Cash Flow Statement) for calculations.
Built with Python (pandas, yfinance, numpy, openpyxl).
