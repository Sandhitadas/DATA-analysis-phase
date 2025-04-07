# DATA-analysis-phase
# Task 1: Data Cleaning and Preprocessing

## Dataset
[Customer Personality Analysis Dataset]([https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis?resource=download))

## Tools Used
- Python (Pandas)

## Cleaning Steps Performed
1. Loaded raw data using the correct delimiter (` sep='\t'`).
2. Removed duplicate rows.
3. Handled missing values in `Income` using median imputation.
4. Standardized text columns (`Education`, `Marital_Status`) — trimmed and converted to lowercase.
5. Converted `Dt_Customer` to `datetime` and formatted as `dd-mm-yyyy`.
6. Renamed all columns to lowercase with underscores for consistency.
7. Ensured correct data types: integers, floats, and datetime.
8. Saved the cleaned dataset as `cleaned_customer_personality.csv`.

## Result
- ✅ 100% data cleaned and ready for analysis.
- 🔍 No missing values.
- 📁 Cleaned file saved for further use.
