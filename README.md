# Regional Sales Analysis & Interactive Power BI Dashboard

## 📊 Interactive Dashboard Demo

This animated demo shows the final Power BI dashboard in action, including filtering by channel, region, and customer.

![Power BI Sales Dashboard Demo](dashboard_demo.gif)

---

## 🚀 Project Overview

The goal of this project is to analyze 2014-2018 sales data from "Northwind Traders company" to identify key revenue and profit drivers. The analysis focuses on uncovering trends across products, channels, and regions to provide actionable insights for optimizing pricing, promotions, and market expansion.

---

## 🛠️ Tools & Technologies

* **Python:** Used for all data cleaning, transformation, and exploratory data analysis (EDA).
    * **Libraries:** pandas, numpy, matplotlib, seaborn
* **Google Colab:** The notebook environment for running the Python analysis.
* **Power BI:** Used for building the final interactive dashboard.

---

## 📈 Analysis & Key Findings

The analysis was performed in the `Sales Analysis.ipynb` notebook and included:

* **Data Cleaning & Integration:** Merged 6 different datasets (Sales, Customers, Products, Regions, etc.) into a single, clean master file.
* **Feature Engineering:** Created new columns for `total_cost`, `profit`, and `profit_margin_percentage` to enable deeper financial analysis.
* **Exploratory Data Analysis (EDA):** Used pandas and seaborn to investigate key questions:
    * What are the overall monthly sales trends?
    * Who are the Top 10 products by revenue?
    * How does sales distribution break down by channel?
    * What is the average profit margin for each channel?
    * Who are the Top 10 customers by revenue?

---

## 📁 Repository Files

* **[Sales Analysis.ipynb](Sales Analysis.ipynb):** The complete Google Colab notebook containing all Python code for data cleaning, feature engineering, and EDA.
* **[sales_data.csv](sales_data.csv):** The final, cleaned CSV file exported from the notebook, which is used as the data source for the Power BI dashboard.
* **[dashboard_demo.gif](dashboard_demo.gif):** The animated demo of the final dashboard (as seen above).
