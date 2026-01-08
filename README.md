# 📊 Mutual Fund Overview & Insights

This mutual fund analysis project focuses on identifying top 30 schemes with high return and low risk using Python, Excel, and Power BI.

🛠️ **Tools Used:** Python (Pandas, Sklearn), Excel, Power BI  
📁 **Dataset:** More Than 2500 Mutual Fund Schemes (Top 30 Filtered)

---

## 🧠 Project Goal

To identify **top-performing, low-risk mutual fund schemes** using data-driven techniques and present insights through a dynamic, professional Power BI dashboard.

---

## 🐍 Python-Based Fund Analysis

I started by importing and exploring a dataset of over 2500 mutual fund schemes.  


### 1. Data Cleaning
- Removed unnecessary columns
- Handled missing values
- Standardized numeric formats (returns, expense ratios)

### 2. Data Description & Understanding
- Statistical summaries using Pandas: mean, median, mode, min, max, std deviation
- Analyzed fund distributions across return rates, risk levels, and fund age

### 3. Data Normalization
- Used `MinMaxScaler` from `sklearn.preprocessing` to normalize numeric fields
- Compared returns and expense ratios on a common scale

### 4. Fund Scoring & Ranking
Custom scoring formula based on:
- High 3-Year Returns  
- Low Expense Ratio  
- Moderate Fund Age  
- Consistent 1-Year Return > 0

### 5. Final Output – Top 30 Funds
Extracted the **Top 30 Mutual Funds** with best return-low risk balance  
🔗 [Top 30 Mutual Funds (Excel)](https://github.com/subhaeng/Mutual-Fund-Analysis/blob/main/top_30_mutual_funds.xlsx)

---

## 📈 Power BI Dashboard – Mutual Fund Insights

After processing the data using Python and Excel, I built an **interactive dashboard** in Power BI.  
🔗 [Power BI Dashboard File (.pbix)](https://github.com/subhaeng/Mutual-Fund-Analysis/blob/main/Mutual%20Fund%20Dashboard.pbix)  
🔗 [Dashboard Preview Image](https://github.com/subhaeng/Mutual-Fund-Analysis/blob/main/Mutual%20Fund%20Dashboard%20.png)

### 📌 Key Features

#### 📅 Dynamic Filters
- Filter by Fund Type, Category, Sub-category, AMC Name, Risk Level, Fund Rating

#### 📊 Key Visuals & KPIs
- 💼 **Total Investment by Fund Type:** AUM across Equity, Debt, Hybrid, etc.  
- 🔁 **SIP vs Lumpsum Summary Cards:** Monthly SIP trends and minimum lump sum amounts  
- 🧾 **Expense Ratio Comparison:** By Investment Strategy and Sub-Category  
- 📈 **3-Year Returns (Donut Chart):** Category-wise long-term returns  
- 🏆 **Top Performing AMCs:** Average return and AUM  
- 👤 **Fund Manager AUM Comparison:** Largest fund managers by assets  
- 🧠 **Insight Cards:** Auto-generated insights with simple explanations

---

## 🔍 Mutual Fund Investment Insights

| Insight Category | Summary |
|------------------|---------|
| 💼 **Investment Trends** | Equity Funds lead with ₹1.35M Cr total size |
| 👤 **Fund Manager** | Vivek Sharma manages highest AUM: ₹7.3M Cr |
| 📉 **Cost vs Return** | Index Funds have lowest expense ratio: 0.26% |
| 🏦 **Best Return (1Y)** | Bank of India Mutual Fund: 14.4% |
| 🔄 **SIP vs Lumpsum** | Avg. SIP: ₹528.50/month, Lumpsum Min: ₹3.05K |
| ⏳ **3-Year Returns** | Equity Funds: 37.84%, Hybrid: 14.25% |

---

## 🖼️ Dashboard Preview

![Mutual Fund Dashboard Preview] <img width="1342" height="746" alt="MutualFundAnalysis" src="https://github.com/user-attachments/assets/fc9b3802-f035-4ebe-838b-51a11387964f" />



---

### 🧠 Final Conclusion – See the Power of Investment

Through this project and dashboard, you can clearly see the **power of investing in mutual funds** when guided by data-driven insights.

By analyzing returns, expense ratios, risk levels, and fund manager performance, I’ve shown how even basic financial knowledge, supported by visual tools, can help improve financial decisions.

💡 This dashboard isn't just about numbers—it's about empowering people to make **smarter, low-risk investments** and take control of their financial future.
Early and informed mutual fund investment leads to **long-term wealth creation**.  
By combining:
- Python for filtering,
- Excel for cleaning,
- Power BI for storytelling,

I created a tool that helps both beginners and experts make **data-driven, low-risk, high-reward decisions**.

---

## 🔧 Tool Summary

| Tool   | Purpose |
|--------|---------|
| Python | Data cleaning, scoring, filtering top 30 funds |
| Excel  | Formatting, validation, supporting data |
| Power BI | Interactive dashboard and visual storytelling |

---

