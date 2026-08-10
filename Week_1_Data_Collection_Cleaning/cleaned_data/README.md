# Week 1 — Cleaned Data

## Overview

This folder contains the cleaned and prepared datasets generated during Week 1 of the Apparel & Textiles Data Analytics project.

The raw datasets were inspected and processed using Python and Pandas before being used for further analysis.

## Cleaning Activities

The following data-cleaning activities were performed:

1. **Data Loading**
   - Loaded the publicly available datasets using Pandas.

2. **Data Structure Inspection**
   - Checked the number of rows and columns.
   - Examined column names and data types.

3. **Missing Value Analysis**
   - Identified missing values using `isnull().sum()`.
   - Reviewed missing values before further processing.

4. **Duplicate Checking**
   - Checked for duplicate records using `duplicated()`.

5. **Data Type Checking**
   - Reviewed numeric and categorical columns.
   - Ensured fields such as price were suitable for analysis.

6. **Data Standardization**
   - Reviewed column names and categorical values.
   - Prepared the datasets for exploratory data analysis and integration.

## Main Fields

The cleaned apparel product data includes fields such as:

- ProductID
- ProductName
- ProductBrand
- Gender
- Price (INR)
- NumImages
- Description
- PrimaryColor

Additional fashion attributes were also reviewed where available, including:

- Style
- Price
- Rating
- Size
- Season
- Material
- FabricType
- PatternType
- Recommendation

## Validation

After cleaning, the dataset was checked for:

- Missing values
- Duplicate records
- Incorrect data types
- Inconsistent categorical values
- Unexpected or invalid values

## Output

The cleaned dataset created in this stage is used as the input for the next stages of the project, including:

- Exploratory Data Analysis
- Data Integration
- Data Transformation
- Power BI Dashboard Development

## Tools Used

- Python
- Pandas
- Jupyter Notebook / Google Colab
