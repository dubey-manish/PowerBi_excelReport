# Fresh Chocos Sales Performance Report.  

## Problem Statement
This Power BI report provides an analysis of the sales performance of individual salespersons and the sales team. It tracks total sales at both individual and team levels, evaluates sales performance globally, and examines the sales of different products such as Chocolate Bars and Chocolate Bites. The report aims to help management make data-driven decisions by identifying top-performing salespersons, understanding sales trends, and optimizing strategies for better revenue generation.

## Steps Followed
1. **Data Collection**: Gathered sales data, including salesperson details, product sales, and regional sales figures.
2. **Data Cleaning & Transformation**: Cleaned and formatted the data in Power Query for consistency and accuracy.
3. **Data Modeling**: Established relationships between tables for efficient reporting.
4. **DAX Calculations**: Used DAX to calculate:
   - Total Amount sold by each salesperson
   - Total Boxes sold
   - Amount per Box
5. **Report Visualization**: Created interactive Power BI dashboards with charts and tables to analyze sales performance globally and by product.

## Useful Insights
- **Top Performers**: Identifies the best-performing salespersons based on total sales.
- **Sales Trends**: Shows trends in sales performance over time, helping to identify peak sales periods.
- **Regional Performance**: Provides insights into which global regions are generating the highest sales.
- **Product Performance**: Analyzes the sales of different products (e.g., Chocolate Bars, Chocolate Bites) to determine which are most profitable.
- **Team Performance**: Evaluates the collective success of the sales team and highlights areas for improvement.

## Useful DAX Queries
```DAX
-- Total Amount Sold
Total_Amount = SUM(Sales[Amount])

-- Total Boxes Sold
Total_Boxes = SUM(Sales[Boxes])

-- Amount per Box
Amount_Per_Box = DIVIDE([Total_Amount], [Total_Boxes], 0)
```

## How to Use This Report  
- Open the **.pbix** file in Power BI Desktop.  
- Interact with the visuals to explore sales trends and individual performance.  
- Use filters to analyze specific salespersons, products, or time periods.  

## Conclusion
This Power BI report provides a comprehensive analysis of sales performance, helping stakeholders track individual and team achievements, optimize sales strategies, and drive better business decisions.

---

