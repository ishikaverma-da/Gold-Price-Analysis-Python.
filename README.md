# Gold Price Analysis 2015-2025 🥇

## Overview
A comprehensive analysis of Gold price trends, returns, volatility, and correlation with US Dollar Index (DXY) using Python. This project explores 10 years of historical gold trading data to uncover patterns, trends, and market behavior.

## Tools & Libraries Used
- **Python** — core programming
- **Pandas** — data manipulation & resampling
- **Matplotlib** — static visualizations
- **Plotly** — interactive charts
- **yfinance** — real-time financial data extraction

## Dataset
- **Source:** Yahoo Finance via yfinance library
- **Ticker:** GC=F (Gold Futures)
- **Period:** January 2015 — December 2025
- **Rows:** 2764 daily trading records
- **Columns:** Open, High, Low, Close, Volume

## Key Insights
- Gold delivered ~4x returns over 10 years — from $1050 to $4500
- Positive returns in 8 out of 10 years — consistent long-term asset
- Only 2018 and 2021 saw negative returns — driven by strong dollar and post-COVID equity boom
- Daily returns follow normal distribution — confirming low volatility safe-haven behavior
- Gold vs Dollar (DXY) correlation = 0.34 — weaker inverse relationship post-2022 due to geopolitical tensions
- Golden Cross patterns (50-day MA crossing 200-day MA) in 2019 and 2023 preceded major rallies

## Charts
1. Gold Price Trend - Daily (2015-2025)
2. Gold Price Trend - Monthly Average
3. Yearly Returns Analysis
4. Moving Averages — 50 Day & 200 Day
5. Trading Volume Analysis
6. Daily Returns Distribution
7. Gold vs US Dollar Index Correlation
