Housing Data Cleaning and Preparation in SQL
This project focuses on cleaning and preparing a raw housing dataset using SQL Server. The goal was to standardize dates, populate missing fields, split address components, remove duplicates, and prepare the dataset for visualization in Tableau.

Tableau Dashboard
https://public.tableau.com/shared/ZHC5SX8TK

Dataset
Housing dataset containing parcel information, property and owner addresses, sale dates, sale prices, and other fields. The raw data required extensive cleaning before analysis.
 
Project Overview
- Standardized date formats using SQL date conversion.
- Populated missing property addresses using self‑joins.
- Split property and owner addresses into separate columns.
- Normalized categorical values (e.g., Y/N to Yes/No).
- Identified and removed duplicate records.
- Dropped unused or redundant columns.

Techniques Used
- SQL joins and self‑joins
- SUBSTRING, CHARINDEX, and PARSENAME for address parsing
- CASE statements for data normalization
- CTE with ROW_NUMBER for duplicate detection
- ALTER TABLE for schema cleanup

Key Insights
- Many missing property addresses could be recovered using ParcelID.
- Address fields were inconsistent and required splitting for analysis.
- Duplicate entries were present and needed removal.
- After cleaning, the dataset was suitable for Tableau visualization.

Tech Stack
- SQL Server
- Tableau
- GitHub

Files Included
- SQL cleaning script
- Tableau workbook
- Excel data
- README documentation
