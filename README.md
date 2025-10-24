# ds_Safwan_Abdur_Rahman

---

## 🧠 Objective
Analyze how trader behavior (profitability, risk, volume, leverage) aligns or diverges from overall market sentiment (Fear vs Greed).  
The goal is to identify hidden trends or signals that could inform smarter trading strategies.

---

## 📊 Datasets
1. **Bitcoin Market Sentiment Dataset**  
   - Columns: `Date`, `Classification` (Fear / Greed)  
2. **Historical Trader Data from Hyperliquid**  
   - Columns include: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.

---

## ⚙️ Workflow
1. **Notebook 1:**  
   - Cleaning & preprocessing raw datasets  
   - Normalizing column names  
   - Converting timestamps to datetime  
   - Extracting date for merging  
   - Saving cleaned CSVs to `csv_files/`  

2. **Notebook 2:**  
   - Exploratory Data Analysis (EDA)  
   - Visualizing PnL, leverage, and volume against sentiment  
   - Generating insights from merged dataset  
   - Saving charts to `outputs/`  

---

## 📈 Key Insights
- Traders tend to **increase leverage and trade size during “Greed” phases**.  
- **Profitability improves slightly during “Fear” periods**, suggesting contrarian advantage.  
- Daily sentiment strongly correlates with **aggregate PnL distribution and volume spikes**.  

---

## 📘 Report
See `ds_report.pdf` for a summarized report of methodology, analysis, and charts.

---

## 🔗 Colab Links
https://colab.research.google.com/drive/11q7GlOxPUUO1hG-8777S325wRKmJzc_A?usp=sharing
https://colab.research.google.com/drive/1xI2k6bPOX2Kc81eJ9K3rSX_xhkArE9zY?usp=sharing

> Make sure both Colab notebooks are set to **“Anyone with the link can view.”**

---

## 📌 Notes
- All processed CSVs and charts are stored in their respective folders for easy access.  
- The folder structure follows the assignment guidelines strictly for submission.
