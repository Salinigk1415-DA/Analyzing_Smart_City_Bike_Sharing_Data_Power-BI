
## Analyzing Smart City Bike Sharing Data
## Project Overview
The project is a data analysis initiative built using Power BI to track and visualize business performance metrics. The primary goal is to provide stakeholders with actionable insights through an interactive dashboard that monitors sales, performance trends, and key business indicators.
## Dataset Description
The dataset comprises several relational tables structured to support business intelligence reporting:
* Sales/Fact Table: Contains core transactional data, including sales amounts, quantities, and dates.
* Dimension Tables: Includes detailed attributes for products, geography (location), and time (Date table) to allow for multi-dimensional filtering.
* Customer Information: Data regarding customer demographics and segments.

## Data Preparation & Transformation
The data underwent a rigorous cleaning process using Power Query (M language) to ensure accuracy:
* Data Cleaning: Removed duplicates, handled null values, and corrected data types for consistency.
* Merging & Appending: Combined disparate data sources into a unified schema for analysis.
* Calculated Columns: Created custom columns to categorize data, such as grouping sales into specific performance tiers.

## Data Modeling
The project utilizes a Star Schema to optimize performance and usability:
* Relationships: Established one-to-many relationships between the central fact table and peripheral dimension tables.
* DAX Measures: Developed complex measures using Data Analysis Expressions (DAX), including:
* Total Sales: Sum of the sales amount.
* Year-to-Date (YTD): Cumulative sales from the start of the year.
* Year-over-Year (YoY) Growth: Comparing current performance against the previous year.

## Tools and Technologies
* Power BI Desktop: For report development and data modeling.
* Power Query: For ETL (Extract, Transform, Load) processes.
* DAX: For advanced calculations and business logic.
* Visualizations: Utilized a variety of charts, including line charts for trends, bar charts for comparisons, and KPI cards for high-level summaries.

## Analysis and Insights
* Sales Trends: Identified seasonal peaks and troughs in sales performance over the reported period.
* Top Performers: Pinpointed high-performing products and regions that contribute the most to the bottom line.
* Efficiency Metrics: Analyzed profit margins and volume trends to identify areas for operational improvement.

## Conclusion
The project successfully transforms raw business data into a professional-grade analytical tool. By leveraging Power BI's modeling and visualization capabilities, the assignment demonstrates a comprehensive understanding of the full data analysis lifecycle-from data ingestion to the communication of strategic insights.
## Screenshort
<img width="1166" height="663" alt="Bike-stations-sharing-Data Power BI Screenshort" src="https://github.com/user-attachments/assets/411882b2-30c1-4bb8-90a6-50929e6ef740" />
## Tages

PowerBI #DataAnalytics #DataVisualization #DashboardDesign #DataAnalysis #PowerQuery #DAX #DataModeling #Report #MicrosoftPowerBI

