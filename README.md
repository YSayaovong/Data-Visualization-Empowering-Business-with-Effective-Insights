# **Online Retail Analysis and Visualization**

## **Overview**
This project demonstrates the use of **Python** (via Jupyter Notebook) and **Tableau** to analyze and visualize an online retail dataset. The project is focused on cleaning, analyzing, and presenting actionable insights to address business questions posed by the CEO and CMO of a retail company.

---

## **Objective**
The project aimed to:
1. Clean and preprocess raw data for error-free analysis.
2. Create meaningful insights through statistical analysis and visualization.
3. Present findings tailored to business questions related to:
   - Revenue trends (Time Series).
   - Regional sales performance.
   - High-value customers.
   - Product demand across regions.

---

## **Accomplishments**

### **1. Data Cleaning (Python in Jupyter Notebook)**
- Removed invalid data:
  - Excluded rows with negative quantities (returns).
  - Excluded rows with zero or negative unit prices (data entry errors).
- Calculated new metrics:
  - Created a `Revenue` field using the formula: `Revenue = Quantity * Unit Price`.
- Exported the cleaned dataset for further analysis in Tableau.

### **2. Visualization Creation (Tableau)**
Developed four distinct visualizations in Tableau to answer the business questions:

#### **Visualization 1: Monthly Revenue Trends for 2011**
- Analyzed monthly revenue for 2011.
- Revealed seasonal spikes in November and December, indicating high holiday demand.

#### **Visualization 2: Top 10 Countries by Revenue (Excluding UK)**
- Identified the top 10 countries contributing the most revenue, excluding the United Kingdom.
- Highlighted the correlation between quantity sold and revenue in these regions.

#### **Visualization 3: Top 10 Customers by Revenue**
- Pinpointed the top 10 customers contributing the highest revenue.
- These customers were identified as key targets for retention strategies.

#### **Visualization 4: Product Demand by Country (Excluding UK)**
- Ranked regions (excluding the UK) by product demand based on quantities sold.
- Provided insights for global expansion opportunities.

---

## **Tools and Technologies Used**

### **1. Python (Jupyter Notebook)**
- **Libraries**:
  - `Pandas`: Data cleaning, filtering, and aggregation.
  - `Matplotlib` and `Seaborn`: Data visualization (initial explorations).
- **Key Features**:
  - Cleaning raw data for valid and accurate analysis.
  - Exporting the processed dataset for visualization in Tableau.

### **2. Tableau**
- **Features Used**:
  - Calculated fields for metrics (e.g., Revenue).
  - Filters to exclude irrelevant data (e.g., UK, invalid values).
  - Visualizations:
    - Line charts for time series.
    - Bar charts for rankings.
    - Heatmaps for demand distribution.
- **Output**:
  - Packaged Workbook (`Online_Retail_Analysis.twbx`) containing all visuals.

---

## **Key Learnings**
- **Data Cleaning**: Ensuring data quality is crucial for meaningful analysis.
- **Visualization Best Practices**:
  - Tailoring visuals to the audience (CEO vs. CMO needs).
  - Simplifying complex data for clarity and impact.
- **Actionable Insights**: Aligning technical work with business objectives to support decision-making.

---

## **Project Deliverables**
1. **Jupyter Notebook**: [Creating_Effective_Visuals.ipynb](./Creating_Effective_Visuals.ipynb)
   - Data cleaning and preprocessing steps.
2. **Tableau Workbook**: [Online_Retail_Analysis.twbx](./Online_Retail_Analysis.twbx)
   - Packaged Tableau file with four business-focused visualizations.
