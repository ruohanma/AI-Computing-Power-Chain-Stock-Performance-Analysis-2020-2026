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
### Option A: Using WRDS (requires WRDS account)
1. Install dependencies:
   pip install pandas numpy matplotlib seaborn wrds
2. Set USE_LOCAL_CSV = False.
3. Run the Python script directly.
4. All charts and metrics will display automatically.
### Option B: Using pre‑saved CSV files (no WRDS needed)
1.In the notebook, set USE_LOCAL_CSV = True.
2.Run all cells – the notebook will read from the local CSV files.

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
- Demo Video: [Your Video Link]   
