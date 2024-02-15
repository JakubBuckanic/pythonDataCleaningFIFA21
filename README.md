# FIFA21 Data Cleaning Project

This repository is dedicated to a Python-based project that meticulously cleans the FIFA21 dataset, transforming it from a raw, unprocessed state into a refined, analysis-ready format. The dataset is sourced from Kaggle.

The project leverages the robust capabilities of the pandas library to execute a series of data cleaning tasks:

1. **Renaming Columns**: Enhances readability and accessibility by renaming column headers.
2. **Identifying Duplicates**: Utilizes pandas' `duplicated()` function to detect and handle duplicate entries.
3. **Finding Unique Values**: Employs pandas' `unique()` function to identify unique values within columns.
4. **Data Type Conversion**: Transforms column data types to formats suitable for subsequent analysis.
5. **Value Replacement**: Replaces specific values, notably converting 'K' and 'M' abbreviations to their full numeric representations.
6. **Dropping Columns**: Removes irrelevant or unnecessary columns from the DataFrame.
7. **String Stripping**: Utilizes pandas' `str.strip()` function to remove leading and trailing spaces from string values.
8. **Value Filtering**: Filters rows based on specific conditions using boolean indexing.
9. **Creating New Columns**: Generates new columns derived from existing data.
10. **Unit Conversion**: Converts heights from feet to centimeters and weights from pounds to kilograms, while also removing unit labels.
11. **Index Alteration**: Modifies the DataFrame index for improved data organization.
12. **Column Reordering**: Rearranges the order of columns within the DataFrame as per requirements.
13. **Saving to CSV**: Stores the cleaned DataFrame into a CSV file for future use and analysis.

This project exemplifies the practical application of data cleaning techniques in Python using pandas. It serves as a comprehensive guide for data preprocessing, demonstrating the transformation of raw, messy data into a clean, structured format conducive to data analysis.
