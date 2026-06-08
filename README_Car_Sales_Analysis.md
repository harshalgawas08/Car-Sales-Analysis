# 🚗 Car Sales Analysis — Power BI Analytics Dashboard

**Course Project | Big Data Technologies | University of Delaware — MS Data Science (Spring 2025)**  
**Built by Ritu Raj Sharma**

---

## 📌 Project Overview

This Power BI project analyzes a car sales dataset to understand dealership performance, customer behavior, vehicle preferences, pricing patterns, and year-over-year sales growth.

The goal of this project was not only to build dashboards, but also to turn raw sales data into clear business insights that can support decision-making for dealerships and sales teams.

Using Power BI, I cleaned and transformed the data, created interactive visual reports, and analyzed key questions related to customer income, gender-based sales, body style preferences, transmission type, and sales performance from 2022 to 2023.

---

## 📂 Repository Contents

```text
├── Car_Sales_Analysis_Dashboard.pbix      # Power BI dashboard file
├── Car_Sales_Dataset.xlsx / .csv          # Source dataset
├── Power_Bi_Car_Sales_Analysis.pdf        # Project report / dashboard screenshots
└── README.md                              # Project documentation
```

---

## 📊 Dataset Summary

| Attribute | Details |
|---|---|
| Source | Kaggle car sales dataset |
| Focus Area | Car sales and dealership performance |
| Key Fields | Car ID, Date, Customer Name, Gender, Annual Income, Dealer Name, Company, Model, Engine, Transmission, Color, Price, Dealer Region, Body Style |
| Customer Segments | Male, Female, Low Income, Medium Income, High Income |
| Vehicle Attributes | Body Style, Transmission, Engine, Company, Model, Color |
| Key Metrics | Total Sales, Average Price, Average Income, Units Sold, Year-over-Year Sales |

---

## 📋 Business Questions Answered

The dashboard was designed to answer the following business questions:

1. **Income vs. Car Price**  
   Is there a relationship between customer annual income and the price of the car purchased?

2. **Gender-Based Sales Comparison**  
   How do total sales and total units sold compare between male and female customers, and what proportion of total sales does each gender represent?

3. **Body Style Performance**  
   Which body styles contribute the most to total sales, and how do those contributions differ across regions?

4. **2022 vs. 2023 Sales Growth**  
   Did car sales in 2023 surpass total sales in 2022?

5. **Transmission and Pricing**  
   Does transmission type, Manual vs. Automatic, affect the average selling price?

---

## 🛠️ Power BI Concepts & Features Used

### Data Preparation with Power Query

- Cleaned and transformed raw sales data
- Replaced inconsistent values in the Engine column
- Removed unnecessary columns that did not add value to the analysis
- Renamed columns to make the dataset cleaner and easier to use
- Prepared the data for dashboard reporting and analysis

### DAX and Calculated Logic

- Created measures for total sales and average price
- Used calculated logic to classify customers into income groups
- Applied DAX functions such as:
  - `CALCULATE`
  - `ALL`
  - `SELECTEDVALUE`
  - `SWITCH`
- Built dynamic measures for category-level and filtered analysis

### Dashboard Design and Visualizations

- KPI cards for Total Sales, Average Price, and Average Income
- Bar charts for sales comparisons
- Donut charts for proportion analysis
- Scatter plots for income and price relationship
- Time-series visuals for 2022 vs. 2023 comparison
- Slicers for filtering by region, dealer, year, body style, income category, and transmission type
- Interactive report pages focused on business questions

---

## 🔍 Key Insights Discovered

- **2023 sales were higher than 2022 sales**, showing positive year-over-year growth.
- Total sales increased from approximately **$300.34M in 2022** to **$371.19M in 2023**, reflecting about **23.6% growth**.
- **SUVs and Hatchbacks** were among the strongest contributors to total sales.
- Customer annual income showed a relatively weak relationship with car price, suggesting that purchasing decisions are influenced by more than income alone.
- Male customers contributed a larger share of total sales compared with female customers in this dataset.
- Automatic and Manual vehicles showed only a small difference in average selling price.
- Regional differences in body style performance suggest that dealerships can better align inventory with local customer preferences.

---

## 📈 Dashboard Pages / Analysis Areas

### 1. Income Category and Price Analysis
Explores whether annual income strongly influences the price of the car purchased.

### 2. Gender-Based Sales Analysis
Compares total sales, units sold, and sales contribution between male and female customers.

### 3. Body Style Sales Analysis
Identifies which body styles generate the highest total sales and how performance changes across regions.

### 4. Year-over-Year Sales Analysis
Compares total sales between 2022 and 2023 to evaluate business growth.

### 5. Transmission-Based Price Analysis
Analyzes whether Automatic or Manual transmission vehicles have different average selling prices.

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository.
2. Open it using **Power BI Desktop**.
3. If prompted, update the dataset path to the local dataset file.
4. Refresh the report.
5. Use slicers and filters to explore the dashboard by year, region, dealer, body style, income category, and transmission type.

> Note: Power BI Desktop is required to open `.pbix` files. It is free and available from Microsoft.

---

## 🎯 Skills Demonstrated

- Power BI Dashboard Development
- Power Query Data Cleaning
- DAX Measures and Calculated Columns
- Data Visualization
- Sales Analytics
- Customer Segmentation
- Business Intelligence Reporting
- Year-over-Year Trend Analysis
- Interactive Dashboard Design

---

## 📌 Tools Used

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Excel / CSV Dataset**

---

## 👤 Author

**Ritu Raj Sharma**  
MS Data Science, University of Delaware  
Interested in Data Analyst, Business Intelligence Analyst, and Data Science roles.

---

## 🏷️ Keywords

`Power BI` `DAX` `Power Query` `Data Analytics` `Business Intelligence` `Sales Analytics` `Dashboard Design` `Data Visualization` `Customer Segmentation` `Car Sales Analysis`
