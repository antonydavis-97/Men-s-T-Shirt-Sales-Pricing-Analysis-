# Men's T-Shirt Sales & Pricing Analysis

## Project Overview

This project demonstrates an end-to-end Business Intelligence workflow using **Azure SQL Database and Power BI** to analyse men's T-shirt pricing, discounts, brands, product variety and profitability.

The project covers the complete process from raw CSV data ingestion and SQL data cleaning through to Power BI transformation, DAX calculations, dashboard development and reporting.

## Technology Stack

* Azure SQL Database
* SQL / SQL Server Management Studio (SSMS)
* Power Query
* DAX
* Microsoft Power BI
* Microsoft Excel

## Data Preparation

The raw CSV dataset was imported into Azure SQL Database and connected through SQL Server Management Studio.

SQL was used to clean and standardise pricing data, including:

* Removing unwanted characters from price fields
* Converting price values into appropriate formats
* Trimming unnecessary spaces
* Updating incorrect or incomplete pricing values

Additional data transformation was performed in Power Query within Power BI, including handling missing pricing values and deriving missing original prices.

## Power BI Analysis

The Power BI report includes analysis of:

* Available brands
* Top 5 brands by discount
* Top brands by product variety
* Average sale price by brand
* Average profit percentage by brand
* Bottom 5 brands by average profit percentage

DAX calculations were created for:

* Discount %
* Profit %
* Cost Price
* Marked Price

## Dashboard

The report contains multiple pages with interactive Power BI visualisations, including bar charts, donut charts, ribbon charts, area charts, pie charts and cards.

## Project Workflow

**CSV → Azure SQL Database → SQL Data Cleaning → Power Query → DAX → Power BI Dashboard → Power BI App**

## Dashboard Demonstration

A video walkthrough of the completed Power BI dashboard is included below.

`powerbi-dashboard-demo.mp4`

## Key Learning Outcomes

* Working with cloud-based Azure SQL databases
* Connecting Power BI to Azure SQL
* SQL-based data cleaning
* Power Query transformations
* Developing DAX calculations
* Designing interactive Power BI dashboards
* Applying Top N analysis and business-focused visualisations
* Publishing and deploying Power BI reports
