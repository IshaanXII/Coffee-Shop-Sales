☕ Coffee Shop Sales Analysis Dashboard


📌 Project Overview
The main objective of this project is to analyze retail sales data for a coffee shop to gain actionable insights that will enhance its overall business performance. By leveraging advanced Excel features, this project transforms raw transactional data into a visual story that identifies peak sales periods, customer preferences, and store-specific performance.




📊 Key Business Questions Addressed
The dashboard was designed to answer several critical business questions:


Sales Trends: How do sales vary by day of the week and hour of the day? 


Peak Activity: What are the peak times for sales activity? 


Revenue Analysis: What is the total sales revenue for each month? 


Store Performance: How do sales vary across different store locations (Astoria, Hell's Kitchen, Lower Manhattan)? 


Order Metrics: What is the average price/order per person? 


Product Performance: Which products and categories (e.g., Bakery, Coffee, Tea) are the best-selling in terms of quantity and revenue? 

🛠️ Technical Tools Used
To handle large datasets and create a dynamic user experience, I utilized several advanced Excel features:

Power Query Editor: For data cleaning, transformation, and shaping.

Power Pivot: To build a robust data model and handle complex relationships between tables.

Pivot Tables & DAX: For performing detailed calculations like "Average Order Value" and "Total Foot Fall."

Advanced Visualizations:

Slicers: Interactive filters for MonthWise_Sales and DayWise_Sales to allow users to drill down into specific time periods.

Dynamic Charts: Pie charts for category distribution, bar charts for store-wise footfall, and line graphs for hourly trends.

📈 Dashboard Insights (Snapshot)
Based on the analysis, the coffee shop achieved:

Total Sales: $698,812.33

Total Foot Fall: 149,116 customers

Average Order Value: 4.68

Best Sellers: "Brewed Chai tea" and "Barista Espresso" rank among the top 5 categories.

📂 Repository Structure
Coffee_Final_Project.xlsx: The main Excel file containing the Power Pivot model and the interactive dashboard.

Dashboard_Screenshot: The Screenshot of the Dashboard.

CoffeeShop_Raw.xlsx: Contains the raw dataset.

🚀 How to Use
Download the .xlsx file from this repository.

Open the file in Microsoft Excel (ensure Power Pivot is enabled).

Use the Slicers on the left side of the dashboard to filter the data by month or day and watch the visualizations update in real-time.

💡 Conclusion
The Coffee Shop Sales Analysis project successfully transformed raw transactional data into a strategic tool for operational efficiency. Key findings from the analysis include:

Performance Leaders: Astoria and Hell's Kitchen emerged as the highest-performing locations in terms of both footfall and total revenue.

Product Strategy: Beverage categories like "Barista Espresso" and "Brewed Chai tea" are significant revenue drivers, suggesting that marketing efforts should remain focused on these high-margin items.

Operational Timing: Sales activity peaks significantly on Fridays, providing a clear indicator for when to increase staffing levels to maintain service quality.

Business Impact: By utilizing the interactive slicers, stakeholders can now monitor the Average Order Value ($4.68) and Total Foot Fall (149,116) in real-time to measure the success of promotional campaigns.

🚀 Future Improvements
To further evolve this project and deepen the insights, the following enhancements are planned:


Predictive Analytics: Implement time-series forecasting using Python or Excel’s Forecast Sheet to predict future sales trends based on historical data.



Advanced Customer Segmentation: Use clustering algorithms to group customers based on their purchasing behavior (e.g., "Daily Commuters" vs. "Occasional Visitors").

Automated Data Pipeline: Transition the data source from static files to a live SQL database (MySQL/DB2) to automate the refresh process via Power Query.

Visualization Migration: Scale the dashboard to Power BI or Tableau to incorporate more complex geographical mapping and mobile-friendly viewing.


Sentiment Analysis: Integrate customer feedback data and perform sentiment analysis to correlate sales dips with service or product satisfaction levels.
