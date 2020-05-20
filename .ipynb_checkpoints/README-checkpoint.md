# Pandas Coding

## Overview
Read and analyzed a .csv file via Pandas coding in Jupyter Lab, observing data for fantasy games, of an independent gaming company. Generated a report summarizing the purchasing data by gender, age, players and items.

## Purchasing Analysis
Calculated and structured a DataFrame providing a basic overview of purchases including: 1) Number of Unique Items, 2) Average Purchase Price, 3) Total Number of Purchases, 4) Total Revenue.

![](Images/purchasing_analysis.png)
![](Images/purchasing_df.png)

## Gender Demographics
Data grouped by Gender to provide: 1) Percentage and Count of Male Players, 2) Percentage and Count of Female Players, 3) Percentage and Count of Other / Non-Disclosed

![](Images/gender_demographics.png)
![](Images/gender_df.png)

## Purchasing Analysis by Gender
Gender data further analyzed to summarize consumer average and total purchases.  Pandas .groupby function utilized to calculate purchases per gender that was structured into a DataFrame.  Data formatting used to clearly display totals by dollar or count.

![](Images/gender_analysis.png)
![](Images/gender_purchase_df.png)

## Age Demographics
Established bins of 4 years to categorize players by age group (i.e. <10, 10-14, 15-19, etc.).  Pandas .groupby function once again applied to calculate purchases per age group.  DataFrame structured and formatted to display totals by dollar or count.

![](Images/age_demographics.png)
![](Images/age_df.png)

## Top Spenders
Individually analyzed purchasing of players to identify the Top 5 spenders by total purchase value.

![](Images/player_purchase_analysis.png)
![](Images/player_purchase_df.png)

## Most Popular Items
Groupby, sorting and data formatting continually used to identify the 10 most popular items by purchase count.  Table summarized by Item ID, Item Name, Purchase Count, Item Price and Total Purchase Value.

![](Images/item_purchase_analysis.png)
![](Images/item_purchase_df.png)

## Most Profitable Items
The top 5 most profitable items identified by total purchase value, then listed in a table.

![](Images/profitable_items.png)
![](Images/profitable_items_df.png)
