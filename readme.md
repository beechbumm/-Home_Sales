# Spark SQL and Data Processing Project

## Overview

In this project, I learned how to process and analyze large datasets using Apache Spark. I focused on managing, optimizing, and querying data in Parquet format. The dataset I used is about home sales. I ran SQL queries to find insights like average home prices based on different criteria. I also explored the benefits of caching data in Spark and compared runtimes for cached and uncached queries.

## Project Steps

- **Setup:**
  - I installed Spark and Java.
  - I set up the Spark environment.
  - I loaded the dataset from a CSV file into a DataFrame.

- **Data Processing:**
  - I partitioned the data by the `date_built` field.
  - I saved the partitioned data in Parquet format.
  - I created temporary views from both the original and Parquet DataFrames.

- **SQL Queries:**
  - I ran SQL queries to calculate average home prices.
  - I used different criteria like the number of bedrooms, bathrooms, and views.
  - I compared the performance of queries on cached and uncached data.
  - I ran the queries on the Parquet data and compared the runtimes.

- **Caching:**
  - I cached the temporary tables in Spark.
  - I uncached the tables when needed.
  - I checked if the tables were still cached.

## What I Learned

I learned how to use Spark SQL and Parquet files to handle large datasets. I found out how to make queries faster by partitioning data and using caching. I also learned how to optimize queries and compare their performance. This project helped me understand how to process big data efficiently in a distributed environment.

## How to Use

To run this project:

1. **Install Software:**
   - Install Apache Spark.
   - Install Java (OpenJDK 11).
   - Install Python and the required libraries (`findspark`, `pyspark`).

2. **Set Up:**
   - Set the environment variables for Spark and Java.
   - Load the dataset and run the code.

3. **Run Queries:**
   - Execute the SQL queries to analyze the data.
   - Compare runtimes for cached and uncached queries.

4. **Optimize:**
   - Try different data partitioning and caching strategies.
   - See how these changes affect performance.

## Conclusion

This project was a great way for me to learn how to work with big data using Apache Spark. I now understand how to manage and query large datasets, make queries faster, and use Parquet files for better performance.
