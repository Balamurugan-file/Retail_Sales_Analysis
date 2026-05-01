# Retail Sales Analysis of an Electronics Store in Myanmar (2020–2023)

A comprehensive data analysis project to evaluate sales performance across categories, regions, customers, and time using Python and Power BI.

---

## 📖 Table of Contents
- Project Overview  
- Data Source  
- Tools & Technologies  
- Data Cleaning & Preparation  
- Exploratory Data Analysis (EDA)  
- Key Insights  
- Recommendations  
- How to Use 

---

## 📊 Project Overview

This project analyzes retail sales data from an electronics store in Myanmar between 2020 and 2023.

**Goals:**
- Identify key business drivers
- Understand customer behavior
- Evaluate regional performance
- Uncover time-based sales patterns
- Support data-driven decision-making

---

## 🗂️ Data Source

- **Source:** Kaggle
- **Time Period:** 2020 – 2023
- **Dataset Description:**
This dataset contains retail sales records for Electronics Retails Analysis, a consumer electronics retailer in Myanmar. It covers transactions from 2020 to 2023 across various regions.


### Key Variables:
| Variable | Description |
|----------|-------------|
| Date | Transaction date |
| Product, Category | Product details |
| Price, Quantity, Discount | Financial metrics |
| Sales Channel, Payment Method | Transaction details |
| Customer Type, Customer Rating | Customer info |
| Region, Delivery Days | Location & logistics |

---

## 🛠️ Tools & Technologies

| Category | Tools |
|----------|-------|
| **Language** | Python (Pandas, NumPy) |
| **Visualization** | Matplotlib, Seaborn |
| **Dashboard** | Power BI |
| **Documentation** | Google colab, MS Word |

---

## 🧹 Data Cleaning & Preparation

### Cleaning Steps:
- ✅ Standardized date format (YYYY-MM-DD)
- ✅ Removed invalid records (non-positive quantities)
- ✅ Cleaned Price column (removed currency symbols → numeric)
- ✅ Filled missing Discount values (group median)
- ✅ Standardized categorical columns (Region, Sales Channel)
- ✅ Handled missing values (mode for categorical, median for numerical)
- ✅ Treated outliers (clipping method)

### Feature Engineering:
- Gross Sales (MMK) = Price × Quantity
- Net Sales (MMK) = Gross Sales - Discount
- Net Sales (USD) = Net Sales (MMK) / Exchange Rate


---

## 🔍 Exploratory Data Analysis (EDA)

**Key questions explored:**
- Sales performance by category?
- Highest revenue-generating region?
- Customer type impact on sales?
- Monthly/yearly sales trends?
- Popular payment methods & sales channels?

---

## 💡 Key Insights

1. **📱 Electronics dominates** (~72% revenue)
2. **🔌 Accessories** high volume, low revenue (~5%)
3. **🏙️ Yangon leads** (~1.5M sales)
4. **👑 VIP customers** most valuable segment
5. **📉 2023 decline** observed
6. **🗺️ Regional contraction** (6→4 regions)
7. **💳 Mobile Pay** most preferred

---

## 🚀 Recommendations

| Priority | Action | Expected Impact |
|----------|--------|-----------------|
| High | Focus Electronics category | Revenue growth |
| High | Accessories promotions | Margin improvement |
| High | VIP loyalty programs | Customer retention |
| Medium | Expand Yangon strategies | Regional balance |
| Medium | Improve low-performers (Magway, Tanintharyi) | Market expansion |
| Medium | Time-based promotions | Sales uplift |
| Medium | Strengthen online channels | Channel diversification |
| Low | Promote Mobile Pay | Transaction efficiency |

---

## ⚙️ How to Use

### Prerequisites
- Python 3.8+
- Power BI Desktop


### Quick Start
```bash
# 1. Clone the repository
https://github.com/Balamurugan-file/Retail_Sales_Analysis
cd retail-sales-analysis-myanmar

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn

# 3. Run Google colab
Retail Sales Analysis of an Electronics Store in Myanmar (2020–2023).ipynb

# 4. Open Power BI Dashboard
Retail_Sales_Dashboard.pbix
```
---

## ⭐ Conclusion

This project demonstrates **end-to-end data analytics skills**:
- Data cleaning & preparation
- Advanced EDA with Python
- Interactive Power BI dashboards
- Actionable business insights

**Skills Gained:**
Python (Pandas, NumPy, Matplotlib, Seaborn)
Power BI (DAX, Visualizations)
Data Cleaning & Business Intelligence
