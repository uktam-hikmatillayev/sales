# sales
An interactive Sales Performance Dashboard built with Power BI, PostgreSQL, and DAX to analyze 60,000 sales records, track key business KPIs, and uncover actionable insights across products, regions, and sales channels for data-driven decision-making.
# 📊 Sales Performance Dashboard

## 📌 Project Overview

This project is an end-to-end sales analytics solution developed using **PostgreSQL, Power BI, and DAX**. It analyzes 60,000 sales records to evaluate business performance, monitor key performance indicators (KPIs), and identify opportunities for business growth.

The interactive dashboard enables business owners and decision-makers to analyze sales performance across different products, regions, categories, sales channels, and time periods.

## 🎯 Project Objectives

- Monitor overall sales performance and profitability.
- Analyze monthly revenue and profit trends.
- Identify top revenue-generating products.
- Evaluate sales performance across different regions.
- Compare online and offline sales channels.
- Support data-driven business decision-making.

## 🛠️ Tools & Technologies

| Technology | Purpose |
|---|---|
| PostgreSQL | Database management and data storage |
| SQL | Data extraction and transformation |
| Power BI | Data visualization and interactive dashboard development |
| DAX | Business calculations and KPI measures |
| Data Modeling | Star schema and table relationships |
| GitHub | Project documentation and version control |

## 🗄️ Dataset & Data Model

The dataset contains **60,000 sales records** and includes information about sales transactions, products, customers, branches, payment methods, and sales channels.

The data model follows a **Star Schema** architecture, consisting of one central fact table and six dimension tables.

### Fact Table

- `Fact_Sales`

### Dimension Tables

- `Dim_Date`
- `Dim_Product`
- `Dim_Customer`
- `Dim_Branch`
- `Dim_Channel`
- `Dim_Payment`

One-to-many relationships are established between the dimension tables and the fact table to enable efficient filtering and analysis.

## 📈 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | 278.46 Billion |
| Total Gross Profit | 48.79 Billion |
| Profit Margin | 17.52% |
| Total Orders | 38K |
| Quantity Sold | 74K |
| Average Order Value | 7.30 Million |

Custom DAX measures were developed to calculate these business indicators dynamically.

Revenue and gross profit calculations account for sales, returns, cancellations, discounts, and product costs where applicable.

## 📊 Dashboard Features

### 1. Monthly Revenue & Profit

A line chart that displays monthly revenue and gross profit trends, helping identify changes in sales performance over time.

### 2. Revenue by Category

A donut chart that illustrates the contribution of each product category to total revenue.

- Electronics: 79.34%
- Home Appliances: 20.66%

### 3. Top 5 Products

A horizontal bar chart that identifies the five highest revenue-generating products.

| Product | Revenue |
|---|---:|
| Apple Smartphone 23 | 6.06B |
| Acer Laptop 15 | 5.73B |
| Realme Smartphone 20 | 5.41B |
| Dell Laptop 06 | 5.21B |
| Samsung Smartphone 01 | 4.73B |

### 4. Revenue by Region

A column chart that compares sales revenue across different regions of Uzbekistan.

Tashkent City leads with approximately 97 billion in revenue, followed by Samarkand and Fergana.

### 5. Sales by Channel

A donut chart that evaluates the revenue contribution of different sales channels.

- Offline Store: 54.7%
- Online Website: 30.5%
- Marketplace: 14.8%

### 6. Interactive Filters

The dashboard includes six interactive slicers:

- Year
- Month
- Region
- Category
- Channel
- Payment

These filters allow users to explore specific business segments and dynamically update dashboard results.

## 💡 Key Business Insights

- Electronics is the dominant product category, contributing 79.34% of total revenue.
- Tashkent City generates approximately 35% of overall revenue.
- Offline stores remain the largest sales channel.
- Digital sales channels collectively contribute 45.3% of total revenue.
- Apple Smartphone 23 is the highest revenue-generating product.
- The business achieves a gross profit margin of 17.52%.

## 🚀 Business Recommendations

- Optimize inventory based on product demand and profitability.
- Expand and improve digital sales channels.
- Investigate growth opportunities in high-revenue regions.
- Analyze the causes of low revenue in underperforming regions.
- Review product costs and discount strategies to improve profit margins.
- Compare monthly performance within individual years to identify reliable seasonal trends.

## 🖼️ Dashboard Preview

![Sales Performance Dashboard](assets/dashboard.png)

## 🧠 Skills Demonstrated

- SQL and relational databases
- Business intelligence
- Data modeling and star schema design
- DAX calculations
- KPI development
- Interactive data visualization
- Sales and profitability analysis
- Business reporting
- Data storytelling

## ⚠️ Analytical Notes

- Total Profit represents gross profit rather than net profit.
- Operating expenses and taxes are not included in the gross profit calculation.
- Revenue rankings do not necessarily represent profitability rankings.
- Monthly results should be analyzed by individual year because the dataset covers different numbers of months across years.

## 📝 Conclusion

This project demonstrates how raw transactional data can be transformed into meaningful business insights through database management, data modeling, analytical calculations, and interactive visualization.

The dashboard provides a centralized view of business performance and supports informed strategic and operational decisions.

## 👨‍💻 Author

**Uktam Hikmatillayev**

Aspiring Data Analyst | SQL | Power BI | Python | Business Intelligence

GitHub: [oktam1020](https://github.com/oktam1020)

---

⭐ If you find this project useful, feel free to star the repository.
