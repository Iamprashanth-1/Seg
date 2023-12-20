# SegWise Assignment

## Overview
This repository contains code for a SegWise assignment, implemented using Pyspark and Python.

## Requirements
- Python
- Pyspark
- JAVA (for local environment)
- Your preferred Python environment (for local environment)

## Steps to Run the Code

### Google Colab
If you are using Google Colab, you can simply upload the notebook and run it, as Java is already set up in that environment.

### Local Environment
If you want to run the code in a local environment, follow these steps:

1. Install JAVA, Pyspark, and Python.
   - For JAVA: [Download and Install JAVA](https://www.oracle.com/java/technologies/javase-downloads.html)
   - For Pyspark: `pip install pyspark`
   - For Python: Make sure you have your preferred Python environment set up.

2. Execute the code in your preferred Python environment.

## Code Flow

### Step 1:
- Load the CSV or parquet file. Make sure the file path is correctly specified in the code.

### Step 2:
- Generate binned values for all numeric columns. You can customize binning parameters based on your data distribution.

### Step 3:
- Generate all possible combinations for numeric columns. Adjust the code to include/exclude specific columns as needed.

### Step 4:
- For each subset, find all possible combinations and store them in-memory. Optimize memory usage for large datasets.

### Step 5:
- Concatenate the columns as required. Ensure proper handling of data types and missing values.

### Step 6:
- Write the result to a CSV file. Specify the output file path in the code.
