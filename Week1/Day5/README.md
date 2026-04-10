## Day 4 – PySpark DataFrame Operations, File Handling & Joins
### Overview

On Day 4, I worked on PySpark DataFrame operations and file handling, including:

Reading and writing data

Data transformations

Column operations

Aggregations

Joins

This helped me understand how real-world data pipelines are built using PySpark.

### What I Did

Created DataFrames from sample data

Read data from files (CSV format)

Wrote DataFrames back to storage

Selected columns using:

select()

col() with alias

Performed column operations:

Renamed columns

Dropped unwanted columns

Applied filter conditions:

Salary-based filtering

Department-based filtering

Used withColumn() to:

Add tax column

Calculate net_salary

Add constant column (company)

Applied conditional logic:

when() (CASE WHEN equivalent)

Used string transformation:

upper()

### What I Learned

How to read and write files in PySpark

Renaming columns using:

withColumnRenamed()

Dropping columns using:

drop()

Difference between:

select() vs withColumn()

Applying transformations and calculations on columns

Using when() for conditional logic

Performing aggregations:

count(), sum(), avg(), max(), min()

### Challenges Faced
Understanding file read/write syntax

Confusion in column operations (rename vs alias)

Writing multiple transformations in a single pipeline

Applying filters with multiple conditions

### How I Solved It

Practiced file operations step-by-step

Tested column operations individually

Compared different approaches (alias vs rename)

Re-ran transformations to verify results

Broke complex logic into smaller steps

### Joins Practice

Created:

Employee DataFrame

Department DataFrame

Performed:

Inner Join

Left Join

Right Join

Full Join

Left Anti Join

Identified unmatched records using NULL conditions

### Outcome

Gained strong understanding of:

File handling in PySpark

Column transformations

Joins and aggregations

Built confidence in handling real-world data processing tasks
