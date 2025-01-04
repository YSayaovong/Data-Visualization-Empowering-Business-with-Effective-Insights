# **Online Retail Data Analysis**

## **Project Overview**
This project demonstrates my ability to clean, analyze, and visualize data using Python. The dataset represents transactions from an online retail store, and the analysis focuses on addressing key business questions posed by the CEO and CMO. The project showcases data cleaning, transformation, and insightful visualizations using Pandas, Matplotlib, and Seaborn. 

---

## **Key Objectives**
The analysis was conducted to answer the following business questions:

### **For the CEO:**
1. **Time Series Analysis**: Analyze monthly revenue trends for the year 2011 to identify seasonal trends and forecast future performance.
2. **Product Demand by Region**: Identify regions (excluding the UK) with the highest product demand to guide expansion strategies.

### **For the CMO:**
3. **Top 10 Countries by Revenue**: Determine the top 10 countries (excluding the UK) by revenue and quantity sold.
4. **Top 10 Customers by Revenue**: Identify the highest revenue-generating customers for targeted retention strategies.

---

## **Project Workflow**

### **1. Data Cleaning**
The dataset required significant preprocessing:
- Removed rows with invalid quantities (less than 1) and unit prices (less than $0).
- Added a new column to calculate revenue:  
  `Revenue = Quantity * UnitPrice`.

### **2. Data Visualization**
Created visualizations to address each business question:
- **Time Series Analysis**: Monthly revenue trends for 2011.
- **Top 10 Countries by Revenue**: Revenue and quantity sold for countries excluding the UK.
- **Top 10 Customers by Revenue**: A ranked bar chart of the highest revenue-generating customers.
- **Product Demand by Region**: A bar chart showing demand (quantity sold) by country, excluding the UK.

---

## **Tools Used**
- **Languages**: Python
- **Libraries**:
  - Data Processing: Pandas, NumPy
  - Data Visualization: Matplotlib, Seaborn
- **Platform**: Google Colab

---
