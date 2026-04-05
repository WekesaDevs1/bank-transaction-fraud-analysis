# Bank Fraud & Data Quality Analysis

## Overview

This project analyzes messy banking transaction data to improve data quality and detect fraud risk patterns. It simulates real-world issues found in financial datasets.

## Problem

Banking data often contains missing values, inconsistent formats, and invalid entries. These issues reduce the accuracy of fraud detection and decision-making.

## Objective

Clean the dataset and uncover patterns that indicate fraudulent activity.

## Dataset

Synthetic transaction dataset with:

* Missing values
* Incorrect data types
* Duplicate records
* Inconsistent categories
* Invalid entries

## Process

### 1. Data Inspection

* Checked structure using `.info()` and `.describe()`
* Identified missing values and inconsistencies

### 2. Data Cleaning

* Converted columns to correct data types
* Handled missing values using median and category replacement
* Removed duplicates
* Standardized text fields
* Removed invalid and extreme values

### 3. Feature Engineering

* Extracted date features (day, month)
* Created high-value transaction flag

### 4. Statistical Analysis

* Mean and variance of transaction amounts
* Confidence interval estimation

### 5. Fraud Analysis

* Compared fraud vs non-fraud transactions
* Analyzed fraud rate by transaction type
* Evaluated risk in high-value transactions

### 6. Visualization

* Distribution of transaction amounts
* Fraud vs transaction amount comparison
* Transaction type frequency
* Fraud rate by branch

### 7. Rule-Based Detection

* Built a simple fraud rule based on high-value transfers
* Compared rule predictions with actual fraud labels

## Key Insights

* High-value transactions show higher fraud risk
* Certain transaction types are more prone to fraud
* Poor data quality can hide fraud patterns
* Data cleaning improves reliability of analysis

## Tools

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* SciPy

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Open the notebook:
   fraud_analysis.ipynb

3. Run all cells

## Project Structure

* data/ → dataset
* fraud_analysis.ipynb → main analysis
* requirements.txt → dependencies

## Author

Your Name
