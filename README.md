
#  Inventory Optimization Dashboard with Power BI

This Power BI project delivers an insightful analysis of product-level inventory data aimed at helping supply chain and procurement teams ensure stock continuity, reduce shortages, and optimize replenishment strategies. The dashboard transforms raw data into a dynamic visual interface that enables better forecasting, supplier management, and location-based inventory planning.

---

## 📊 Project Summary

Built in Power BI, this dashboard highlights:

- Low inventory alerts
- Supplier delivery performance
- Inventory distribution by region
- Reordering and stock turnover behavior

These insights empower warehouse managers and logistics coordinators to prevent fulfillment issues, streamline restocking, and maintain availability of fast-moving goods.

---

## 📁 Data Description

The dataset includes the following key fields:

| Column               | Description                                      |
|----------------------|--------------------------------------------------|
| Product_ID           | Unique product identifier                        |
| Product_Name         | Name of the product                              |
| Category             | Product category (e.g., Books, Electronics)      |
| Unit_Price           | Price per item                                   |
| Stock_Quantity       | Current number of units in stock                 |
| Stock_Level          | Categorized level: Low, Medium, High             |
| Reorder_Point        | Threshold that signals reordering is needed      |
| Lead_Time_Days       | Delivery time from supplier                      |
| Last_Restock_Date    | Last date the product was restocked              |
| Supplier_ID          | Unique identifier for each supplier              |
| Warehouse_Location   | Warehouse city                                   |
| Min_Order_Quantity   | Minimum quantity required for reorder            |
| Status               | Product status: Active or Discontinued           |
| Entry_Date           | Date product entered the inventory system        |
| Country              | Country of the warehouse                         |
| Latitude / Longitude | Geo coordinates of warehouse location            |

---

## 🧾 Executive Summary

- **Category Analysis**: Home & Garden, Office Supplies, and Books maintain high inventory levels. However, Home & Garden also experiences the most stockouts, indicating replenishment gaps.
- **Reorder Risk**: Books and Office Supplies are frequently below reorder points, calling for improved monitoring systems.
- **Regional Insight**: Germany holds the highest stock levels, followed by Belgium and Spain. France has relatively fewer SKUs and stock volume.
- **Supplier Evaluation**: SUP018, SUP016, and SUP030 consistently deliver on time. SUP041 exhibits significant delays in Books and Toys.
- **Restocking Patterns**: Highest restocking activity occurs in January and May. February and August show the lowest restocking volume, potentially due to seasonal planning lags.

---

## 📸 Dashboard Snapshots

### Overview Page
![Inventory Overview](https://github.com/jotstolu/Inventory-Optimization-Dashboard-with-Power-BI/blob/main/snapshots/overview.png?raw=true)

### Supplier Insights Page
![Supplier Performance](https://github.com/jotstolu/Inventory-Optimization-Dashboard-with-Power-BI/blob/main/snapshots/supplier%20insight.png?raw=true)

### Country-Level Inventory Breakdown
![Stock by Country](https://github.com/jotstolu/Inventory-Optimization-Dashboard-with-Power-BI/blob/main/snapshots/country%20wise%20inventory.png?raw=true)

### Monthly Restocking Trends
![Restocking Trends](./screenshots/restocking_trends.png)

> 📌 Ensure your `screenshots/` folder includes these image files when uploading to GitHub.

---

## 🔍 Deep Dive Insights

- **Stock Quantity by Category**: Over 300K units held in Books, Office Supplies, and Home & Garden. However, Home & Garden also sees the largest volume of stockouts (~68K units).
- **Reorder Point Tracking**: Electronics and Clothing are generally above reorder thresholds, but Books and Office Supplies frequently fall below.
- **Restock Demand**: Books lead in restock quantity (~2,000 units), suggesting strong demand. Clothing and Office Supplies follow.
- **Inventory Turnover**: Highest in Home & Garden, Sports, and Books (~25K+ units each).
- **Supplier Delivery Times**: Most suppliers operate between 15.7 and 17.3 days. SUP041 lags behind with inconsistent delivery in multiple categories.

---

## 📅 Seasonal Restock Patterns

- High-volume restocking: January, May, September, November.
- Low restocking: February (590 units) and August (689 units).
- Notable spikes: January’s peak in Office Supplies and Clothing, December restocking in Sports and Books.

---
