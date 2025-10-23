# 📊 Stock Market Data Analysis 

This repository analyzes multi-company stock market data using Python (Pandas, Plotly, Seaborn, etc.) and visualizes financial metrics for insights into performance, risk, and valuation.

---

##  Overview

The notebook explores data from multiple technology companies — **Apple, Amazon, Microsoft, and Netflix** — focusing on their stock performance, trading volume, financial ratios, and correlations.

---

##  Visualizations & Insights

### 1. **Stock Price Trends (Plotly Line Chart)**
**Description:** Interactive line chart showing closing prices over time for multiple companies.

**Insights:**
- **Apple & Microsoft:** Steady long-term growth, low volatility.  
- **Amazon:** Moderate growth with periodic volatility spikes.  
- **Netflix:** Highly volatile post-2020 with sharp peaks and corrections.  
- **Overall:** Tech giants maintain strong upward momentum, with Netflix showing the highest risk/reward profile.

  <img width="1092" height="615" alt="closing price chart" src="https://github.com/user-attachments/assets/9ea9805d-18dd-4d38-b3c1-1946a3f23179" />


---

### 2. **Average Trends (Bar Chart)**
**Description**
This section provides insights into the **average Return on Equity (ROE)** and **average Profit Margin** of selected companies, highlighting their efficiency and profitability.

**Insights**
- **Best Performer:**  
  - **Apple** stands out with both high ROE and high profit margin, indicating strong efficiency and profitability.
  
- **Steady Performer:**  
  - **Microsoft** shows moderate ROE and profit margin, reflecting consistent and stable performance.
  
- **Underperformers:**  
  - **Netflix** has low ROE and profit margin, signaling low efficiency and potential concerns for profitability.
  
- **Mixed Performance:**  
  - **Amazon** has moderate ROE but low profit margin, suggesting reasonable operational efficiency but weaker profitability.
<img width="1102" height="600" alt="row barchart" src="https://github.com/user-attachments/assets/f7cdd751-e570-439d-99a7-49ce4a28c86d" />
  

---

### 3. **Trading volume**
**Description:** Donut chart showing each company’s share of total trading volume, highlighting market activity and liquidity.

**Insights**
- **Apple and Amazon** dominate trading activity, reflecting high investor interest and liquidity.
- **Microsoft** maintains steady volume, showing consistent market engagement.
- **Netflix** has a smaller share, indicating relatively lower trading activity.
- Overall, the chart highlights which companies are most actively traded, helping investors gauge market interest and potential liquidity for each stock.

<img width="1092" height="600" alt="newplot (3)" src="https://github.com/user-attachments/assets/6049f994-f6fb-4a53-aa96-4d7270b4f3fb" />

---

### 4. **Company Comparison Chart**
**Description**
This section illustrates the **distribution of daily returns across companies**, showing each company's contribution to overall daily return volatility.

**Insights**
- **Apple & Microsoft:**  
  - Largest slices – consistently higher daily returns, indicating strong market activity.
  
- **Amazon:**  
  - Moderate slice – moderate daily return volatility.
  
- **Netflix:**  
  - Smallest slice – lower daily returns, suggesting less impact on overall portfolio volatility.


<img width="1092" height="600" alt="distribution daily return pie chart" src="https://github.com/user-attachments/assets/e13adc2f-e135-4613-95d2-a09ac3aee91d" />

---

### 5. **Profit Margin vs. Market Cap (Scatter Plot)**
**Description:** KPI Comparision.

**Insights:**
- **Apple:** Outlier with both highest profit margin and market cap.  
- **Positive correlation** between Profit Margin and Operating Margin.  
- **Quick Ratio** moderately linked to profitability — liquidity supports efficiency.

  <img width="1092" height="600" alt="scatter" src="https://github.com/user-attachments/assets/9f8714e7-ab16-46c5-8ca4-56d4176d6f9b" />


---

### 6. **Correlation Heatmap (Seaborn)**
**Description:** Correlation matrix of key financial metrics.

**Insights:**
- **Operating Margin ↔ Profit Margin:** Strong positive correlation.  
- **Quick Ratio ↔ Profit Margin:** Moderate link.  
- Highlights relationships useful for portfolio and financial health analysis.

  <img width="1092" height="700" alt="heatmap" src="https://github.com/user-attachments/assets/fd9a77b7-28cc-4ea9-941b-c0b9f46af690" />


---

### 7. **Distribution Plot **
**Description:** Distribution of daily returns or margins.

**Insights:**
- **Apple/Microsoft:** Normal distribution — lower volatility.  
- **Netflix:** Heavy-tailed distribution — high volatility and frequent outliers.  
- Supports **risk assessment** of return variability.
<img width="1092" height="600" alt="barchart" src="https://github.com/user-attachments/assets/32c129a3-1156-4767-bde5-698835a7e91a" />

---

### 8. **Candlestick Chart (Plotly)**
**Description:** Daily OHLC visualization for price movement.

**Insights:**
- **Apple/Microsoft:** Smaller wicks, stable growth.  
- **Netflix:** Large wicks, frequent reversals.  
- Useful for identifying support/resistance and short-term trading signals.

  <img width="1092" height="600" alt="candlestick chart" src="https://github.com/user-attachments/assets/63b7dab3-f927-49de-9b00-5b61f445e635" />


---

##  Key Takeaways

| Aspect | Apple | Microsoft | Amazon | Netflix |
|:--|:--|:--|:--|:--|
| **Trend Stability** | Very High | Very High | Moderate | Low |
| **Volatility** | Low | Low | Medium | High |
| **Market Cap** | Highest | High | Medium | Lower |
| **Profitability** | Strong | Strong | Moderate | Variable |
| **Risk Level** | Low | Low | Medium | High |

---

##  Summary

1. **Apple & Microsoft** are the most stable and profitable performers.  
2. **Netflix** shows extreme volatility — high risk but potential short-term gains.  
3. **Amazon** exhibits moderate growth and occasional corrections.  
4. **Profitability** and **market valuation** show clear positive correlation.  
5. **Distribution & volume trends** reveal the risk patterns behind each stock.  

---

##  Technologies Used
- **Python Libraries:** Pandas, NumPy, Plotly, Matplotlib, Seaborn  
- **Notebook Environment:** Jupyter Notebook  
- **Data Format:** CSV (Stock Data)  

---




