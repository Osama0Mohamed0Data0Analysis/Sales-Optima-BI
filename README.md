# 📊 Sales Performance & Logistics Power BI Dashboard

An end-to-end Business Intelligence project analyzing sales, product performance, customer behavior, and shipping logistics.

## 🚀 Project Overview
This project transforms raw retail and online sales data into actionable business insights using Power BI. It features a complete relational data model, advanced DAX measures, and interactive dashboards to monitor executive KPIs, sales rep targets, and regional shipping costs.

## 🗂️ Data Architecture & Tables (`Sales.xlsx`)
The relational model consists of 7 interconnected tables:
1. **Orders**: Transaction records, order/shipping/delivery dates, payment methods, and foreign keys.
2. **Orders_details**: Quantities sold, discounts, profits, and taxes per line item.
3. **Products**: Categories, sub-categories, product names, and unit costs.
4. **Customers**: Customer demographics, types (Retail/Online), and historical sales.
5. **Sales_Reps**: Employee details, hire dates, annual salaries, and annual sales targets.
6. **Shipping**: Geographic details (Postal code, City, State, Region) and unit shipping costs.
7. **Return**: Tracking returned orders and return dates.

## 📈 Key Dashboard Pages & KPIs
* **Executive Overview**: Total Sales, Net Profit, Return Rates, and Delivery Durations.
* **Product & Category Performance**: Best/worst performing products and profit margins by category.
* **Sales Reps Performance**: Actual sales vs. Annual Targets (`Annual Target`).
* **Shipping & Logistics**: Regional cost analysis and delivery efficiency.

## 🛠️ Tools & Technologies Used
* **Power BI Desktop**: Data modeling, DAX, and interactive visualizations.
* **Excel / Python (Pandas)**: Data extraction, transformation, and validation.
* **GitHub**: Version control and project documentation.
