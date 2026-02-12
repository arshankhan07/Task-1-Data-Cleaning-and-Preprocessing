# Task-1-Data-Cleaning-and-Preprocessing
Objective: Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats).

README – Data Cleaning & Preprocessing
Dataset:
Mall Customer Segmentation Data (Kaggle)

Objective:
Prepare the raw dataset for analysis by identifying and correcting issues such as missing values, duplicates, inconsistent formats, and incorrect data types.

Steps Performed
1. Data Inspection:

-Loaded the CSV file into Pandas.
-Reviewed structure, column names, and data types using head() and info().

2. Missing Values:

-Checked using isnull().sum().
-No missing values were found.

3. Duplicate Records:

-Checked using duplicated().sum().
-No duplicate rows were present.

4. Text Standardization:

-Cleaned the Gender column
-removed extra spaces
-converted values to lowercase for consistency.

5. Column Renaming:

-Converted headers to a uniform format:
-lowercase
-spaces replaced with underscores
-special characters removed.

6. Data Type Correction:

-Ensured appropriate types
-customerid, age, annual_income_k$, spending_score_1_100 → integer.

Final Dataset:
Rows: 200
Columns: 5

File produced: mall_customers_cleaned.csv

Outcome:
The dataset is now consistent, validated, and ready for exploratory data analysis and machine learning tasks such as clustering.
