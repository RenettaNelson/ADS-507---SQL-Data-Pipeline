# Wild and Wonderful Sales: A Way to Hike Up Your Profit

### Our Project
This project uses SQL and Python to create a production-ready data pipeline. Using multiple datasets, an ETL or ELT pipeline was built to process the data and produce a dashboard for visualization.

###Team 3
Ben Earnest
Renetta Nelson
Vannesa Salazar

### Methods Used
* Data preprocessing
* Exploratory Data Analysis
* Data Transformation
* Data Visualization


### Technologies
* Python, mySQL
* Pandas, jupyternotebook
* Github Repository

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- writeup/reporting
- presentation
- voice recordings

### Objective
The objective of our project is to use the following datasets to create a visualization for an outdoor resale chain to consolidate monthly sales trend and layer it to economic indicators.

### Data Sources

GOsales dataset. This data includes information about daily sales for a fictitious outdoor equipment retail chain (Relational Database Repository, n.d) .  It includes five tables that consists of product information, retailer information, order methods, and daily sales.  The data covers January 2015 through August 2016. 

Monthly consumer price index (CPI) change.  This data was collected from the Bureau of Labor and Statistics (BLS) website.  It contains the monthly change to the CPI, covering years 2012-2022.  We intend to use this data to compare sales performance metrics to CPI.

Monthly unemployment rate.  This data was also collected from the BLS website, and includes monthly unemployment as a percentage of the overall workforce for the years 2012-2022.  We intend to use this data to compare to the sales performance metrics.
Gross Domestic Product.  This data was collected from The World Bank Group and contains the GDP values of various countries for the past 61 years. We will only be utilizing the years that are consistent with the GOSales data. The GDP for the applicable countries will be broken into quarters and displayed for 2015 and 2016. We will join this with the GOSales data, which will display each respective countries quarterly profits. By examining these two visuals, we will identify any trends between sales and GDP. 

Consumer Confidence Index: This data is collected from The Organisation for Economic Co-operation and Development (OECD). The CCI will be viewed over the 2015 and 2016 years to correspond with the other economic indicators as well as the go sales data that we are basing the pipeline on. The information included in the CCI will indicate whether consumers are spending or if they are saving and how those indicators correspond with go sales data. By understanding their relevance exciting information can be understood on buying habits of consumers and their overall impact on sales. Any value of 100 or more will indicate strong consumer confidence. 

## Required Python Packages
* import pandas as pd
* from pandas.io import sql
* from sqlalchemy import create_engine
* from sqlalchemy.pool import Pool
* import mysql.connector
* import json
* import csv
* import os

* import numpy as np
* import pymysql as mysql
* import matplotlib.pyplot as plt
* import requests
* import getpass
* import seaborn as sns
* from pptx import Presentation 
* from pptx.util import Inches 


## Getting Started

## Featured Notebooks/Analysis/Deliverables
* [Presentation slides ](https://docs.google.com/presentation/d/1yqAHFY4O4jF9iG8J3dKcHRYTRHIPlyIzV0p5uKePlQY/edit?usp=sharing)

1. Clone this repo using raw data.
2. add code and push new code into repo. To ensure cohesive code make sure to run all cells prior to upload. 
3. Import all required python packages. 

## Extract Data
1. CSV files are then extracted from the repo they are stored in, into pandas dataframes. 
-go_1k
-go_daily_sales
-go_methods...etc.

## Transform Data and cleaning
- New columns need to be added to the different dataframes in order to make comparisons based on Year and Month. 
-mySQL does not like using spaces so all dataframes need to have their spaces replaced with underscores. 
-Columns that are not related or correlated to the problem solution are drop for consistency. 
-A few dataframes are merged to determine correlation. 

## Load transformed tables to destination database
- Using a SQL connector, jupyter notebooks is connected to mySQL and a destination Database is created. Next an engine is created to add data to the SQL database. The code provided in the repo will indicate once the tables are loaded and if they are loaded successfully. 

## Query Data through mySQL connection
- With the help of a cursor the data is then queried using SQL commands within Jupyter notebook. Using SQL a new table is created for all the economic indicators that will be used against the gosales data to determine the impacts of those indicators. 

## Visualizations are sent to Powerpoint slides. 
- A function is used to send all meaningful visualizations to a powerpoint slide. 
- Visuals can there be shared with various stakeholders, external or internal consumers to make determinations on profitability. 
- Monthly metric ppt may be viewed from local folder where user clones the repository. 

