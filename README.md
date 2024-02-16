Global Super Stores Dashboard Project

Introduction
This project involves the creation of a dashboard aimed at providing insights from the Global Super Stores dataset. The dashboard is designed to cater to the viewpoint of a sales manager, offering key metrics and visualizations to aid in decision-making and performance evaluation.

Dataset Overview
The dataset provided for this project consists of four years of data from the Global Super Stores. It comprises three main tables:

Order Table: Contains essential information such as order ID, order date, profit, ship date, ship mode, segment, region, and additional columns.
People Table: Includes details about personnel and their associated regions.
Return Table: Contains information about returned orders, including the order ID and a column indicating whether the order was returned ('Yes' or 'No').
Data Preparation and Transformation
Utilized Power Query Editor to import and clean the data from an Excel file.
Transformed the data to ensure proper formatting and alignment.
Created additional columns:
Year Column: Derived from the order date to facilitate year-wise analysis.
Delivery Days Column: Calculated the number of days between the order date and the ship date.
Return Numerical Column: Converted the 'Return' column to numerical values (1 for 'Yes', 0 for 'No') for better analysis.
Dashboard Components
Slicer: Implemented a slicer on the year column to enable filtering by year.
Cards:
Total Sale
Total Quantity
Average Delivery Days
Total Return Orders
Charts:
Top 5 Profit-Making Products (Bar Chart)
Top 5 Loss-Making Products (Bar Chart)
Segment-Wise Sales (Pie Chart)
Region-Wise Sales (Donut Chart)
Insights Provided
The dashboard offers insights into:

Total sales, return orders, and average delivery days.
Top 5 profit-making and loss-making products.
Segment-wise and region-wise sales distribution.
Conclusion
Overall, the dashboard serves as a valuable tool for the sales manager to track performance, identify trends, and make informed decisions based on the provided metrics and visualizations.

