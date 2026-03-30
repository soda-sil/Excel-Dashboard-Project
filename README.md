# 📊 Bike Buyers Sales Dashboard — Excel Project

## 📌 Project Overview

This project covers a full data analysis workflow in Microsoft Excel, from raw data to an interactive dashboard. 

Using a real-world dataset of 1,000+ customer records, the goal was to clean the data, explore it through Pivot Tables, and build a dynamic dashboard that reveals the key demographic factors influencing bike purchases.

## 📂 Dataset

- **Source:** Bike Buyers Dataset from AlexTheAnalyst
- **Rows:** 1,026 records (1,000 after removing duplicates)
- **Columns:** ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, Purchased Bike


## 🛠️ Tools Used

- **Microsoft Excel:** data cleaning, Pivot Tables, charts, and dashboard


## 🔍 Project Workflow

1. **Data Cleaning (Working Sheet)**
    - Preserved the original raw data by working on a separate sheet
    - Removed 26 duplicate rows using Excel's Remove Duplicates tool
    - Replaced abbreviated values: M → Married / S → Single, M → Male / F → Female
    - Changed the Income column data type from General to Currency
    - Created a new Age Brackets column using a nested IF formula to group ages

2. **Pivot Tables & Charts**
    - Built three Pivot Tables to answer key business questions:Do higher earners buy more bikes? Does proximity affect bike buying? Which age group buys the most bikes?

3. **Interactive Dashboard**
    - Combined all three charts into a single clean dashboard
    - Added Slicers to allow dynamic filtering by: Marital Status, Region, Education


## 📈 Key Insights

- **Income:** Male customers earned more on average and purchased more bikes. Higher income correlates with bike purchases across both genders
- **Commute Distance:** Customers with the shortest commute (0–1 miles) purchased the most bikes
- **Age:** Middle-aged customers (31–55) were the most likely to purchase a bike
- **Region:** North America had the highest number of bike buyers


## 💡 Key Excel Skills Demonstrated

- **Data Cleaning:** Remove Duplicates, Find & Replace, data type formatting
- **Nested IF:** Age bracket classification
- **Pivot Tables**: Aggregating and summarizing data
- **Pivot Charts:** Bar, line, and column visualizations
- **Slicers:** Interactive dashboard filtering
- **Dashboard Design:** Combining charts into a single view

## 📁 Repository Structure

├── README.md

└── data/

│    └── Project - Excel Dataset to Dashboard.xlsx    # Full workbook with all sheets and dashboard

## 🚀 How to Reproduce

1. Download bike_buyers_dashboard.xlsx
1. Open in Microsoft Excel
1. Navigate through the sheets: bike_buyers → Working Sheet → Pivot Table → Dashboard
1. Use the slicers on the Dashboard sheet to filter and explore the data interactively

## 🖼️ Dashboard Preview
<img width="957" height="653" alt="Excel - Dashboard Preview" src="https://github.com/user-attachments/assets/aa12a830-2300-4efb-ac6f-e1aa14fdfe6d" />


## 👤 Author

### Sofia Costa

https://www.linkedin.com/in/sofiassvcosta/

https://github.com/soda-sil
