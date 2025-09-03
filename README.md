<img width="1028" height="580" alt="Screenshot 2025-09-04 at 5 21 45 AM" src="https://github.com/user-attachments/assets/b46f3d94-6aba-4836-bde8-61e37007a32b" />

Here is a preview of the final dashboard. You can also view the Live Interactive Dashboard here : "https://drive.google.com/file/d/1x_NnBn1yZ5lD2ySxJ40Bs-1hjwnz-3zP/view?usp=sharing"

(Suggestion: Replace the image link above with a direct link to your dashboard screenshot in your GitHub repository for better performance).

Key Features & KPIs
The dashboard provides a detailed breakdown of sales performance through various metrics and visualizations:

KPI Cards: At-a-glance view of crucial metrics including:

Total Revenue: The sum of all sales.

Average Order Value: The average amount spent per order.

Total Pizzas Sold: The total quantity of pizzas sold.

Total Orders: The total number of distinct orders.

Average Pizzas Per Order: The average number of pizzas sold in each order.

Trend Analysis:

Daily & Monthly Order Trends: Visualizes order volume by day of the week and month, helping to identify peak hours and seasonal patterns.

Sales Performance Analysis:

Sales by Pizza Category & Size: Donut charts showing the revenue contribution of each pizza category and size.

Pizzas Sold by Category: A bar chart comparing the total quantity of pizzas sold across different categories.

Product Analysis (Best & Worst Sellers):

Identifies the Top 5 and Bottom 5 pizzas based on Revenue, Total Quantity Sold, and Total Orders, providing insights into product popularity and performance.

Tools and Technologies Used
Database: MySQL (for data storage and querying)

Querying & Database Management: Azure Data Studio

BI & Visualization Tool: Microsoft Power BI

Data Source: Flat File (.csv)

Project Workflow
Data Loading: The initial pizza sales data was provided in a CSV format and was imported into a MySQL database to create a structured dataset.

Data Analysis & Aggregation: All business logic and calculations were performed directly within MySQL. I wrote a series of SQL queries to aggregate the data and calculate the specific metrics needed for each visual in the dashboard (e.g., calculating total revenue, grouping sales by day, finding the top 5 best-selling pizzas).

Data Export: The result of each SQL query was exported as a separate, pre-processed CSV file. This approach was chosen to optimize the performance of the Power BI report and to handle the development on a macOS environment.

Data Modeling in Power BI: The exported CSV files were loaded into Power BI. Each file served as a distinct table, ready for visualization without the need for complex DAX calculations in Power BI.

Dashboard Development: The dashboard was designed and built in Power BI, creating a user-friendly interface with various interactive visuals like KPI cards, bar charts, line charts, and donut charts to present the insights derived from the SQL queries.
