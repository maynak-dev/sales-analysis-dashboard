Sales Data Analysis Dashboard – Power BI & Excel

Overview:
An interactive dashboard built in Power BI to analyze and visualize sales data across products, regions, and customer segments. The dashboard provides insights into total revenue, top-performing products, and month-over-month growth trends. Data cleaning and transformation were performed in Excel before connecting to Power BI.

Folder Structure:
sales-analysis-dashboard/

│

├── data/

│   ├── sales_data_raw.csv

│   ├── cleaned_sales_data.xlsx

│

├── reports/

│   ├── IT_Sales_Performance.pbix

│   ├── KPI_Report_Snapshot.png

│

├── docs/

│   ├── Data_Model_Structure.png

│   ├── README_Notes.txt

│

└── README.md

Features:
- Data cleaning and formatting using Excel formulas and filters
- Power BI dashboard with dynamic KPIs (Revenue, Profit, Customer Growth)
- Interactive slicers by region, category, and time period
- Visualizations: bar charts, pie charts, line trends, and tree maps
- DAX measures for growth rate and YoY comparisons

Tech Stack:
- Power BI
- Microsoft Excel
- Power Query, DAX

Setup Instructions:
1. Clone this repository:
   git clone https://github.com/maynak-dev/sales-analysis-dashboard.git
2. Open cleaned_sales_data.xlsx in Excel for data understanding.
3. Open IT_Sales_Performance.pbix in Power BI Desktop.
4. Refresh the dataset – visuals will update automatically.
5. Publish to Power BI Service (optional).

Insights Example:
- Total sales increased 15% QoQ with the Electronics segment leading.
- The South region showed highest customer retention rate.

Future Enhancements:
- Automate refresh using Power BI Gateway.
- Integrate API data (ERP or CRM) for live updates.
