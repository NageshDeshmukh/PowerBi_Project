## DASHBOARD LINK : 
https://app.powerbi.com/groups/8fea09f6-ecec-4362-a845-c901e7895240/dashboards/89fc5582-ee0e-41dd-b15a-542ed71641aePowerBi

## BlinkIT Grocery Analysis Dashboard - Power BI 

This project is an interactive Power BI dashboard designed to analyze sales performance, 
customer satisfaction, and inventory distribution for Blinkit, an online grocery shopping platform owned by Zomato. 
 
# Project Overview  
This Power BI dashboard provides insights into **BlinkIT Grocery Sales Data** with interactive visualizations.  
It includes key metrics like **Total Sales, Avg Sales, No. of Items, and Avg Rating**, along with **item-wise analysis, outlet performance, and sales trends**.  

---

## Work Completed  

### Loaded Dataset into Power BI**
- Imported **BlinkIT Grocery Data** from a excel file into Power BI.
- Opened **Power Query Editor** to inspect data quality.
- Removed **duplicates and null values** from key columns.
- Changed data types for numeric and categorical fields.
- Applied **basic transformations** (renaming columns, formatting values).
- Clicked **Close & Apply** to load clean data into Power BI.

---

###  Data Modeling & Relationships**
- Verified the **data model** in the **Model View**.  
- Ensured that the dataset had a structured format with **proper column naming**.
- No relationships were needed as data came from a single table.

---

### Created Key DAX Measures & Calculations**
Used **DAX (Data Analysis Expressions)** to create key metrics:
- **Total Sales** → `SUM(BlinkIT_Grocery_Data[Sales])`
- **Avg Sales** → `AVERAGE(BlinkIT_Grocery_Data[Sales])`
- **No. of Items** → `DISTINCTCOUNT(BlinkIT_Grocery_Data[Item Identifier])`
- **Avg Rating** → `AVERAGE(BlinkIT_Grocery_Data[Rating])`
- **% of Total Sales** → `DIVIDE([Total Sales], SUMX(ALL(BlinkIT_Grocery_Data), BlinkIT_Grocery_Data[Sales]))`
- **Total Items by Type** → `COUNT(BlinkIT_Grocery_Data[Item Type])`

---

### Created Dashboard Visualizations**
Added **interactive visuals** to represent the data insights:

#### **KPI Cards**

- **Total Sales ($1.20M)**  
- **Avg Sales ($141)**  
- **No. of Items (8523)**  
- **Avg Rating (3.9)**  

#### **Charts & Graphs**

- **Bar Chart** → Item Type vs. Sales  
- **Pie Chart** → Fat Content Distribution  
- **Line Chart** → Sales Trend by Year  
- **Donut Chart** → Outlet Size Distribution  
- **Table/Matrix** → Outlet Type vs. Sales, Avg Sales & Rating  

#### **Filters & Slicers**

- **Outlet Location** (Tier 1, Tier 2, Tier 3)  
- **Outlet Size** (Small, Medium, Large)  
- **Item Type**  

---

### Applied Conditional Formatting & Interactivity**

- Highlighted **highest sales** using **color-coded bars**.  
- Used **conditional formatting** in tables to differentiate outlet sales.  
- Enabled **tooltips** to display additional insights.  
- Applied **cross-filtering** between visuals for better interaction.  

---

### Final Testing & Optimization**

- Verified calculations and corrected any inconsistencies.  
- Optimized **performance** by removing unnecessary columns.  
- Ensured **visual consistency** for a clean and professional look.  

---

### Published & Shared Dashboard**

- Saved the **Power BI (.pbix) file** for future modifications.  
- Published the report to **Power BI Service** for online access.  
.
