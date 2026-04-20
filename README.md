# 📊 Amazon Sales Intelligence Dashboard (Power BI)

## 🔍 Project Overview

This project presents an end-to-end data analysis solution using **Power BI** to explore Amazon sales data.
The dashboard provides insights into **sales performance, product trends, customer behavior, geographic distribution**, and **month-over-month (MoM) growth patterns**.

The goal of this project is to transform raw sales data into actionable business insights using **data cleaning, modeling, and visualization techniques**.

---

## 🚀 Key Features

### 📈 Sales Performance Overview

* Total Revenue, Total Orders, and Average Order Value (AOV)
* Yearly revenue trend analysis
* Revenue contribution by product category
* Identification of top-performing product, customer, and country

---

### 🛍️ Product Performance Insights

* Highest performing products by revenue
* Lowest performing products
* Product ranking with revenue, quantity, and AOV
* Category-wise revenue distribution

---

### 👥 Customer Behavior Analysis

* Top customers by revenue
* Customer segmentation (Low, Medium, High value)
* Customer spending distribution
* Average customer spend analysis

---

### 🌍 Geographic Sales Analysis

* Revenue distribution by country (Tree Map)
* Map visualization for global sales
* Top revenue-generating cities
* Top 5 states by revenue contribution

---

### 📊 MoM Performance & Trend Analysis

* Monthly revenue trend (seasonal pattern)
* Category performance vs previous month (MoM)
* Current vs previous month revenue comparison
* Identification of growth and decline drivers

---

## 🧠 Key Business Insights

* February shows a consistent seasonal dip across all years
* December typically records peak sales, but 2024 shows a decline (~8%)
* MoM growth for Dec 2024 is **-5.15%**, indicating a short-term drop from November
* The decline is primarily driven by weaker performance in key categories (e.g., Clothing)
* This may indicate reduced year-end demand or incomplete sales data for 2024

---

## 🛠️ Tools & Technologies

* **Power BI** – Dashboard development & visualization
* **DAX (Data Analysis Expressions)** – Measures and calculations
* **Python (Pandas)** – Data cleaning & preprocessing
* **Power Query** – Data transformation
* **Data Modeling** – Relationships & schema design

---

## 🐍 Data Cleaning (Python)

Data preprocessing was performed using Python (Pandas) before importing into Power BI:

* Removed missing values and duplicates
* Converted date columns into proper datetime format
* Created new columns (Year, Month)
* Ensured data consistency for analysis

---

## 📂 Project Structure

```
amazon-sales-dashboard-powerbi/
│
├── Amazon_Sales_Dashboard.pbix
├── dataset.csv
├── cleaned_data.csv
│
├── python/
│   └── data_cleaning.py
│
├── screenshots/
│   ├── overview.png
│   ├── product.png
│   ├── customer.png
│   ├── region.png
│   ├── mom_analysis.png
│
└── README.md
```

---

## 📸 Dashboard Preview

### 1️⃣ Sales Performance Overview

![Overview](screenshots/overview.png)

### 2️⃣ Product Performance Insights

![Product](screenshots/product.png)

### 3️⃣ Customer Behavior Analysis

![Customer](screenshots/customer.png)

### 4️⃣ Geographic Sales Analysis

![Region](screenshots/region.png)

### 5️⃣ MoM Performance & Trend Analysis

![MoM](screenshots/mom_analysis.png)

---

## ⚙️ How to Use

1. Download the `.pbix` file
2. Open using **Power BI Desktop**
3. Use slicers (Year, Category, Month) to explore insights
4. Navigate across pages using the sidebar icons

---

## 🎯 Business Value

This dashboard helps stakeholders:

* Monitor overall sales performance
* Identify top and underperforming products
* Understand customer purchasing behavior
* Analyze regional revenue concentration
* Detect trends and anomalies in monthly performance

---

## 👤 Author

**Jeeva Nandham**
Aspiring Data Analyst

---

## ⭐ If you found this useful

Give this repo a ⭐ and feel free to connect!


