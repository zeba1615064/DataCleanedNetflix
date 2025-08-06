# DataCleanedNetflix# 
Netflix Dataset Cleaning (Excel)

## 📌 Task Objective
This task involved cleaning and preprocessing the Netflix Movies & TV Shows dataset to prepare it for analysis.  
Key cleaning steps included:
- Handling missing values
- Removing duplicates
- Standardizing text formatting
- Fixing date formats
- Renaming columns for uniformity
- Ensuring correct data types

## 🛠 Tools Used
- Microsoft Excel

## 📂 Files in this Repository
- *netflix_titles(main).xlsx* → Final cleaned dataset in Excel format
- *netflix_cleaning_summary.xlsx* → One-page Excel summary of cleaning steps

## 🔍 Summary of Cleaning
1. *Missing Values*
   - Filled missing Director, Cast, and Country fields with "Unknown".
   - Filled missing date_added values with placeholder 01-Jan-1900.
2. *Duplicates*
   - Checked and removed duplicate rows.
3. *Standardized Text*
   - Trimmed spaces from text fields.
   - Converted country names to Title case (e.g., "usa" → "Usa").
   - Converted rating values to uppercase.
4. *Date Formats*
   - Converted date_added to dd-mm-yyyy format.
5. *Column Names*
   - Renamed to lowercase with underscores (e.g., "Date Added" → "date_added").
6. *Data Types*
   - Ensured release_year is stored as an integer.

## 📊 Final Dataset Shape
- *Rows:* 322
- *Columns:* 12

---

*Dataset Source:* [Netflix Movies and TV Shows - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
