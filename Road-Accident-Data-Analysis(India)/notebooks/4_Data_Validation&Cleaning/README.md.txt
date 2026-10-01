# Stage 4 – Data Validation and Cleaning

## Purpose

Validate the extracted road accident data and clean the dataset by identifying missing values, duplicate records and inconsistent data before aggregation and analysis.

## Required checks

- Check for missing values in all columns.
- Calculate missing-value counts and percentages.
- Check for duplicate records.
- Check for duplicate accident records where applicable.
- Check the data types of important columns.
- Check for invalid or inconsistent values.
- Check numerical accident-related fields for valid values.
- Check categorical fields for unexpected categories.
- Check text fields for blank or unnecessary whitespace.
- Standardize values where required.
- Convert columns to appropriate data types where required.
- Preserve missing information instead of automatically treating missing values as zero.
- Perform final validation after cleaning.

**Important:** The cleaning process is based on the actual values and validation results obtained from the dataset. The original raw dataset is preserved separately from the cleaned data.

## Output

The stage produces a validated and cleaned road accident dataset that can be used for aggregation, analysis and visualization in the following project stages.