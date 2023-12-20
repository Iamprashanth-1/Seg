# SegWise Assignment

## Overview
This repository contains code for a SegWise assignment, implemented using Pyspark and Python.

## Steps to Run the Code

### Google Colab
If you are using Google Colab, you can simply upload the notebook and run it, as Java is already set up in that environment.

### Local Environment
If you want to run the code in a local environment, follow these steps:

1. Install JAVA, Pyspark, and Python.
2. Execute the code in your preferred Python environment.

## Code Flow

### Step 1:
- Load the CSV or parquet file.

### Step 2:
- Generate binned values for all numeric columns.

### Step 3:
- Generate all possible combinations for numeric columns.

### Step 4:
- For each subset, find all possible combinations and store them in-memory.

### Step 5:
- Concatenate the columns as required.

### Step 6:
- Write the result to a CSV file.

