# 🛒 SuperStore Sales Dashboard with Forecasting - Power BI 
## 📌 Objective
This repository showcases an interactive SuperStore Sales Dashboard developed using Power BI. The primary goal is to deliver insightful visualizations and a 15-day sales forecast using time series analysis. This dashboard empowers retail decision-makers to monitor sales trends, identify profitable areas, and optimize strategies for business growth.

To contribute to the success of a business by utilizing data analysis techniques, specifically focusing on time series analysis, to provide valuable insights and accurate sales forecasting.

The project dives deep into sales data across various dimensions such as region, category, shipping mode, and customer segment—ultimately helping stakeholders make data-driven decisions.
## 📁 Dataset
The dataset used includes information on:

- **Order Details**: Order ID, Order Date, Ship Date, Ship Mode  
- **Customer Information**: Customer Name, Segment, Region  
- **Product Details**: Category, Sub-Category, Product Name  
- **Sales Metrics**: Sales, Quantity, Discount, Profit

These fields are used to generate key metrics, forecast future sales, and uncover actionable business insights.
## 🛠️ Tools Used
- **Power BI** – for data visualization and dashboard development.
- **Power Query** – for data cleaning and transformation.
- **DAX** – for creating calculated columns, KPIs, and time-based measures.
## 🧹 Data Cleaning & Transformation (Power Query)
The raw dataset underwent the following cleaning and transformation steps using Power Query:

- Removed duplicates and corrected inconsistent date formats
- Filled missing values in critical columns
- Converted data types to appropriate formats (e.g., dates, numbers)
- Created new columns for time-based analysis (Year, Month, Week)
- Filtered irrelevant or erroneous entries
- Merged & structured tables for efficient data modeling

These steps ensured that the data was ready for accurate visualization and forecasting.

## 📊 Dashboard Visualizations
The dashboard includes the following components:
### 📊 Key Metrics & Insights

- **Total Sales**: $1.6M
- **Total Profit**: $175K
- **Total Orders**: 22K
- **Avg. Shipping Time**: 4 days

### 📈 Charts & Insights

| 📊 **Chart Type**         | 📌 **Graph Name**                      | 💡 **Insight** |
|--------------------------|----------------------------------------|----------------|
| **Donut Chart**          | **Payment Mode Distribution**          | 43% of the customers prefer **Cash on Delivery (COD)** as their payment method |
| **Donut Chart**          | **Sales by Region**                    | **West** region accounts for the highest sales at **33%** |
| **Donut Chart**          | **Sales by Segment**                   | **Consumer segment** dominates with nearly **48%** of total sales |
| **Bar Chart**            | **Sales by Category**                  | **Office Supplies** leads with sales of **$640K**, though profit margins vary |
| **Column Chart**         | **Sales by Sub-Category**              | **Phones** sub-category tops the list with over **$173K** in sales |
| **Bar Chart**            | **Sales by Ship Mode**                 | **Standard Class** shipping is most used, generating around **$33K** in sales |
| **Area Chart**           | **Sales by Month**                     | Seasonal peak observed during **November–December**, aligning with holiday sales |
| **Area Chart**           | **Profit by Month**                    | Profit trends follow similar seasonality, peaking in **Q4** |
| **Forecast Line Chart**  | **15-Day Sales Forecast**              | Predicts a stable trend with around **$3K daily sales** in the upcoming period |
| **Map Chart**            | **Sales & Profit by State**            | Highlights **California** and **New York** as the most profitable states based on sales distribution |
### 🔃 Interactive Filters
- **Region Filter**: central , East , West , South
  
### 🔍 Detailed Insights:
- **Top Region**: West (33% of sales)
- **Top State**: California ($340K sales)
- **Top Segment**: Consumer (48%)
- **Top Category**: Office Supplies ($640K)
- **Top Sub-Category**: Phones ($200K)
- **Top Ship Mode**: Standard Class (0.33M)

### 📈 Trend Observations:
- **Sales peak in Nov-Dec** (holiday season)
- **Profit fluctuates**, not always aligned with high sales
- **COD dominates (43%)** as payment method
- **15-Day Sales Forecast** predicts ~3K daily sales

## 🖼️ Screenshots of the Dashboard
1. Overview of the Dashboard 
![Overview](https://github.com/akanshagupta211/SuperStore-Sales-Dashboard/blob/main/Visualizations(screenshots)/Overview.png)
2. Central Region
   ![Overview](https://github.com/akanshagupta211/SuperStore-Sales-Dashboard/blob/main/Visualizations(screenshots)/Central%20Region.png)
3. Western Region
 ![Overview](https://github.com/akanshagupta211/SuperStore-Sales-Dashboard/blob/main/Visualizations(screenshots)/Western%20Region.png)
4. southern region
   ![Overview](https://github.com/akanshagupta211/SuperStore-Sales-Dashboard/blob/main/Visualizations(screenshots)/Southern%20Region.png)
5. Eastern region
   ![Overview](https://github.com/akanshagupta211/SuperStore-Sales-Dashboard/blob/main/Visualizations(screenshots)/Eastern%20Region.png)
6. 15-Day Forecast
   ![Overview]https://github.com/akanshagupta211/SuperStore-Sales-Dashboard/blob/main/Visualizations(screenshots)/15-days%20Sales%20forecasting.png)
> Screenshots is stored in `Visualizations(screenshots)/` folder for reference.
## 🚀 How to Use
1. Download the PBIX file from this repo.
2. Open in Power BI Desktop.
3. Interact with the filters, slicers, and visualizations to explore the insights.
## 📌 Conclusion
This HR Dashboard enables organizations to:
- Identify key drivers of employee attrition
- Monitor job satisfaction across roles
- Segment employees by salary, age, and tenure for better engagement strategies

It helps HR teams make data-driven decisions and enhance employee retention programs.

## 📫 Contact
For queries, suggestions, or collaboration opportunities, feel free to connect via [LinkedIn](#www.linkedin.com/in/akansha-gupta-b649a2216) or [Email Me](mailto:akanshabkg@gmail.com
).

---

This allows users to explore insights specific to each region and analyze performance trends more effectively.
⚠️ **Note**: This dashboard is part of a **data analysis project** and is not based on live or real-time business data.
