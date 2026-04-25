# Support-Tickets-ETL-Pipeline
An end-to-end ETL pipeline in AWS involving structured (MySQL) and unstructured data (.log files). Data extracted from two sources into S3, transformed it using Lambda and Glue Studio to store processed data in parquet files which are later loaded into Redshift. Also used Amazon Athena for ad-hoc analysis on the processed data stored in S3.
