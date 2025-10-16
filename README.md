# excel-dashboard
This Excel dashboard visualizes amazon sales department efficiency using interactive charts and tables.
📊 Amazon Sales Dashboard (Excel)

This project is an interactive Excel Dashboard designed to analyze and visualize Amazon sales data. It includes KPIs, charts, and filters for easy insights into sales performance.
 1. Project Overview
The Amazon Sales Dashboard helps track:
Total Sales, Profit, Quantity Sold
Sales by Region, Category, and Sub-Category
Top Performing Products and Customers
Monthly and Yearly Trends

 2. Dataset Description
The dataset includes columns such as:
Order ID
Order Date
Region
Category
Sub-Category
Sales
Profit
Quantity
Customer Name
3. Steps to Create the Dashboard
Step 1: Import the Data
1. Open Excel.
2. Go to Data → Get Data → From File → From Workbook / CSV.
3. Load the Amazon sales dataset into Excel.
Step 2: Clean the Data
Check for missing or duplicate entries.
Convert Order Date to Date format.
Ensure numeric columns (Sales, Profit, Quantity) are formatted correctly.

Step 3: Create a Pivot Table
1. Select the entire dataset.
2. Go to Insert → PivotTable.
3. Create multiple PivotTables for:
Sales by Category
Profit by Region
Monthly Sales Trends
Top 10 Products by Sales

Step 4: Insert Charts
Use Pivot Charts or Standard Charts:
Column Chart → Sales by Category
Line Chart → Monthly Sales Trend
Pie Chart → Region-wise Sales Share
Bar Chart → Top Products

Step 5: Add Slicers and Timelines
1. Click on PivotTable → Insert Slicer → Choose fields (e.g., Region, Category).
2. Add Timeline for Order Date.
3. Connect slicers to all PivotTables (use Report Connections).

Step 6: Design the Dashboard
Move charts and slicers to one sheet called Dashboard.
Add titles, background color, and labels.
Align visuals neatly for a clean layout.

Step 7: Final Touches
Add KPIs (using formulas or cards):
Total Sales = SUM(Sales)
Total Profit = SUM(Profit)
Total Quantity = SUM(Quantity)
Add filters for better interactivity.

4. How to Use
Open the Excel file (Amazon_Sales_Dashboard.xlsx).
Use slicers and timelines to explore sales insights dynamically.

5. Upload to GitHub
Steps to upload:
1. Create a new repository on GitHub (example: amazon-sales-dashboard).
2. Click Upload files → Add your Excel file (Amazon_Sales_Dashboard.xlsx).
3. Add a README.md file (this guide).
4. Commit changes → Done!

6. Dashboard Preview
(You can add a screenshot here)
 
7. Tools Used
Microsoft Excel
Pivot Tables, Pivot Charts
Data Cleaning and Visualization

 
