# BlinkIt Sales Analysis
                                                
## Dashboard Link: 
https://app.powerbi.com/links/xTkfe7-Tus?ctid=8bf89164-b311-40ca-a295-2e0f5f39d14e&pbi_source=linkShare

## Problem Statement: 
To conduct a comprehensive analysis of Blinkit’s sales performance, customer satisfaction and inventory distribution to identify key insights and opportunities for optimization using various KPIs and visualizations in Power BI.

## KPI’s Requirements:
1.	Total Sales – The overall revenue generated from all items sold.
2.	Average Sales – The average revenue per sale
3.	Number of Items – The total count of different items sold
4.	Average Rating – The average customer rating for items sold

## Business Requirements:
1.	Total Sales by Fat Content – Analyze the impact of fat content on total sales and assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content
2.	Total Sales by Item Type –Identify the performance of different item types in terms of total sales and assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with item type
3.	Fat Content by Outlet for Total Sales – Compare total sales across different outlets segmented by fat content and assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content  
4.	Total Sales by Outlet Establishment – Evaluate how the age or type of outlet establishment impact total sales
5.	Sales by Outlet Size – Analyze the correlation between outlet size and total sales
6.	Sales by Outlet Location – Assess the geographic distribution of sales across different locations
7.	All Metrics by Outlet Type – Provide a comprehensive view of all key metrics broken down by outlet types

## Steps Followed:
1.	Data was imported to Power BI in excel format. Data quality was checked in Power Query Editor after having changed column profiling to view entire dataset and in ‘Item Fat Content’ column ‘low fat’ was changed to ‘Low Fat’ and ‘reg’ was changed to ‘Regular’ to bring all same types in a common format.
2.	The dashboard building process was started and first new measures for Total Sales, Average Sales, No of Items and Average Rating were created using DAX functions. Cards were added representing each of the values.
3.	A Donut Chart was created with filters to view fat content by various metrics provided in requirements like Total Sales, Average Sales etc.
4.	A Clustered Bar Chart was added to view Fat Content based on Outlet Type with the various metrics like Total Sales, Average Sales etc available as filters.
5.	Another Clustered Bar Chart was added to view Item Type with respect to the various metrics.
6.	An area chart was added to show the relation between Total Sales and Outlet Establishment Year.
7.	Two pie charts were added to show relation between Total Sales and Outlet Size and Outlet Location.
8.	A table was added to show all metrics by outlet type
9.	Three filters were added including Outlet Type, Outlet Size and Item Type.
10.	Finally, Dashboard was completed and published to Power BI.
    
                            

