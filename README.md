# Bitcoin Sentiment Trading Strategy Analysis
**Candidate:** POLEBOINA KAVYA  
**Focus:** Data Science / Quant Finance

## 📊 Project Overview
This project explores the relationship between market psychology (Bitcoin Fear & Greed Index) and actual trading performance. By merging historical price action with sentiment data, I identified high-probability trading zones based on market "Fear" and "Greed" levels.

## 🚀 Key Insights
* **The "Fear" Advantage:** The highest average daily profits ($52,793) were realized during periods of **Extreme Fear**.
* **Counter-Sentiment Strategy:** Data suggests a highly effective strategy:
    * **BUY (Long)** when the market is in a state of **Fear**.
    * **SELL (Short)** when the market is in a state of **Extreme Greed**.
* **Win Rate:** While "Extreme Greed" showed a higher nominal win rate (46.7%), the most significant PnL gains occurred during market distress.

## 📂 Project Structure
* `data/`: Contains the Bitcoin Fear & Greed Index and historical trading datasets.
* `notebooks/`: Jupyter Notebook containing the data cleaning, merging, and analysis logic.
* `outputs/`: Data visualizations showing PnL distribution by sentiment.
* `reports/`: The final PDF report summarizing the executive findings and methodology.

## 🛠️ Tools Used
* **Python:** Pandas, Matplotlib, Seaborn.
* **Analysis:** Time-series merging, sentiment classification, and PnL aggregation.





