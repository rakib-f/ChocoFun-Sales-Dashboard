## ChocoFun Sales Dashboard

### Project Overview
At first, data is transformed using the Power Query Editor. Then, proceeded with data modeling, establishing relationships between tables, writing DAX measures, and creating calculated columns. A date table is made using DAX. Visuals are set up including slicers, card visuals, donut charts, maps, column charts, matrices and tables. It also has AI visuals and buttons for navigation.

### Visualizations

### 1. Sales Overview
This page provides a high-level summary of sales performance, including comparisons to previous years, regional performance, and top products.

### Key Metrics and Visualizations
- **Sales Selected Year vs. Previous Year**:
  - **Description**: **Bar chart** comparing monthly sales for the selected year against the previous year.
  - **Insight**: Identifies trends and seasonal patterns in sales performance.

- **Orders, Sales, and Profit Summary**:
  - **Orders**: Total number of orders.
  - **Sales**: Total sales amount.
  - **Profit**: Total profit amount.
  - **Insight**: Quick view of overall performance metrics.

- **Sales vs. Profit of Top 10 Products**:
  - **Description**: **Table** displaying total sales and profit for the top 10 products.
  - **Insight**: Highlights the most profitable products and their contribution to total sales.

- **Total Orders by Region**:
  - **Description**: **Pie chart** showing the distribution of orders across different regions (Midwest, Northeast, South, West).
  - **Insight**: Helps identify the most active regions in terms of order volume.

- **TotalLineSales and Profit Percentage by Name (Map)**:
  - **Description**: **Map** visualizing sales and profit percentages by location.
  - **Insight**: Geographical distribution of sales and profit.

### Interactive Filters
- **Month Filter**: Allows users to filter data by specific months.
- **Year Filter**: Allows users to filter data by specific years (2022, 2023, 2024).
- **Product Filter**: Allows users to filter data by specific products.
- **Region Filter**: Allows users to filter data by specific regions (Midwest, Northeast, South, West).

### 2. Orders Overview
This page allows for detailed analysis of orders, including filtering top customers, distribution system and order flow.

### Interactive Filters
- **Month Filter**: Allows users to filter data by specific months.
- **Year Filter**: Allows users to filter data by specific years (2022, 2023, 2024).
- **Product Filter**: Allows users to filter data by specific products.
- **Region Filter**: Allows users to filter data by specific regions (Midwest, Northeast, South, West).

### Key Metrics and Visualizations
- **Top Customers by Sales and Profit**:
  - **Description**: The top 5 customers by sales and profit are shown in **clustered bar chart**.
  - **Insight**: Identifies the most valuable customers in terms of revenue and profitability.

- **Total Orders by Warehouse Code**:
  - **Description**: The total number of orders placed by the warehouse is shown in a **donut chart**.
  - **Insight**: Shows the distribution of order volume across different warehouses.

- **Warehouse Sales**:
  - **Description**: A chart showing the percentage of total orders placed by each warehouse.
  - **Insight**: Visualizes the contribution of each warehouse to total order volume, highlighting key distribution centers.

- **Order Flow**:
  - **Description**: A **Decomposition Tree** displays the flow of orders from warehouses to customers.
  - **Insight**: Visualizes the distribution of orders.

- **A Narative**:
  - **Description**: Displays 3 key insights provided by the AI.

### Insights and Analysis
- **Seasonal Sales Trends**: The dashboard reveals significant sales peaks during certain months, indicating seasonal demand.
- **Regional Performance**: The Northeast and South regions show the highest order volumes, suggesting strong market presence in these areas.
- **Product Profitability**: Turkish delight and Toffee are among the top-performing products in terms of both sales and profit.
- **Growth Opportunities**: Identifying regions with lower sales can help in strategizing marketing efforts to boost sales in those areas.

### Setup and Usage
1. **Power BI Desktop**: Ensure you have Power BI Desktop installed on your computer.
2. **Data Source**: Connect the Power BI file to your data source. Ensure the data source includes all necessary fields such as dates, sales, profit, product descriptions, and regions.
3. **Refresh Data**: Refresh the data in Power BI to ensure the dashboard reflects the latest information.
4. **Filters**: Utilize the interactive filters to explore the data based on specific months, years, products, and regions.
