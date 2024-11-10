# Where Business Thrives: A Country-by-Country Financial Indicator Comparison

### Run the Jupyter Notebook to view the full analysis and visualizations.

### Overview
This project explores and compares key financial indicators across multiple countries, using data extracted via the Nasdaq Data Link API. By analyzing indicators like profitability, liquidity, efficiency, leverage, and growth, this project provides insights into global company performance and identifies the best countries for business success.

### Project Goals
- To assess and compare country-level financial health using fundamental financial indicators.
- To identify trends and outliers that distinguish high-performing countries from those with potential financial issues.
- To visualize and summarize findings for accessible interpretation of cross-country financial strengths and weaknesses.

### Data Collection and Preprocessing
- **Data Source**: Nasdaq Data Link API, specifically the MER/F1 financial dataset.
- **Process**: Financial data was extracted and processed in Python, focusing on a few specific indicators (like Current Ratio, EBITDA, Operating Margin) for consistent cross-country comparisons.
- **Data Aggregation**: Data was pivoted, aggregated by financial category, and grouped by country for comparative insights.

### Analysis Breakdown
- **Profitability Indicators**: Analysis of metrics like EBITDA and Net Income to gauge revenue-generating efficiency.
- **Liquidity Indicators**: Examining Current and Quick Ratios, and Cash from Operations to determine short-term financial stability.
- **Efficiency Indicators**: Assessing Inventory Turnover, Total Asset Turnover, and Accounts Payable Turnover to understand operational effectiveness.
- **Leverage Indicators**: Reviewing Total Debt to Equity and Interest Coverage for insights into debt reliance and risk.
- **Growth Indicators**: Evaluating Total Revenue and return metrics to understand growth patterns across countries.

### Key Results
- **Top Performing Countries**: Summarized findings highlight which countries are optimal for business based on financial indicators.
- **Insights into Financial Health**: Comparative analysis across indicators illustrates varied financial health and growth potential across global markets.

### Technologies Used
- Python (Pandas, Seaborn)
- Nasdaq Data Link API
- Jupyter Notebook

### License
This project is licensed under the MIT License.
