# Trader Performance vs Market Sentiment Analysis

## Overview

This project analyzes the relationship between Bitcoin Market Sentiment (Fear & Greed Index) and Hyperliquid trader performance.

The objective is to determine whether market sentiment influences trader profitability, trading activity, and trading behavior.

---

## Project Structure

```
Trader-Performance-vs-Market-Sentiment
│
├── data
├── output
├── Trader_Performance_Analysis.ipynb
├── README.md
├── requirements.txt
└── summary.md
```

---

## Dataset

### 1. Bitcoin Fear & Greed Index

Contains:

- Date
- Sentiment Classification
- Sentiment Value

### 2. Hyperliquid Historical Trader Data

Contains:

- Account
- Coin
- Execution Price
- Size
- Side
- Closed PnL
- Transaction Details

---

## Analysis Performed

- Data Loading
- Data Cleaning
- Missing Value Check
- Duplicate Check
- Timestamp Conversion
- Dataset Merge
- Daily PnL Calculation
- Win Rate Calculation
- Average Trade Size
- Trades per Day
- Buy vs Sell Analysis
- Trader Segmentation
- Sentiment Analysis

---

## Visualizations

- Average Closed PnL by Market Sentiment
- Number of Trades by Market Sentiment
- Buy vs Sell across Market Sentiments

---

## Key Findings

- Extreme Greed market conditions produced the highest average trader profitability.
- Fear periods recorded the highest trading activity.
- SELL trades slightly outnumbered BUY trades during most market conditions.

---

## Strategy Recommendations

- Increase exposure cautiously during Extreme Greed while maintaining risk controls.
- Avoid excessive trading during Fear periods despite increased market activity.

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Trader-Performance-vs-Market-Sentiment.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open

```
Trader_Performance_Analysis.ipynb
```

Run all cells from top to bottom.

---

## Author

Luv Thapa
