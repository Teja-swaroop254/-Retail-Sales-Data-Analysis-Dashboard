# Retail Sales Data Analysis & Dashboard

This project provides a complete end-to-end analysis of retail sales data.  
It includes data loading, cleaning, outlier detection, exploratory data analysis (EDA), and dashboard-style visualizations to uncover insights such as top-performing categories, customer behavior, and sales trends.

The analysis is performed inside the notebook:

- **_Retail Sales Data Analysis & Dashboard.ipynb**

Dataset required:

- **retail_store_sales.csv**

---
```python
##  Project Structure

├── _Retail Sales Data Analysis & Dashboard.ipynb
├── retail_store_sales.csv
└── README.md
```
---


#  Analysis Workflow

This project follows a structured workflow to ensure clean, meaningful analysis.

---

## **1. Data Loading & Inspection**

### ✔ Tasks Performed
- Load the CSV dataset
- Display the first few rows of data
- Show dataset shape (rows & columns)
- List all available columns
- Identify:
  - **Categorical columns**
  - **Numerical columns**
  - **Datetime columns**

---

## **2. Data Cleaning**

Cleaning ensures that data is ready for accurate analysis.

### ✔ Cleaning Steps
- Handle missing values using mode/median
- Remove the **"Discount Applied"** column due to high missing percentage
- Standardize categorical values (strip spaces, apply title case)
- Convert datatypes:
  - Numeric: Price Per Unit, Quantity, Total Spent
  - Date: Transaction Date
  - Category: Category, Payment Method, Location
- Remove duplicate records (if any)

---

## **3. Outlier Detection**

Outliers can distort results, so they are checked and analyzed.

### ✔ Methods Used
- **IQR (Interquartile Range)** outlier detection
- Boxplot visualization
- Distribution plots (histograms)

### ✔ Variables Checked
- Price Per Unit  
- Quantity  
- Total Spent  

---

## **4. Exploratory Data Analysis (EDA)**

The heart of the project — understanding the data using univariate and bivariate analysis.

---

### **Univariate Analysis**

#### ✔ Numerical Column Analysis
- Distribution of **Price Per Unit**
- Distribution of **Quantity**
- Distribution of **Total Spent**

#### ✔ Categorical Column Analysis
- Category counts
- Payment method frequency
- Location frequency

---

### **Bivariate Analysis**

Examining relationships between variables.

#### ✔ Category Relationships
- **Category vs Payment Method**
- **Category vs Location**

#### ✔ Sales & Price Patterns
- **Price Per Unit vs Total Spent** (scatter plot)
- **Quantity vs Total Spent** (scatter plot)

#### ✔ Time-Based Analysis
- Monthly sales trend using Transaction Date

#### ✔ Business KPIs
- Average Total Spent by Location
- Revenue contribution by Category

---

## **5. Visualizations (Dashboard Elements)**

A complete set of visualizations is created to form a dashboard-like analytical experience.

### ✔ Visuals Included
- Countplots
- Bar Charts
- Boxplots
- Scatter Plots
- Heatmaps (correlation matrix)

These visual elements help stakeholders quickly understand performance and behavior patterns.

---

#  Sample Insights

Below are examples of insights observed from the data:

### ✔ Business Insights
- Some product categories consistently generate the **highest revenue**.
- Most customers prefer **Digital Wallet** and **Credit Card** as payment methods.
- Certain store locations perform significantly better in **revenue** and **quantity sold**.
- Some categories are **price-sensitive**, while others rely on **high quantity purchasing**.
- Monthly sales trends show **seasonal patterns** and periods of increased demand.

---





