# Housing Prices Project

Exploratory Data Analysis Project in Python | **Sep 2022**

_This project compares house prices in Victoria from 2010 to 2021._

## Background Information

Information was gathered from two datasets obtained from Data Vic. The [first](https://discover.data.vic.gov.au/dataset/victorian-property-sales-report-median-house-by-suburb-time-series/resource/dd0b13ae-83f8-4cc8-be32-375a3a0c6b74) dataset consisted of the median prices of Victorian suburbs between the years of 2010 and 2020. The [second](https://discover.data.vic.gov.au/dataset/victorian-property-sales-report-median-house-by-suburb/resource/b8b005dc-39bd-4d5b-8c6f-0d1e13abb8cf) dataset had records of median prices for the quarters of 2021 as well as additional information on the number of sales in each quarter.

Both datasets underwent **data cleaning** and **transformation** in preparation for analysis in Python using Matplotlib. 


### Skills Used

* Data Cleaning/Transformation: dealing with NaN values, converting data types, updating empty records, adding columns from different DataFrames
* Data Analysis/Visualisation: Matplotlib (Bar charts, line charts, combination charts), input function


### Languages/Tools Used
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="70" height="70" />

## Findings

In 2020, the most expensive suburb was Toorak taking the top spot amounting to a median price of $5.2 million. Upon observing the top 10 suburbs, almost all suburbs are located in Melbourne's inner east, the only exclusion being the seaside town, Portsea, located about 60km away from the CBD. The 10 most affordable suburbs are located in regions of rural Victoria, with distance exceeding 250km away from Melbourne. 

Between the years 2010 and 2020, Portland North had the largest increase in median price (341%), which increased from $115,000 in 2010 to $507,000. On the other hand, Rupanyup experienced median price deficit by 30% bringing its median price in 2020 to $90,000.

Based on estimates of median prices in 2021, Toorak remains as the most expensive suburb, costing $5.8m. Additionally, the suburb had sold 205 houses in the year, a considerably larger amount than the second most expensive suburb, Deepdene, only recording 32 sales for the year.

In 2021, Traralgon had the most sales, recording 934 houses sold. It is followed by Truganina and Frankston which has 910 and 909 sales respectively.