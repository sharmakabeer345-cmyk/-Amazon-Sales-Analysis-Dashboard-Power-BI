# -Amazon-Sales-Analysis-Dashboard-Power-BI
# 📊 Amazon Sales Analysis Dashboard | Power BI


An interactive Power BI dashboard that tracks Amazon sales performance across time, product categories and customer reviews. It gives a single view of year-to-date and quarter-to-date sales, best-selling products and review trends.

## 🖼️ Dashboard Preview

## 🎯 Business Objective

Sales teams and managers need to answer a few questions quickly:
- How are sales performing this year and this quarter?
- Which months and weeks drive the most revenue?
- Which product categories contribute the most to sales?
- Which products lead in sales, and which lead in customer reviews?

This dashboard answers all of these in one page.

## 📌 Key Metrics (KPIs)

| KPI | Description |
|---|---|
| YTD Sales | Total sales from the start of the year to date |
| QTD Sales | Total sales from the start of the quarter to date |
| YTD Products Sold | Total number of products sold this year to date |
| YTD Reviews | Total customer reviews received this year to date |

## 📈 Dashboard Features

- **KPI Cards**: YTD Sales, QTD Sales, YTD Products Sold and YTD Reviews at a glance
- **Sales by Month**: area chart showing the monthly sales trend
- **Sales by Week**: column chart showing weekly sales movement
- **Sales by Product Category**: table comparing YTD and QTD sales for each category
- **Top 5 Products by YTD Sales**: the best-selling products
- **Top 5 Products by YTD Reviews**: the most-reviewed products
- **Slicers**: filter the report by Product Category and Quarter

## 🗂️ Data Model

- **Fact table:** `Amazon_Data` (product category, product description, price in dollars, reviews)
- **Dimension table:** `Date Table` (month name, week, quarter) used for time-based analysis
- **DAX measures:** YTD Sales, QTD Sales, YTD Products Sold, YTD Reviews

## 🛠️ Tools & Skills

- Power BI Desktop
- DAX (time intelligence measures)
- Data Modeling
- Data Visualization & Dashboard Design
- Business Analytics

## 📁 Repository Structure

```

## ▶️ How to Open the Project

1. Install **Power BI Desktop** (free from the Microsoft Store or the Microsoft website)
2. Download `AMAZON_SALES_ANALYSIS.pbix` from this repository
3. Open the file in Power BI Desktop
4. Use the slicers to explore sales by Product Category and Quarter

## 👤 Author

**Kabeer Sharma**
MBA (Finance & Business Analytics)

⭐ If you found this project useful, consider giving the repository a star.
