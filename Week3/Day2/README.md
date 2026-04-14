# Week 2- Day 2 - Pyspark & Delta Lake

## Overview

This project demonstrates hands-on implementation of Data Engineering concepts using PySpark and Delta Lake, focusing on ETL pipelines, data processing, and lakehouse architecture.

## Null Handling & Data Cleaning

### What I Practiced
Handled missing and null values in datasets
Cleaned inconsistent and incomplete records
Applied filtering and replacement strategies
Prepared data for transformation stages

### Functions Used
isNull(), isNotNull()
ifNull(), Nullif(), nvl()
fillna()
dropna()
coalesce()
when().otherwise()

### Key Learnings
Understood importance of data quality in pipelines
Learned multiple strategies to handle missing values
Improved preprocessing skills for real datasets

## User Defined Functions (UDF)

### What I Practiced
Created custom functions for transformation logic
Applied UDFs on DataFrame columns
Implemented business-specific rules

### Functions Used
udf()

### Key Learnings
Learned how to implement custom logic in PySpark
Understood when UDFs are required
Gained flexibility in complex transformations

## Databricks Widgets (Parameterization)

### What I Practiced
Used widgets for dynamic parameter input
Passed runtime values to notebooks
Eliminated hardcoded paths and values

### Functions Used
dbutils.widgets.text()
dbutils.widgets.dropdown()
dbutils.widgets.combobox()
dbutils.widgets.multiselect()
dbutils.widgets.get()

### Key Learnings
Learned how to make pipelines dynamic
Understood reusable notebook design
Improved workflow flexibility

## Full Load vs Incremental Load

### What I Practiced
Implemented full data overwrite strategy
Built incremental loading pipelines
Processed only new/changed records

### Functions Used
write.mode("overwrite")
write.mode("append")
join(..., "left_anti")

### Key Learnings
Understood full vs incremental load concepts
Learned efficiency benefits of incremental processing
Improved pipeline optimization skills

## Delta Lake Operations & Advanced Features

### What I Practiced
Worked with Delta tables for storage
Performed Create, Insert, Update, Delete operations
Implemented MERGE INTO for upsert logic
Used Time Travel and Restore features
Tracked table history

### Functions / Commands Used
format("delta")
save()
mode("append")
MERGE INTO
UPDATE, DELETE
DESCRIBE HISTORY
RESTORE TABLE

### Key Learnings
Understood ACID compliance in data lakes
Learned versioning and rollback concepts
Gained strong understanding of Delta Lake architecture
Improved real-world data reliability concepts

## End-to-End ETL Pipeline

### What I Practiced
Built full ETL pipeline from ingestion to output
Performed multiple transformation steps
Handled duplicates and data inconsistencies
Produced clean final datasets

### Key Learnings
Understood complete data pipeline lifecycle
Learned integration of multiple transformation steps
Gained real-world ETL experience

### Final Conclusion

This practice covered a full real-world Data Engineering workflow including ingestion, cleaning, transformation, incremental processing, and Delta Lake-based storage systems.
