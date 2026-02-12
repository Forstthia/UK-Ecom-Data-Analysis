# UK-Ecom-Data-Analysis
A business intelligence project analyzing 540k rows of UK retail data using Excel &amp; Power BI.
# UK Cross-Border E-Commerce Business Intelligence Analysis 🇬🇧📊

![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811?style=flat&logo=powerbi)
![Excel](https://img.shields.io/badge/Excel-Power%20Query-217346?style=flat&logo=microsoft-excel)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Project Overview
This project is an end-to-end Business Intelligence analysis based on 540,000+ rows of transactional data from a UK-based cross-border e-commerce platform. 

Objective: To identify growth drivers, optimize inventory management, and refine marketing strategies for the upcoming fiscal year by analyzing sales trends, market distribution, and product diversity.

## 🛠️ Technical Architecture

### 1. Data ETL (Extract, Transform, Load)
- Tool: Microsoft Excel (Power Query)
- Process:
  - Cleaned 540k rows of raw data, handling null values in CustomerID.
  - Logic Validation: Excluded records with Quantity < 0 (Returns) to ensure revenue accuracy.

### 2. Data Modeling
- Tool: Power BI (DAX)
- Key Metrics: Built data models for Average Order Value (AOV), Order Volume, and MoM Growth Rates.

---

## 🚀 Key Insights & Visualizations

### 1. Seasonal Trends & "Peak Season" Signal
- Observation: Sales spiked from 644k in August to 907k in September, recording a 40.8% MoM growth. This signals the start of the Q4 peak season.
- Peak: The annual revenue peaked in November (1.15M), aligning with Black Friday and Christmas pre-sales.

<img width="1873" height="1305" alt="image" src="https://github.com/user-attachments/assets/b99dd9cc-46bb-4469-bcf1-83287e753260" />



### 2. Market Distribution Strategy
- Core Insight: Excluding the UK, Netherlands emerged as the #1 overseas market (~300k revenue), likely driven by B2B wholesale logistics.
- Opportunity: EIRE (Ireland) shows the highest retention potential, while Germany and France remain the volume leaders.

<img width="1865" height="1306" alt="image" src="https://github.com/user-attachments/assets/f008f622-59bc-43e1-abad-d7ab6280a8a3" />


### 3. The "Long-tail" Effect
- Data Finding: The Top 10 best-selling SKUs contribute only 1% of total volume.
- Conclusion: The business is driven by a vast variety of niche products rather than a few "blockbusters".

<img width="1876" height="1319" alt="image" src="https://github.com/user-attachments/assets/0091a5f3-df60-4b9b-8316-07cd8909fb38" />


---

## 💡 Business Recommendations

Based on the data analysis, the following strategies are proposed:

| Category | Actionable Strategy | Expected Outcome |
| :--- | :--- | :--- |
| 📦 Supply Chain | Pre-peak Stocking: Complete Q4 inventory stocking by mid-August to handle the 40% Sept surge. | Prevent Out-of-Stock (OOS) during Nov peak. |
| 💰 Pricing | Tiered Pricing: Implement bulk-buy discounts for the Netherlands market to capture B2B demand. | Increase Average Order Value (AOV). |
| 🎯 Marketing | Dayparting Ads: Limit paid ad spend to 09:00 - 16:00 (peak hours) and cut budget during 20:00 - 07:00. | Save ~30-40% of invalid ad budget. |
| 🛍️ Sales | Bundling: Use "Blind Box" or "Cross-selling" bundles for long-tail items. | Activate the 99% slow-moving inventory. |

---

## 📂 Repository Structure

```text
UK-Ecom-Data-Analysis/
├── 📁 Dataset
│   └── Dataset_UK_Retail_Cleaned_v1.xlsx   # Cleaned Data Source
├── 📁 Dashboard
│   └── Dashboard_UK_Ecom_Analysis_v1.pbix  # Interactive Power BI File
└── 📁 Report
    └── Insights_Report_UK_Retail_Business.pdf # Full PDF Report

---

## ⚙️ How to Use

1. **Clone this repository** `git clone https://github.com/yourUserName/UK-Ecom-Data-Analysis.git`

2. **Open the Dashboard** Locate and open `Dashboard/Dashboard_UK_Ecom_Analysis_v1.pbix` in Power BI Desktop.

3. **Update Data Source Path** If the data fails to refresh, follow these steps:
   - Click **Transform Data** in the ribbon.
   - Select **Edit Parameters**.
   - Change `FolderPath` to your current local directory.
