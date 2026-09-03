# Cleaned Data

This folder contains the cleaned version of the sales dataset (`cleaned_sales_data.csv`), ready for analysis.

## What was fixed:
- Removed duplicate records
- Standardized city names to a single consistent spelling
- Standardized payment mode categories
- Converted all dates to a single format (YYYY-MM-DD)
- Removed currency symbols and confirmed numeric columns
- Corrected TotalAmount mismatches
- Removed invalid negative Quantity entries
- Handled missing values appropriately (blanks left as blank, missing cities grouped as "Unknown")

This cleaned dataset is the one connected to the [Looker Studio dashboard](https://datastudio.google.com/reporting/374920a9-1a37-4f91-bad9-1b33d10a72a3).

See the main [README](../README.md) for full project details.
