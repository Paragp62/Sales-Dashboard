# Sales-Dashboard
Simple Sales Dashboard

Objective

The objective of this project is to create an interactive dashboard to visualize and analyze sales performance of mobile phones and laptops over time, by region, and by product category.

The dashboard helps identify trends and key drivers of sales to support data-driven decision making, following best practices in data visualization.


Tools Used

Power BI Desktop: Used for data import, modeling, and creating the interactive dashboard visuals.

Python (Pandas): (Optional) Utilized for initial data cleaning and transformations before importing the dataset into Power BI.

DAX (Data Analysis Expressions): Used within Power BI to create calculated columns or measures if needed for metrics like total sales.


Dataset Description

File: mobile_sales.csv – a CSV file containing sales transaction records for mobile and laptop products.

Columns: Fields include Date (order date), Region (e.g., East, Central, West), Category (Mobile or Laptop), and Sales (sales amount).

Content: The dataset simulates sales transactions, providing monthly sales data broken down by region and product category. It may also include additional details like product specifications or customer information if available.


Steps Taken

Data Import: Loaded the mobile_and_laptop_sales.csv file into Power BI Desktop.

Data Cleaning: Checked for missing or inconsistent values and ensured correct data types (e.g. dates parsed as dates, numeric sales values).

Data Transformation: Converted the Order Date to a "Month-Year" format to facilitate time-based aggregation. Created any calculated columns or measures (for example, total monthly sales).

Visualization: Created the following visuals in Power BI:

Line Chart: Plotted total sales over time (month-year).

Bar Chart: Compared sales totals across regions.

Donut Chart: Showed sales share by product category (Mobile vs. Laptop).

Slicer: Added a slicer/filter for Region to allow interactive filtering of all charts.


Design: Applied consistent colors, labels, and titles to ensure the dashboard is clear and user-friendly.


Dashboard Features

Line Chart (Sales over Months): Displays the trend of total sales over each month. Line charts are effective for showing how values change over time.

Bar Chart (Sales by Region): Compares total sales for each geographic region. Bar charts are ideal for comparing values across categories.

Donut Chart (Sales by Category): Illustrates the proportion of sales contributed by each product category (Mobile vs. Laptop). Donut charts (a variant of pie charts) highlight parts of a whole.

Region Slicer: An interactive filter control that allows the user to select one or more regions. This slicer narrows the data displayed in all charts, making it easy to focus on a specific region.

Dynamic Interaction: All visuals are interconnected. Selecting a region in the slicer automatically updates the line, bar, and donut charts to reflect the filtered data.


Key Insights

Regional Performance: The West region drove the strongest growth in sales during Q3, while the East region maintained high overall sales throughout the year. (This suggests targeted marketing or seasonal demand in different regions.)

Category Dominance: Mobile devices consistently outsold laptops, indicating that the mobile product category contributes the majority of total revenue.

Seasonal Trend: Sales steadily increased as the year progressed, with a peak in December (likely reflecting holiday season demand).

Upward Trend: The line chart shows an overall upward trend in sales over the year, implying overall growth in sales performance.


How to Use

1. Open Report: Launch Power BI Desktop and open the Simple_Sales_Dashboard.pbix report file.


2. Interact with Slicer: Use the Region slicer on the left to filter the dashboard by any combination of East, Central, and West.


3. View Updates: Observe that the line, bar, and donut charts update automatically based on the selected region(s).


4. Hover for Details: Hover over any data point in the visuals to see exact values and additional details (e.g. specific sales figures or month).


5. Export or Print: The dashboard can be exported to PDF or images via Power BI for sharing.



File Structure


Simple_Sales_Dashboard.pbix — Power BI report file containing the dashboard.

dashboard.png — Screenshot of the dashboard (visual overview).

dashboard.pdf — PDF export of the dashboard (for easy sharing).

README.md — This documentation file.

Additional analysis or script files (if any) can be included here.


Author and Credits

Parag

Credits:

Dashboard designed using Power BI Desktop (Microsoft).

Dataset or sample data is based on public sales data examples (for example, Kaggle or other open datasets).

Chart design and best practices reference: Microsoft Power BI documentation.



