# S&P 500 Historical Data Cleaning Project

This repository contains the data-cleaning portion of an S&P 500 historical research project.

## Files

- `sp500.csv` – original historical S&P 500 dataset
- `sp500_project.ipynb` – Jupyter notebook containing the data-cleaning process
- `sp500_cleaned.csv` – cleaned and tidy dataset produced by the notebook

## Data-cleaning steps

The notebook:

1. Reads the original dataset
2. Inspects the data types and missing values
3. Standardizes column names using lowercase snake_case
4. Converts the date column to datetime
5. Converts numerical columns to numeric data types
6. Checks for invalid dates and duplicate observations
7. Converts unavailable PE10 values recorded as zero to missing values
8. Sorts the observations chronologically
9. Confirms that each row represents one month and each column represents one variable
10. Exports the cleaned dataset

No datasets were joined because all required variables were already contained in one dataset.
