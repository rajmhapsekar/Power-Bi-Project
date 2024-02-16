<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Global Super Stores Dashboard Project</title>
</head>
<body>
    <h1>Global Super Stores Dashboard Project</h1>

    <h2>Introduction</h2>
    <p>This project involves the creation of a dashboard aimed at providing insights from the Global Super Stores dataset. The dashboard is designed to cater to the viewpoint of a sales manager, offering <strong>key metrics</strong> and <strong>visualizations</strong> to aid in decision-making and performance evaluation.</p>

    <h2>Dataset Overview</h2>
    <p>The dataset provided for this project consists of four years of data from the Global Super Stores. It comprises three main tables:</p>
    <ul>
        <li><strong>Order Table:</strong> Contains essential information such as order ID, order date, profit, ship date, ship mode, segment, region, and additional columns.</li>
        <li><strong>People Table:</strong> Includes details about personnel and their associated regions.</li>
        <li><strong>Return Table:</strong> Contains information about returned orders, including the order ID and a column indicating whether the order was returned ('Yes' or 'No').</li>
    </ul>

    <h2>Data Preparation and Transformation</h2>
    <p>Utilized Power Query Editor to import and clean the data from an Excel file. Transformed the data to ensure proper formatting and alignment. Created additional columns:</p>
    <ul>
        <li><strong>Year Column:</strong> Derived from the order date to facilitate year-wise analysis.</li>
        <li><strong>Delivery Days Column:</strong> Calculated the number of days between the order date and the ship date.</li>
        <li><strong>Return Numerical Column:</strong> Converted the 'Return' column to numerical values (1 for 'Yes', 0 for 'No') for better analysis.</li>
    </ul>

    <h2>Dashboard Components</h2>
    <ul>
        <li><strong>Slicer:</strong> Implemented a slicer on the year column to enable filtering by year.</li>
        <li><strong>Cards:</strong> Total Sale, Total Quantity, Average Delivery Days, Total Return Orders</li>
        <li><strong>Charts:</strong> Top 5 Profit-Making Products (Bar Chart), Top 5 Loss-Making Products (Bar Chart), Segment-Wise Sales (Pie Chart), Region-Wise Sales (Donut Chart)</li>
    </ul>

    <h2>Insights Provided</h2>
    <p>The dashboard offers insights into:</p>
    <ul>
        <li>Total sales, return orders, and average delivery days.</li>
        <li>Top 5 profit-making and loss-making products.</li>
        <li>Segment-wise and region-wise sales distribution.</li>
    </ul>

    <h2>Conclusion</h2>
    <p>Overall, the dashboard serves as a valuable tool for the sales manager to track performance, identify trends, and make informed decisions based on the provided metrics and visualizations.</p>
</body>
</html>

