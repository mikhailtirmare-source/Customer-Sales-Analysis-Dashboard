# Tableau Sales & Customer Dashboard

## Project Overview
This project is an interactive Tableau dashboard designed to analyze sales, profit, quantity, and customer performance across multiple dimensions including product category, sub-category, geography, and time. The dashboard provides leadership with a consolidated view of business performance to support data-driven decision making.

The solution consists of a **Sales Dashboard**, with dynamic filters for year, product, and location.

---

## Business Objective
The goal of this dashboard is to:
- Monitor overall sales, profit, and quantity trends
- Compare current year performance against the previous year
- Identify high- and low-performing product sub-categories
- Analyze geographic performance at country, state, and city levels
- Enable quick exploration through interactive filters and KPI-driven insights

---

## Datasets Used
The project is built using four datasets:
1. **Orders** – Transaction-level sales, profit, quantity, and order dates - <a herf="https://github.com/mikhailtirmare-source/Customer-Sales-Analysis-Dashboard/blob/main/Orders.csv">Dataset,</a>
2. **Customers** – Customer-level attributes and identifiers  https://github.com/mikhailtirmare-source/Customer-Sales-Analysis-Dashboard/blob/main/Customers.csv
3. **Product Category** – Category and sub-category hierarchy  https://github.com/mikhailtirmare-source/Customer-Sales-Analysis-Dashboard/blob/main/Products.csv
4. **Location** – Country/Region, State, and City details  https://github.com/mikhailtirmare-source/Customer-Sales-Analysis-Dashboard/blob/main/Location.csv

All datasets were joined and modeled inside Tableau to support analysis at multiple granularities.

---

## Data Modeling & Preparation
- Established relationships between Orders, Customers, Product, and Location datasets
- Standardized date fields for time-based analysis
- Ensured consistency of keys across datasets
- Handled nulls and missing values within calculations where applicable

---

## Key KPIs & Calculated Fields
Three primary KPIs were created using **calculated fields** and used as Tableau measures:

- Total Sales
- Total Profit
- Total Quantity

Additional calculations include:
- Year-over-Year (YoY) % Change vs Previous Year
- Highest Month and Lowest Month indicators
- Above / Below Average flags for trend analysis
- Profit vs Loss classification for sub-category analysis

These calculations drive KPI tiles, trend lines, and conditional formatting within the dashboard.

---

## Dashboard Features
### Sales Dashboard
- KPI tiles for Sales, Profit, and Quantity with YoY comparison
- Monthly trends highlighting highest and lowest performing months
- Sales & Profit by Product Sub-Category with profit/loss indicators
- Time-series trend analysis showing performance above and below average benchmarks

### Filters & Interactivity
- **Year Selector**
- **Product Filters** (Category, Sub-Category)
- **Location Filters** (Country/Region, State, City)
- Interactive selections to support focused analysis

---

## Design & Usability Considerations
- Clean layout optimized for executive consumption
- Consistent color usage for profit, loss, above, and below indicators
- KPI-focused layout to highlight key business metrics first
- Navigation between Sales and Customer dashboards

---

## Key Insights (Example)
- Profit increased despite a slight decline in overall sales
- Certain sub-categories consistently generate losses and require attention
- Sales performance varies significantly by geography
- Peak sales months do not always align with peak profit months

---

## How to Use the Dashboard
1. Download the `.twbx` file from this repository
2. Open it in Tableau Desktop
3. Use the filter panel to explore performance by year, product, or location
4. Navigate between Sales and Customer dashboards for deeper insights

---

## Future Enhancements
- Customer segmentation and lifetime value analysis
- Parameter-driven KPI comparison
- Forecasting using Tableau analytics features
- Performance optimization for larger datasets

---

## Tools Used
- Tableau Desktop
- Calculated Fields
- Dashboard Actions & Filters
