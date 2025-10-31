# ds_thanseela
Analyzing trader performance vs market sentiment using Fear/Greed Index -Data Science Assignment


Overview

This project analyzes how market sentiment (Fear & Greed Index) influences trader performance using real trading data.
The analysis connects sentiment trends with profitability (PnL), trade sizes, and execution behavior to identify how traders respond during periods of fear and greed.

Datasets Used

Fear & Greed Index

Columns: timestamp, value, classification, date

Source: Market sentiment data representing daily fear or greed levels.

Trading Dataset

Columns: account, coin, execution_price, size_usd, side, closed_pnl, etc.

Source: Hyperliquid trader activity data.

Key Steps

Data loading and preprocessing

Merging sentiment and trading datasets by date

Exploratory Data Analysis (EDA)

Correlation and regression analysis

PDF report summarizing findings

Key Insights

Trader profits increase during Extreme Greed phases.

Higher trading volume during Fear phases.

Weak but positive correlation between sentiment and profit.

Project Files:
notebook_1.ipynb      → Colab notebook (main code)
csv_files/            → Raw and processed data
outputs/              → Charts & visualizations
ds_report.pdf         → Summary report
