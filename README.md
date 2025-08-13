# 📊 USA Regional Sales Analysis

## 📝 Overview
This project applies **data analytics techniques** to a multi–year U.S. sales dataset to uncover trends, identify growth opportunities, and recommend strategies for revenue and profit optimization.  
The analysis covers **5 years of transactions (2014–2018)** for Acme Co., spanning multiple channels, product lines, and geographic regions.

The work includes:
- **Data ingestion & cleaning** from multi–sheet Excel data sources
- **Exploratory Data Analysis (EDA)**
- **Trend, seasonality & outlier detection**
- **Customer & product segmentation**
- **Key business recommendations**
- **Interactive Power BI dashboard** for self-service insights

> **Business Goal:** Transform raw sales data into actionable intelligence for pricing, promotions, regional strategy, and inventory planning.

---

## 🚀 Problem Statement
Regional sales performance in the U.S. showed **inconsistent revenue and profitability**, with limited visibility into:
- Seasonal sales swings
- Top- and bottom-performing SKUs
- Channel profitability
- Regional growth potential

**Key Question:**  
> *How can we leverage historical sales data to identify growth levers, manage margin risks, and optimize strategy across products, channels, and regions?*

---

## 🔍 Approach

### **Phase 1 — Exploratory Data Analysis (EDA)**
- Data profiling and schema validation
- Merging and cleaning multi-sheet Excel data
- Feature engineering: profit, profit margin %, monthly aggregation
- Univariate & bivariate analysis to uncover relationships
- Regional, product, channel & customer segmentation
- Trend and seasonality analysis
- Outlier detection for revenue and pricing anomalies

### **Phase 2 — Interactive Dashboard**
- Designed a **Power BI dashboard** for self-service analysis
- Real-time slicing by product, region, channel, and time period
- Visual storytelling for sales leaders and marketing teams

---

## 🛠️ Tech Stack & Tools
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** – Data processing & visualization
- **Google Colab** – Development environment
- **Power BI** – Interactive dashboard creation
- **Excel** – Raw data storage & inspection

---

## 📊 Data Description
Final curated dataset contains:

**Identifiers:** `order_number`, `order_date`, `customer_name`, `channel`, `product_name`  
**Financials:** `quantity`, `unit_price`, `revenue`, `cost`, `profit`, `profit_margin_pct`  
**Calendar:** `order_month_name`, `order_month_num`, `order_month`  
**Geography:** `state`, `state_name`, `us_region`, `lat`, `lon`  
**Planning:** `budget (2017)`  

---

## 📈 Key Insights
From the EDA & dashboard, we discovered:

- **Seasonality:**  
  - Peaks in late spring/early summer (May–June)  
  - Lows in January, with a notable dip in early 2017

- **SKU Concentration:**  
  - Products **26 & 25** account for ~25% of total revenue  
  - Lower-tier SKUs underperform and may need repricing or phasing out

- **Channel Mix:**  
  - **Wholesale** drives 54% of sales volume  
  - **Export** has the highest average margin (~38%)

- **Geographic Performance:**  
  - **California** leads with $230M revenue and 7.6K orders  
  - West region shows largest seasonal swings  
  - Northeast lags – potential market development opportunity

- **Customer Analysis:**  
  - Revenue is highly concentrated in top accounts (e.g. Aibox Company)
  - Large clients with low margins highlight pricing pressure

- **Correlation Analysis:**  
  - **Unit price** has strongest correlation with revenue (0.91) and profit (0.79)  
  - Quantity plays a secondary role (< 0.35 correlation with financials)
 
  - ## 💡 Recommendations
1. **Seasonal Promotions:** Boost off-peak months with targeted offers.
2. **SKU Optimization:** Double down on top SKUs, re-evaluate low-margin products.
3. **Channel Strategy:** Expand high-margin Export relationships; incentivize Wholesale for volume.
4. **Regional Investments:** Replicate California's approach in other high-potential states; strengthen Northeast presence.
5. **Margin Monitoring:** Flag and analyze orders below target margin thresholds.

## 📚 What I Learned
- Joining and harmonizing disparate datasets for holistic business analysis
- Building reproducible EDA pipelines in Python
- Translating analytical insights into actionable strategic recommendations
- Designing executive-friendly dashboards in Power BI
- Communicating data findings effectively through visual storytelling

---

## 📌 Potential Next Steps
- Automate ETL with scheduled data refreshes
- Add predictive modeling for sales forecasting
- Incorporate more granular customer behavior analytics
- Benchmark performance against industry averages

---

## 👤 Author
**Aryan Aher**  
Data Analyst / BI Developer | Skilled in Python, SQL, Power BI, and Data Storytelling  
