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

Consumer Confidence Index: This data is collected from The Organisation for Economic Co-operation and Development (OECD). The CCI will be viewed over the 2015 and 2016 years to correspond with the other economic indicators as well as the go sales data that we are basing the pipeline on. The information included in the CCI will indicate whether consumers are spending or if they are saving and how those indicators correspond with go sales data. By understanding their relevance exciting information can be understood on buying habits of consumers and their overall impact on sales. 

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
* [Presentation slides ]()

1. Clone this repo using raw data.
2. add code and push new code into repo. To ensure cohesive code make sure to run all cells prior to upload. 
3. Use ###### flags for output

## Extract Data

## Transform Data

## Deploy Data to mySQL

## Query Data through mySQL connection

## Trigger Visualizations to a Powerpoint




