PySpark Practice – Customer Orders Analysis
## Overview

In this task, I worked on a simple Customer and Orders dataset using PySpark.

I created DataFrames from raw Python data and performed operations like joining datasets, filtering, and aggregation.

The goal of this task was to understand how real-world data is processed and analyzed using PySpark, which is widely used in data engineering.

## What I Did

Created a Spark Session

Built two DataFrames:

Customers dataset

Orders dataset

Performed join operation using customer_id

Applied:

Filtering (based on city)

Aggregations (total spending)

Basic analysis on order data

## What I Learned
How to create DataFrames from Python lists

How joins work in PySpark (similar to SQL joins)

Writing transformations using:

filter()

groupBy()

agg()

Understanding how data flows in a distributed processing system (Spark)

Difference between raw data and structured DataFrames

## Challenges Faced

Initially confused about how to join two DataFrames correctly

Understanding PySpark syntax compared to SQL

Handling column references after join (same column names issue)

Debugging errors due to small syntax mistakes

## How I Learned / Solved Them

Practiced small examples step by step instead of jumping into complex logic

Compared PySpark operations with SQL queries to understand better

Re-ran code multiple times and analyzed errors carefully

Broke the problem into smaller parts (create → join → analyze)

Practiced similar questions to gain confidence

## Outcome

This task helped me build a strong foundation in PySpark basics, especially:

DataFrame operations

Joins and aggregations

Thinking in terms of data pipelines
