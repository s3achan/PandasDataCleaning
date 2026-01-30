### Employee Dataset Cleaning Pipeline

**Purpose:** Transform a messy, real-world-style employee dataset into clean, consistent, analysis-ready data.

## Overview

This repository contains a Jupyter notebook that performs thorough data cleaning on an example employee dataset full of common real-world quality problems:

- Inconsistent name formatting & casing (John Doe vs john doe vs JOHN DOE)
- Invalid / extreme / text-based ages
- Negative, missing, text, or malformed salaries ("not available", "55k", etc.)
- Multiple date formats and invalid dates (e.g. 2021-02-30)
- Inconsistent department names (sales / Sales / SALES / "sales ")
- Missing values in different representations (NaN, empty string, "not available")
- Duplicate records after standardization
- Unrealistic values (age 135, age 17 with high salary, etc.)

Files

| File                                      | Description                                      |
|-------------------------------------------|--------------------------------------------------|
| `employee_data_with_quality_issues.xlsx`  | Original dirty dataset (source of truth / example) |
| `Employee_Data_Cleaning.ipynb`            | Main Jupyter notebook with cleaning steps        |
| `employee_dataset_100_reocrds.xlsx`       | Updated Records to include 100 datasets          |

