# Azure Data Factory Typed Sales Pipeline
ADF Pipeline that loads .csv into Azure SQL tables using appropriate data types.

## Project Overview

This project demonstrates an Azure data factory pipeline that moves CSV customer data from Azure Blob Storage into Azure SQL database using appropriate SQL data types.

## Pipeline Architecture

P02_Customers.csv, -> Azure Blob Storage, -> Azure Data Factory, -> Azure SQL Database.

## Technologies used

* Azure Data Factory
* Azure Blob Storage
* Azure SQL Database 
* GitHub

## Screenshots

## 1. Azure resources

![Azure resources](P02%20Azure%20Data%20Pipelines%20Screen%20Prints/01-P02-Azure-Resources.png)

![ADF pipeline source](P02%20Azure%20Data%20Pipelines%20Screen%20Prints/02-P02-ADF-Pipeline-Source.png)

![ADF data source](P02%20Azure%20Data%20Pipelines%20Screen%20Prints/03-P02-Azure-SQL-Customer-Data.png)

## What I learned

* How to connect Blob Storage to ADF and use a copy activity.
* Schema and mapping basics for CSV to SQL.
* Importance of exact file naming in documentation.
* Mapping to proper SQL data types.
* Using a primary key to prevent duplicates.
* Troubleshooting primary key errors, and using truncate to clear test data.
* Validate, debug, and publish.

## Project files

* [P02_Customer.csv](P02_Customers.csv)