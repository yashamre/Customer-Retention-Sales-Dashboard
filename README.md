# 📊 Customer Retention & Sales Insights Dashboard

This project presents a professional Power BI dashboard that analyzes customer purchase behavior and sales performance using the **Online Retail dataset**. It uncovers trends across time, geography, and product lines — enabling better business decisions based on actionable insights.

---

## 📁 Project Structure

``` 

Customer-Retention-Sales-Dashboard/
│
├── Customer Retention & Sales Insights Dashboard.pbix        # Power BI dashboard file
├── Online Retail.xlsx                                        # Cleaned transactional data
├── Screenshots/
│   └── dashboard_preview.jpeg                                # Dashboard screenshot
└── README.md                                                 # Project documentation

```

---

## 💡 Project Overview

- **Goal:** Help stakeholders understand customer purchasing patterns, retention, and geographic sales breakdown.
- **Dataset:** [Online Retail Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/online+retail)
- **Tool:** Microsoft Power BI (Desktop)

---

## 📌 Key Features

### ✅ **1. KPI Cards**
- **💰 Total Revenue Generated**
- **🧍 Total Unique Customers**
- **🛒 Total Orders Placed**

### ✅ **2. Revenue Trend Over Time**
- Monthly revenue pattern across a 12-month window
- Visualized with dynamic `Year-Month` timeline

### ✅ **3. Top Products by Revenue**
- Horizontal bar chart showing top 10 products
- Helps optimize inventory and marketing spend

### ✅ **4. Revenue by Country**
- **Donut chart**: % share of each country
- **Map visual**: Geospatial distribution of revenue globally

### ✅ **5. Slicers for Interactivity**
- Country, Year-Month, and CustomerID filters allow detailed exploration of the data

---

## 🧠 Methodology

- Data cleaned in **Power Query**:
  - Removed nulls and negative quantity/price
  - Added `Revenue` column = `Quantity * UnitPrice`
  - Extracted `Year`, `Month`, and `YearMonth` from `InvoiceDate`
- Applied visual best practices:
  - Consistent theme
  - Proper formatting, labels, and alignment
  - Dashboard-level interactivity

---

## 📸 Dashboard Preview

![Dashboard Screenshot](https://github.com/yashamre/Customer-Retention-Sales-Dashboard/blob/604371d90f88847f271bd7e705bf9982280416d7/Screenshots/dashboard_preview.jpeg)

---

## 📈 Tools Used

| Tool           | Purpose                            |
|----------------|------------------------------------|
| Power BI       | Dashboard creation & visualization |
| Power Query    | Data cleaning and transformation   |
| Excel/CSV      | Data source and preprocessing      |

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open with **Power BI Desktop**
3. Use filters to explore various trends and breakdowns
4. Modify visuals or add new ones as needed
