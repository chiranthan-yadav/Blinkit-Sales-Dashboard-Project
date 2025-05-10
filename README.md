#  Blinkit Sales Dashboard – Power BI Project

This project is a real-time interactive **Power BI dashboard** built using transactional data from Blinkit (a grocery delivery platform). The project mimics real business scenarios and aims to uncover key performance insights using **DAX, visuals, and KPI tracking**.

---

##  Dashboard Overview

The dashboard provides a high-level summary of the following key metrics:

-  **Total Sales:** `$1.20M`
-  **Average Sales:** `$141`
-  **Number of Items Sold:** `8523`
-  **Average Customer Rating:** `3.9/5`

---

##  Key Features

###  KPIs
- Total Sales
- Average Sales per Order
- Total Number of Items
- Average Rating

###  Visualizations Used
- **KPI Cards** – Highlight real-time metrics
- **Stacked Column Chart** – Sales vs Items by Category
- **Line Chart** – Trend of Sales over Time
- **Pie/Donut Chart** – Sales by Region or Outlet
- **Bar Charts** – Best-selling items or categories

###  DAX Measures
Some of the important DAX formulas used:

```dax
Total Sales = SUM(Sales[Amount])
Average Sales = AVERAGE(Sales[Amount])
Total Items = SUM(Sales[Quantity])
Average Rating = AVERAGE(Customer[Rating])

THANK YOU- 
