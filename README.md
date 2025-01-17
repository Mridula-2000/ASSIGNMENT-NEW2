# ASSIGNMENT-NEW2
Power BI Assignment 2 submission sample repo
Tables
ASSIGNMENT-2


The Assignment-2 is about transformation using power query

#Steps Done

1. Data cleaning 

*Remove Duplicates and blank rows,correcting the column headers


2. Establish relation between 3 tables


3. Visual segmentation

*Utilize slicer visualizations to segment data by region,country,and market.

4. Shipping Analysis
*Shipping percentage by ship Mode

*A DAX formula has been applied to calculate the percentage of shipping costs based on ship Mode

DAX
*DIVIDE(SUM('Orders'[Shipping Cost]), CALCULATE(SUM('Orders'[Shipping Cost]), ALL('Orders'[Ship Mode])))

*Sales visualizations

*Sales by region(Map)
 - Use the map visualization to visually represent sales across different regions.

*Sales by City (Stacked Column Chart)

  - Analyze sales trends in various cities using the stacked column chart.

  *Sales by State (Map)

  - Visualize sales distribution across different states using the map.

  *Sales by Market(Stacked Bar Chart)

  - Understand sales performance by market through the stacked bar chart.

5.created tables for all the visualization

Tables for Detailed Information 
  - Supporting tables have been created for each visualization.



