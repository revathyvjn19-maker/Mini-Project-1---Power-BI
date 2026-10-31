# Mini-Project-1---Power-BI
E-Commerce Sales Analysis using Power BI

# E-Commerce Sales Analysis using Power BI

**Data Modelling and DAX**

•	Created a new Date Table using DAX.

Syntax 
**Date table = ADDCOLUMNS(CALENDAR(MIN('Sales Data'[Order Date]),MAX('Sales Data'[Order Date])),"Year",YEAR([Date]),"month Number",MONTH([Date]),"month name",FORMAT([Date],"MMM"),"Quarter","Q"&QUARTER([Date]),"Day",DAY([DATE]))**

•	Established relationship between the Date Table and Sales Data.

•Created calculated measures for sales, profit, and orders.

•	Added a calculated column called Product Type.
# Dashboard Pages and Visualizations

**1. Sales Overview**

•	KPI cards for Total Sales, Total Profit, and Total Orders.

•	Bar chart for Sales by Category.

•	Bar chart for Sales by Region.

•	Line chart for Monthly Sales Trends.

•	Slicers for Category, Year, and Region.

**2. Sales Trend Analysis**

•	Line chart for Total Sales by Year and Month.

•	Line chart for Total Profit by Year and Month.

•	Bar chart for Total Sales by Year.

•	Column chart for Total Sales by Year and Quarter.

•	Slicer for Year.

**3. Product and Category Analysis**

•	Scatter chart to compare Total Sales and Total Profit by Sub-Category and Region.

•	Stacked bar chart for Sales and Profit by Category.

•	Treemap for Sales by Category.

•	Summary table for Category-wise Sales and Profit.

•	Slicer for Category.

**4. Regional Sales Analysis**

•	Donut chart for Sales by Region.

•	Funnel chart for Sales by City.

•	Column chart to compare Sales and Profit by Region.

•	Map to display Sales by City and Region.

•	Matrix to show Regional Sales, Profit, and Orders.
