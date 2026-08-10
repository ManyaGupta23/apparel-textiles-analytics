# Week 3 — Data Integration & Transformation

## Overview

Week 3 focused on integrating and transforming apparel and fashion datasets collected during the previous stages of the project.

The main objective was to handle differences between datasets, standardize categorical information, and prepare the data for further business analysis.

## Objectives

- Integrate multiple apparel datasets
- Identify differences between datasets
- Standardize categorical values
- Create business-category mappings
- Handle inconsistent or missing information
- Prepare integrated data for dashboard and analysis

## Data Integration

The datasets contained different structures and attributes.

For example, one dataset contained:

- ProductID
- ProductName
- ProductBrand
- Gender
- Price
- PrimaryColor

while another dataset contained:

- Style
- Rating
- Size
- Season
- Material
- FabricType
- PatternType

Since the datasets did not contain a common unique identifier suitable for a direct merge, a direct row-by-row merge could create incorrect relationships.

Therefore, categorical mapping and transformation were used where appropriate.

## Brand Category Mapping

A mapping table was created to convert raw brand values into standardized business categories.

Example:

| ProductBrand | BrandCategory |
|---|---|
| SPYKAR | Fashion |
| Parx | Fashion |
| SHOWOFF | Fashion |
| Kenneth Cole | Luxury |
| Police | Accessories |
| Vishudh | Ethnic Wear |
| Homesake | Home Decor |

This mapping converts raw categorical values into standardized business categories that are easier to analyze.

## Transformation Process

The integration workflow included:

1. Reviewing dataset structures
2. Identifying common and different fields
3. Checking data types
4. Standardizing categorical values
5. Creating mapping categories
6. Handling missing values where required
7. Validating the transformed data
8. Saving the integrated dataset

## Validation

The transformed data was checked for:

- Missing values
- Duplicate records
- Unexpected categories
- Incorrect mappings
- Data-type consistency
- Number of records before and after transformation

## Files

- `mapping/` — Brand/category mapping files
- `integrated_data/` — Integrated and transformed dataset
- `Week 3 Integration data Report.pdf` — Detailed Week 3 report
- `ETL process.ipynb` — Python/Colab notebook, if used

## Tools Used

- Python
- Pandas
- Google Colab / Jupyter Notebook

## Key Outcome

The data integration and transformation process converted different raw data structures into a more consistent format suitable for business analysis and visualization.

## Next Step

The transformed data was used as supporting data for **Week 4 — Power BI Dashboard Development**.
