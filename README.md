# Data Cleaning in SQL

This repository contains SQL queries for cleaning and preprocessing data from the 'NashvilleHousing' table in the 'PortfolioProject' database. The SQL queries demonstrate various data cleaning tasks, such as standardizing date formats, populating missing property addresses, breaking out address components, changing values, and removing duplicates.

## Queries and Tasks

1. **Standardize Date Format:**
   - Converts the 'SaleDate' column to a standardized date format.

2. **Populate Property Address Data:**
   - Populates missing property addresses based on matching Parcel IDs.

3. **Breaking Out Address into Individual Columns:**
   - Splits the 'PropertyAddress' column into separate 'Address' and 'City' columns.

4. **Breaking Out Owner Address:**
   - Splits the 'OwnerAddress' column into 'Address,' 'City,' and 'State' columns.

5. **Change 'Y' and 'N' to 'Yes' and 'No':**
   - Converts 'Y' and 'N' values in the 'SoldAsVacant' field to 'Yes' and 'No,' respectively.

6. **Remove Duplicates:**
   - Identifies and removes duplicate rows from the dataset based on specific columns.

7. **Delete Unused Columns:**
   - Drops unused columns, including 'OwnerAddress,' 'TaxDistrict,' 'PropertyAddress,' and 'SaleDate.'

## How to Use

1. Ensure you have access to the 'PortfolioProject' database with the 'NashvilleHousing' table.
2. Copy and paste the SQL queries into your SQL management tool (e.g., SQL Server Management Studio) and execute them.
3. Each query is labeled with its respective task for data cleaning and preprocessing.

**Note:** Be cautious when executing data cleaning queries, as they may modify or delete data in the database.

## Author

Saketh Yalamanchili

Feel free to adapt and modify these SQL queries to suit your specific data cleaning needs. If you have any questions or suggestions, please don't hesitate to reach out.
