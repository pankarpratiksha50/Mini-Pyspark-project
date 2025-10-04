# Mini-Pyspark-project
📌 Project Description

This project demonstrates Data Analysis using PySpark on an orders dataset. It covers data ingestion, transformation, SQL queries, and storage using PySpark functionalities. The project includes:

Creating a SparkSession as the entry point.

Reading CSV data into a DataFrame with schema inference.

Exploring data using .show() and .printSchema().

Applying User Defined Functions (UDFs) for custom transformations.

Using withColumn() to create new columns.

Registering DataFrames as temporary SQL views with createOrReplaceTempView() and running SQL queries.

Formatting date columns with date_format().

Implementing Window Functions (row_number, rank, sum over) for ranking and aggregation.

Writing processed data into Parquet and CSV formats.

Demonstrating partitioning and saving results efficiently.
