# Sales-Data-Insights

A Python project using Pandas and NumPy to analyze sales data from an Excel dataset. This script cleans missing values, computes key metrics, and provides statistical insights into sales performance.

## Features

- **Data Loading**: Reads an Excel file and loads it into a Pandas DataFrame.
- **Data Cleaning**:
  - Handles missing `CustomerName` entries by filling with "Unknown".
  - Imputes missing values for `TotalSales`, `UnitPrice`, and `Quantity` using calculations or median/mean values.
- **Analysis**:
  - Total sales by region.
  - Average sales per product.
  - Identification of highest/lowest revenue-generating products.
- **Statistical Metrics**: Uses NumPy to compute mean, median, and standard deviation for numerical fields.

