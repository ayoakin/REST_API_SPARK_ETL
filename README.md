# ETL Pipeline with Apache Spark using a REST API 

## Project Overview
Extract, transform, and load (ETL) pipelines process data from multiple sources into central repositories to serve various business purposes.This project uses a toy pipeline to model an ETL in the wild that ingests data from a REST API using PySpark. 

This project creates an ETL (extract, transform, load) pipeline that:
* Imports data from a public API (using PySpark, the Python API for Spark)
* Creates a dataframe
* Creates a temporary view or HIVE table for SQL queries
* Cleans and transform the data based on business requirements
* Converts and stores data in requested file formats such as (CSV,ORC, JSON, Parquet)
* Creates visualization using Matplotlib on process data.

For a detailed explanation on the ETL processes used, check out the accompanying [article on medium](https://medium.com/@ayoakinkugbe/a-step-by-step-guide-to-building-an-etl-pipeline-with-apache-spark-using-csv-parquet-and-json-3344050d265d)

### Code
You can find the code for this project [here](https://github.com/ayoakin/REST_API_SPARK_ETL/blob/main/ETL_Pipeline_with_Apache_Spark_using_a_Rest_API.ipynb).

File overview:

* `ETL_Pipeline_with_Apache_Spark_using_a_Rest_API.ipynb` - the full code from this project


## Environment Setup

### Installation
To follow this project, please install the following locally:

* Python 3.8+
* Spark-3.2.1
* os
* sys
* Python packages
  * pyspark
  * pyspark.sql.functions
  * Matplotlib

### Data

You can access the USA Spending API used for the project here:

* [Toptier Agencies](https://api.usaspending.gov/api/v2/references/toptier_agencies/) - REST API data source

