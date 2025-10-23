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

---

### 2. **Volume Trends (Bar/Line Chart)**
**Description:** Trading volume plotted across time for selected stocks.

**Insights:**
- Volume spikes align with **earnings releases** or **major announcements**.  
- **Netflix** exhibits extreme trading activity during volatile periods.  
- **Apple/Microsoft:** Stable trading volumes showing consistent investor confidence.

---

### 3. **Moving Average Plot (50-day & 200-day)**
**Description:** Short-term and long-term moving averages for trend analysis.

**Insights:**
- **Apple/Microsoft:** 50-day MA consistently above 200-day — sustained bullish trend.  
- **Netflix:** Frequent crossovers (golden/death crosses) due to volatility.  
- **Amazon:** Intermediate trend changes seen at intervals.

---

### 4. **Company Comparison Chart**
**Description:** Combined line graph comparing all companies’ stock prices.

**Insights:**
- **Apple** dominates with the highest price magnitude.  
- **Microsoft** close behind in consistent growth.  
- **Amazon:** Moderate upward trend.  
- **Netflix:** Large oscillations indicate unstable momentum.  

---

### 5. **Profit Margin vs. Market Cap (Scatter Plot)**
**Description:** Relationship between profitability and market valuation.

**Insights:**
- **Apple:** Outlier with both highest profit margin and market cap.  
- **Positive correlation** between Profit Margin and Operating Margin.  
- **Quick Ratio** moderately linked to profitability — liquidity supports efficiency.

---

### 6. **Correlation Heatmap (Seaborn)**
**Description:** Correlation matrix of key financial metrics.

**Insights:**
- **Operating Margin ↔ Profit Margin:** Strong positive correlation.  
- **Quick Ratio ↔ Profit Margin:** Moderate link.  
- Highlights relationships useful for portfolio and financial health analysis.

---

### 7. **Distribution Plot (Histogram/KDE)**
**Description:** Distribution of daily returns or margins.

**Insights:**
- **Apple/Microsoft:** Normal distribution — lower volatility.  
- **Netflix:** Heavy-tailed distribution — high volatility and frequent outliers.  
- Supports **risk assessment** of return variability.

---

### 8. **Candlestick Chart (Plotly)**
**Description:** Daily OHLC visualization for price movement.

**Insights:**
- **Apple/Microsoft:** Smaller wicks, stable growth.  
- **Netflix:** Large wicks, frequent reversals.  
- Useful for identifying support/resistance and short-term trading signals.

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




