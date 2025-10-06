# Trade and Sentiment Analysis
## Objective
The objective of this project is to analyze how trading behavior (profitability, risk, volume, leverage) aligns or diverges from overall market sentiment (fear vs greed) and to identify hidden trends or signals that could influence smarter trading strategies.

## About the project
* Cleaned, aggregated, and merged trader and market sentiment datasets to create a unified view for behavioral analysis.
* Analyzed profitability, trading volume, leverage, and position sizes across Fear vs. Greed market phases, uncovering patterns like higher risk-taking in Greed and disciplined trading in Fear.
* Highlighted how market sentiment influences trader behavior, providing insights that can inform smarter, data-driven trading strategies.

### Dataset
The dataset used for this analysis were:
1. Bitcoin Market Sentiment Dataset: Provides Classification (Fear vs Greed) according to Date.
2. Historical Trader Data from Hyperliquid: Contains variables like account, symbol, execution price, size, side, time and other attributes.

### Methodologies
- Exploring datasets
- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis

## Key Insights
- *Greed periods* → higher volumes, larger positions, more traders active, but not always higher profitability.  
- *Fear periods* → lower volumes, fewer traders, but sometimes better PnL due to disciplined strategies.

### Outputs
<img width="598" height="455" alt="Regression Plot - Execution Price vs Closed PnL" src="https://github.com/user-attachments/assets/012214c5-34c9-4216-9069-108aafaec681" />
<img width="996" height="547" alt="Line Chart - Value Over Time" src="https://github.com/user-attachments/assets/709bb337-689e-4845-bcff-0a37a5efe423" />
<img width="1043" height="547" alt="Line Chart - Closed PnL Over Time" src="https://github.com/user-attachments/assets/66a47ba6-c650-4cfa-88df-f96f27e6f525" />
<img width="523" height="624" alt="Box Plot - Classification vs Size USD" src="https://github.com/user-attachments/assets/043bc047-920d-4223-939f-a3e76619ff0d" />
<img width="855" height="638" alt="Bar Graph - Classification vs Account" src="https://github.com/user-attachments/assets/4ebe41e9-64de-46ee-8077-d66b1265d302" />

