# Blinkit_Analysis_Dashboard

### Dashboard Link :  https://github.com/Nandini-1423/Blinkit_Analysis/blob/main/blinkit_dashboard.pbix


## Problem Statement

The objective of this project is to analyze the sales performance of BlinkIT Grocery stores using the provided dataset. The analysis aims to identify key trends and insights that can help the company make data-driven decisions to improve sales and profitability.

## Dataset Overview 
 hey guys!! we are going to see an amazing and interactive dashboard which is on a very famous application that is called blinket analysis which is a product of a zomato right so blinket is actually a grocery online grocery shopping store ,
 
 where you can order different items , which we are ordering from that particular app we are going to see that particular analysis of this particular , we can see this company all right so now we have different amount of data in in the form of an Excel sheet.

The BlinkIT Grocery Data dataset contains information about various grocery items sold at different outlets. It includes details about the items, the outlets, and the sales performance. This dataset is used to create a comprehensive Power BI dashboard for analyzing sales, profits, and other key metrics.

 ## File Information
File Name: BlinkIT Grocery Data.xlsx
Sheet Name: BlinkIT Grocery Data


## Highlights
- 📈 The dashboard includes interactive filters and dynamic visuals to explore sales performance, customer satisfaction, inventory distribution, and outlet performance.
- 📊 Key Performance Indicators (KPIs) are calculated for total sales, average sales, number of items, and average ratings.
- 🍩 Donut charts are used to analyze sales by fat content, while bar charts visualize sales by item type.
- 🗺️ The dashboard uses line charts to track outlet establishment performance, matrix cards for Outlet size and location analysis, and a matrix to analyze Outlet type.

## Data Dictionary
### Columns
- Item Fat Content: The fat content of the item (e.g., Low Fat, Regular).
- Item Identifier: A unique identifier for each item.
- Item Type: The category of the item (e.g., Fruits and Vegetables, Frozen Foods).
- Outlet Establishment Year: The year when the outlet was established.
- Outlet Identifier: A unique identifier for each outlet.
- Outlet Location Type: The location type of the outlet (e.g., Tier 1, Tier 2).
- Outlet Size: The size of the outlet (e.g., Small, Medium, High).
- Outlet Type: The type of the outlet (e.g., Supermarket Type1, Supermarket Type2).
- Item Visibility: The visibility of the item in the store.
- Item Weight: The weight of the item.
- Sales: The sales amount of the item.
- Rating: Customer rating for the item.

## Data Processing
- Calculations: The dashboard includes calculated fields such as total profit, which is 
   derived using DAX queries.
- Visualization: Various charts and slicers are used to present the data in an intuitive and 
    interactive manner.

## Steps followed 
 - Step 1 : Load data into PowerBI Desktop , dataset is an XLSX Worksheet (.xlsx).
 - Step 2 : Cleaning the dataset 
 - Step 3 : Build insights for the dataset 
## Dashboard Insights 

The Power BI dashboard created using this dataset provides the following insights:

-  Create a new table in the dataset abd give the name eg: Metrics  and create some columns : 
   Total sales , Avg sales ,No. of items , Avg ratings

- Use card new visual and create a cards for (Total sales , Avg sales , no. of items , Avg 
    ratings ).

- Create a doughnut chart for Fat Content clolumn where in values drop metrics table which 
    you created by Dax query  , and in legend drop Item Fat Content column.

- Create a clustered bar chart  for Fat by outlet where in x - axis : Metrics , y - axis = outlet location type .
- Create a stacked bar chart for itrm type clolumn , where : x-axis - metrics table , y-axis 
   item type
- Create a line chart  for outlet establishment  , where - x-axis :- outlet establishment , y-axis : total-sales
  
- Create a doughnut chart for outlet size : medium, small, high
  in legend - outlet size , values total sales.
  
- Create a funnel chart  for outlet location , where cateogry - outlet location type , values - sum of values
- Create matrix chart for outlet type  where rows: outlet type , columns - values :- total 
  sales , no. of items , abg sales , avg rating , item visibility .
- create a slicer for outlet location type , outlet size, item type  and created it on the 
  blinkit banner .
  
### Measure new data 

- Total Sales find
- Average Sales
- No. of items
- Average Rating 

## Usage
- Open the BlinkIT Grocery Data.xlsx file in Power BI.
- Load the data from the "BlinkIT Grocery Data" sheet.
- Use the fields and calculated measures to create visualizations as described above.
- Interact with the dashboard by using filters and slicers to explore different aspects of 
   the data.


📈 
📊
🍩
🗺️
