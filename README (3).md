# 🚚 Logistics Operations Analytics

<div align="center">

### Power BI Dataset | Operations Domain | Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

</div>

---

## 📌 Problem Statement

An Indian logistics company wants to analyze its operations data to:
- Track **revenue, profit and order performance** across products, customers and regions
- Identify **delayed deliveries** and their root causes
- Understand **warehouse and driver efficiency**
- Surface **loss-making orders** and suggest business improvements

---

## 📂 Repository Structure

```
📦 Logistics-Operations-Analytics
 ┣ 📓 Logistics_Operations_Analytics.ipynb   ← Main notebook (all analysis)
 ┣ 📊 Logistics_PowerBI_Dataset__1_.xlsx     ← Source dataset (8 sheets)
 ┣ 📄 README.md                              ← Project documentation
 ┣ 📄 requirements.txt                       ← Python dependencies
 ┗ 📄 .gitignore                             ← Git ignore rules
```

---

## 📊 Dataset Overview

The dataset contains **8 sheets** covering all dimensions of logistics operations:

| Sheet | Description | Rows |
|-------|-------------|------|
| `Orders` | Core transactions with revenue, profit, delivery info | 300 |
| `Customers` | 15 customers across 4 regions in India | 15 |
| `Products` | 10 products across 5 categories | 10 |
| `Warehouses` | 5 warehouse hubs across India | 5 |
| `Drivers` | 12 drivers with vehicle types | 12 |
| `DateTable` | Date dimension for time-series analysis | — |
| `Relationships` | Data model relationships | — |
| `Suggested_KPIs` | KPI definitions from business team | 7 |

### Key Columns (Orders Sheet)
| Column | Description |
|--------|-------------|
| `OrderID` | Unique order identifier |
| `OrderDate` | Date of order placement |
| `Quantity` | Units ordered |
| `Revenue` | Total revenue (₹) |
| `ShippingCost` | Shipping cost (₹) |
| `TotalCost` | Total cost incurred (₹) |
| `Profit` | Revenue − TotalCost (₹) |
| `DeliveryDays` | Days taken to deliver (1–7) |
| `DeliveryStatus` | Delivered / Delayed / In Transit |

---

## 📈 KPI Dashboard

| KPI | Value |
|-----|-------|
| 💰 Total Revenue | ₹50M+ |
| 📈 Total Profit | ₹11M+ |
| 📊 Profit Margin | ~23% |
| 📦 Total Orders | 300 |
| ✅ On-Time Delivery Rate | ~77% |
| ⚠️ Delayed Orders | 35 (11.7%) |
| 🔴 Negative Profit Orders | 41 |
| ⏱️ Avg Delivery Days | 4.0 |

---

## 🔍 Key Insights

### 🏆 Products
- **Laptop** is the top-revenue product (₹55,000/unit)
- **Keyboard, Mouse & Router** frequently generate **negative profit** — pricing issue identified
- Office products (**Printer, Scanner**) show healthy margins

### 🌍 Regions
- **South region** leads in revenue and order volume
- **East region** has lowest contribution — growth opportunity

### 🚨 Delivery Performance
- 35 orders were **delayed** — Bangalore Hub has highest delay rate
- Delivery days range from **1 to 7** with an average of **4 days**

### 👥 Customers
- Top 3 customers contribute disproportionate revenue — **concentration risk**
- Customer-level profitability analysis included

---

## 🗂️ Notebook Sections

| Section | Description |
|---------|-------------|
| 0 | Imports & Setup |
| 1 | Load All 8 Sheets |
| 2 | Data Inspection & Quality Check |
| 3 | Build Master Merged Table |
| 4 | 📊 KPI Dashboard (7 KPIs) |
| 5 | Revenue & Profit — Monthly + Regional |
| 6 | Product Performance Analysis |
| 7 | Customer Analysis |
| 8 | Delivery Performance |
| 9 | Warehouse Performance |
| 10 | Driver Performance |
| 11 | Profitability & Loss Analysis |
| 12 | Correlation Heatmap |
| 13 | Business Insights & Recommendations |

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/jismon-george/Logistics-Operations-Analytics.git
cd Logistics-Operations-Analytics
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Place the dataset
```
Put Logistics_PowerBI_Dataset__1_.xlsx in the same folder as the notebook
```

### 4. Launch notebook
```bash
jupyter notebook Logistics_Operations_Analytics.ipynb
```

---

## 🧰 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</div>

---

## 💡 Business Recommendations

1. **Review pricing** for Keyboard, Mouse, Router — 41 loss-making orders need attention
2. **Investigate delays** — Bangalore Hub and specific driver-warehouse combos drive most delays
3. **Grow South region** operations — highest ROI region
4. **Diversify customer base** — reduce top-3 customer revenue dependency
5. **Renegotiate shipping costs** — weakly correlated with profit, room to optimize

---

## 👤 Author

**Jismon George**

[![GitHub](https://img.shields.io/badge/GitHub-jismon--george-181717?style=flat-square&logo=github)](https://github.com/jismon-george)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
<i>Dataset: Indian Logistics Company Operations Data — Power BI Analytics Project</i>
</div>
