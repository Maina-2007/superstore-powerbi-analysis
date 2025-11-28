#  Superstore Sales & Profitability Analysis – Power BI Project
## Dashboard
<img width="1274" height="690" alt="Dashboard" src="https://github.com/user-attachments/assets/021a4e74-f131-49ce-9295-807ba8fcd792" />

##  Project Overview  
This project analyzes sales performance for a fictitious retail company, **Superstore**, using interactive Power BI dashboards.  
The dataset was cleaned, normalized, and modeled into a star schema to enable efficient reporting and insights extraction.

The final dashboard highlights key business metrics (KPIs), customer behavior, geographic performance, and product profitability.

---

##  Problem Statement  
Superstore’s management needed a clear understanding of its sales and profitability performance across different customer segments, regions, and product categories.  
Although transactional data was available, it had not been cleaned, structured, or transformed into a decision-ready format.

**The business needed answers to questions such as:**

- Which customer segments contribute the most revenue and profit?  
- How do sales and profit vary across regions and states?  
- Which products or categories are underperforming?  
- What are monthly sales trends and seasonal patterns?  
- How do shipping modes affect profitability and order volume?  
- What is the company’s overall sales performance over time?

This project delivers an interactive analytical solution that addresses these needs.

---

##  Data Preparation  
The project involved comprehensive data cleaning, normalization, and modeling.

###  Data Cleaning  
- Removed duplicates  
- Corrected data types  
- Standardized date formats  
- Checked for missing values  
- Added calculated fields (e.g., profit margin)

###  Data Modeling – Star Schema  
A star schema was built consisting of:

#### **Fact Table**
- `Fact_Superstore`  
  Contains all transactional data including sales, profit, quantity, discount, customer ID, product ID, location fields, and order dates.

#### **Dimension Tables**
- `Dim_Customers`  
- `Dim_Products`  
- `Dim_Location`  
- `Dim_Calendar` (created using MIN & MAX of the *Order Date* field)

### ✔ DAX Measures  
Key measures created:

- `Total Sales`  
- `Total Profit`  
- `Profit Margin`  
- `Total Orders`  
- `Average Quantity Per Order`  
- Optional YOY calculations

---

##  Dashboard Features  
The Power BI dashboard includes:

- **KPI Cards**: Sales, Profit, Profit Margin, Total Orders, Average Quantity  
- **Sales by Segment** – Donut Chart  
- **Sales by Region** – Bar Chart  
- **Profit by Ship Mode** – Bar Chart  
- **Monthly Sales Trend** – Line/Area Chart  
- **Sales by State (Map)** – Geographic insight  
- **Interactive Slicers**: Ship Mode, Month, Region, Year  
- **Reset Slicers Button** for improved usability  

---



