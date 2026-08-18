# 📊 Sales Data Analysis Dashboard — 2024
**Tools: Python · Excel · Power BI**

> Analysed a 1,000-row retail sales dataset to identify top-performing products, seasonal trends, and a 23% Q3 revenue dip — with restocking recommendations to address it.

---

## 🚀 Project Overview

| Item | Detail |
|------|--------|
| **Dataset** | 1,000 retail transactions across 5 categories, 5 regions, 4 channels |
| **Period** | January 2024 – December 2024 |
| **Tools** | Python, Excel (openpyxl, pandas), Power BI |
| **Key Finding** | Q3 (Jul–Sep) shows a ~23% revenue dip vs quarterly average |

---

## 📁 Project Structure

```
sales-dashboard-2024/
│
├── data/
│   └── Retail_Sales_Dataset_2024.xlsx   # 1,000-row dataset (4 sheets)
│
├── charts/
│   ├── 01_kpi_banner.png                # KPI summary cards
│   ├── 02_monthly_revenue.png           # Monthly trend + Q3 annotation
│   ├── 03_quarterly_analysis.png        # Quarterly revenue & margins
│   ├── 04_top_products.png              # Top 10 products by revenue
│   ├── 05_category_analysis.png         # Category revenue & share
│   ├── 06_regional_analysis.png         # Regional performance
│   ├── 07_channel_breakdown.png         # Sales channel breakdown
│   ├── 08_seasonal_heatmap.png          # Category × Month heatmap
│   ├── 09_restocking_recommendations.png# Q3 dip + action plan
│   └── 10_full_dashboard.png            # 📌 Portfolio screenshot
│
├── analysis.py                          # Main Python analysis script
├── generate_data.py                     # Dataset generator
└── README.md
```

---

## 📊 Key Insights

1. **Electronics is the top category** — contributes ~35% of total revenue
2. **Laptop is the #1 product** by revenue across all regions
3. **Q3 Revenue Dip (~23%)** detected in Jul–Sep — seasonal pattern across all categories
4. **East region leads** in total revenue; all regions show similar margins (~24%)
5. **Retail Store & Online** channels account for 55%+ of revenue

---

## ⚠️ Q3 Dip Analysis & Restocking Plan

| Category | Q3 Impact | Recommendation |
|----------|-----------|----------------|
| Electronics | High dip | Restock 6 weeks early · Bundle deals |
| Clothing | High dip | Monsoon collection · Navratri pre-stock |
| Sports | Medium dip | Shift to indoor sports focus |
| Home & Kitchen | Low dip | Festival pre-stocking |
| Groceries | Minimal dip | Routine restock schedule |

---

## 🛠️ How to Run

```bash
# 1. Clone the repo
git clone https://github.com/YOUR_USERNAME/sales-dashboard-2024.git
cd sales-dashboard-2024

# 2. Install dependencies
pip install pandas openpyxl matplotlib seaborn plotly

# 3. Generate the dataset
python generate_data.py

# 4. Run the full analysis
python analysis.py
```

---

## 📈 Power BI Dashboard

Open `Retail_Sales_Dataset_2024.xlsx` in Power BI Desktop and connect to the **Sales Data** sheet.

**Recommended slicers:**
- Region (North / South / East / West / Central)
- Category (Electronics / Clothing / Groceries / Home & Kitchen / Sports)
- Quarter (Q1 / Q2 / Q3 / Q4)
- Channel (Online / Retail Store / Distributor / Direct Sales)

---

## 🧰 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)

---

## 👤 Author

**Your Name**  
[LinkedIn](https://linkedin.com/in/yourprofile) · [Portfolio](https://yourportfolio.com) · [GitHub](https://github.com/yourusername)
