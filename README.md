# ACC102 Track2 – AI Computing Power Chain: Stock Performance Analysis (2020–2026)
Python Data Analysis Project for ACC102 – Financial Analysis of AI-Related Stocks

## Overview
This project conducts a comprehensive financial analysis of five key companies in the global AI computing power chain using historical stock data. It calculates key risk and return metrics and generates 11 professional visualizations to reveal performance patterns driven by generative AI demand.

## 1. Analytical Problem & Target Users
- **Analytical Problem**: Evaluate the historical risk‑return performance of major AI computing power stocks.
- **Target Users**: Investors, finance students, and researchers interested in AI industry stock performance.

## 2. Dataset Information
- **Source**: WRDS CRSP Daily Stock File (dsf)
- **Access Date**: 2026-04-22
- **Period**: 2020-01-01 to 2026-04-20
- **Tickers**: NVDA, MSFT, GOOGL, TSM, AVGO
- **Variables**: date, price (prc), daily return (ret)

## 3. Python Methods & Libraries
- **Libraries**: pandas, numpy, matplotlib, seaborn, wrds
- **Data processing**: Import, pivot, clean, and handle missing values
- **Metrics**:
  - Cumulative return
  - Annualized return & volatility
  - Sharpe ratio
  - Maximum drawdown
  - 60‑day rolling volatility
  - Correlation matrix
- **Visualization**: Line charts, bar charts, heatmap, boxplot, scatter plot

## 4. Visual Outputs (11 Charts)
1. Raw Stock Price Trends
2. Cumulative Return Comparison (Initial $1)
3. Annualized Volatility
4. Historical Maximum Drawdown
5. Return Correlation Heatmap
6. Annualized Return
7. Sharpe Ratio
8. Mean Daily Return
9. Daily Return Distribution (Boxplot)
10. 60‑Day Rolling Volatility
11. Risk‑Return Trade‑off Scatter Plot

## 5. Key Insights
- NVDA and AVGO show explosive growth since 2023 driven by AI demand.
- NVDA delivers the highest annualized return and cumulative return.
- MSFT and GOOGL have lower volatility and are suitable for risk‑averse investors.
- All stocks faced large drawdowns in mid‑2022 during rate hikes.
- High correlation between MSFT and GOOGL; low correlation between GOOGL and TSM.
- A clear positive risk‑return relationship exists across the sector.

## 6. How to Run
### Prerequisites
- Python 3.8 or higher installed on your machine
- Git (to clone the repository) or you can download the ZIP file
### Step 1: Clone or download the repository
    '''bash
    git clone https://github.com/ruohanma/AI-Computing-Power-Chain-Stock-Performance-Analysis-2020-2026.git
    cd AI-Computing-Power-Chain-Stock-Performance-Analysis-2020-2026
### Step 2: Install dependencies
- Install all required packages using the provided requirements.txt file (recommended):
  
    pip install -r requirements.txt
### Step 3: Choose your data source
#### Option A: Using WRDS (requires live data & WRDS account)
1. Open the Jupyter notebook: AI Computing Power Chain Stock Performance Analysis 2020-2026.ipynb
2. In the first configuration cell, set USE_LOCAL_CSV = False
3. Run all cells: Cell → Run All from the Jupyter menu
4. The notebook will:
- Connect to WRDS
- Download daily price and return data for the five tickers (NVDA, MSFT, GOOGL, TSM, AVGO) from 2020-01-01 to 2026-04-20
- Compute risk-return metrics
- Display 11 charts and console outputs
#### Option B: Using pre-saved CSV files (no WRDS required)
1. Open the Jupyter notebook: AI Computing Power Chain Stock Performance Analysis 2020-2026.ipynb
2. In the first configuration cell, set USE_LOCAL_CSV = True
3. Run all cells: Cell → Run All from the Jupyter menu
4. The notebook will read the CSV files from the data/ folder and display all outputs immediately

## 7. Limitations
- Only price and return data are used; fundamental indicators are not included.
- Results are based on historical data and do not predict future returns.
- Geopolitical risks and policy changes are not modeled.

## 8. Future Improvements
- Add fundamental indicators (P/E, revenue, profit margins)
- Include more AI and semiconductor companies
- Build forecasting models for returns and volatility
- Develop interactive visualizations

## 9. Submission Links
- GitHub Repository: https://github.com/ruohanma/AI-Computing-Power-Chain-Stock-Performance-Analysis-2020-2026/tree/main
