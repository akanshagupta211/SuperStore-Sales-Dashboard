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

### ✅ KPI Cards:

- **Total Sales**: $1.6M
- **Total Profit**: $175K
- **Total Orders**: 22K
- **Average Shipping Time**: 4 days
  
### 📈 Charts & Insights

| 📊 **Chart Type**         | 📌 **Graph Name**                      | 💡 **Insight** |
|--------------------------|----------------------------------------|----------------|
| **Donut Chart**          | **Sales by Payment Mode**              | 43% of the customers prefer **Cash on Delivery (COD)** as their payment method. |
| **Donut Chart**          | **Sales by Region**                    | **West** region accounts for the highest sales at **33%**.|
| **Donut Chart**          | **Sales by Segment**                   | **Consumer segment** dominates with nearly **48%** of total sales. |
| **Column Chart**         | **Sales by Sub-Category**              | **Phones** sub-category tops the list with over **$173K** in sales. |
| **Bar Chart**            | **Sales by Category**                  | **Office Supplies** leads with sales of **$640K**, though profit margins vary. |
| **Bar Chart**            | **Sales by Ship Mode**                 | **Standard Class** shipping is most used, generating around **$33K** in sales. |
| **Area Chart**           | **Sales by Month**                     | Seasonal peak observed during **November–December**, aligning with holiday sales. |
| **Area Chart**           | **Profit by Month**                    |Profit trends show peaks in **April 2019** and **December 2020**, with steadier performance throughout 2020.|
| **Map Chart**            | **Sales & Profit by State**            | Highlights **California** and **New York** as the most profitable states based on sales distribution. |
|**Horizontal Bar Chart**  | **Sales by State**	                    |**California** leads with **~$340K** in sales, followed by New York and Texas.|
| **Forecast Line Chart**  | **15-Day Sales Forecast**              | Predicts a stable trend with around **$3K daily sales** in the upcoming period. |

### 🎯 Interactive Filters : 
- **Region Filter**: central , East , West , South

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
   ![Overview](https://github.com/akanshagupta211/SuperStore-Sales-Dashboard/blob/main/Visualizations(screenshots)/15-days%20Sales%20forecasting.png)
> Screenshots is stored in `Visualizations(screenshots)/` folder for reference.

## 📌 Conclusion
The SuperStore Sales Dashboard serves as a powerful analytical tool, enabling data-driven decisions through clear insights into sales performance, customer behavior, and upcoming trends. It helps businesses optimize strategies and improve overall performance.
- **Top Region & State**: West region and California lead in sales.
- **High-Performing Areas**: Office Supplies and Phones are the top category and sub-category.
- **Customer & Delivery Trends**: Consumer segment and Standard Class ship mode dominate sales.
- **Sales & Profit Trends**: Peaks in Nov–Dec (holiday season); profit spikes in Apr 2019 and Dec 2020.
- **Forecast Insight**: 15-day prediction shows steady sales of around 3K per day.

## 🚀 How to Use
1. Download the PBIX file from this repo.
2. Open in Power BI Desktop.
3. Interact with the filters, slicers, and visualizations to explore the insights.
   

## 📫 Contact
For queries, suggestions, or collaboration opportunities, feel free to connect via [LinkedIn](#www.linkedin.com/in/akansha-gupta-b649a2216) or [Email Me](mailto:akanshabkg@gmail.com
).
