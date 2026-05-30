# Netflix Data Cleaning and Preprocessing

## Project Overview

This project demonstrates data cleaning and preprocessing techniques on the Netflix Titles dataset using Python and Pandas.

The objective is to improve data quality by handling missing values, checking duplicates, standardizing text fields, converting date formats, validating data types, and exporting a cleaned dataset for further analysis.

---

## Dataset Information

* Dataset: Netflix Titles Dataset
* Original Dataset Size: 8,807 rows × 12 columns
* Cleaned Dataset Size: 8,797 rows × 12 columns

---

## Data Cleaning Tasks Performed

### 1. Missing Value Handling

Handled missing values in:

* director
* cast
* country
* rating

Missing categorical values were replaced with meaningful placeholders such as:

* Unknown
* Not Available

### 2. Duplicate Detection

Checked the dataset for duplicate records.

* Duplicate Rows Found: 0
* Duplicate Rows Removed: 0

### 3. Text Standardization

Performed text cleaning by:

* Removing extra spaces
* Standardizing formatting
* Improving consistency across columns

### 4. Date Conversion

Converted the `date_added` column into a proper datetime format for easier analysis.

### 5. Column Renaming

Renamed columns where necessary to maintain consistency and readability.

### 6. Data Type Validation

Verified and validated data types for all columns.

### 7. Export Cleaned Dataset

Saved the processed dataset as:

`netflix_titles_cleaned.csv`

---

## Results

### Dataset Shape Comparison

| Stage           | Rows | Columns |
| --------------- | ---- | ------- |
| Before Cleaning | 8807 | 12      |
| After Cleaning  | 8797 | 12      |

### Remaining Missing Values

| Column     | Missing Values |
| ---------- | -------------- |
| date_added | 88             |
| duration   | 3              |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Google Colab
* GitHub

---

## Repository Contents

```text
Netflix-Data-Cleaning/
│
├── netflix_titles.csv
├── netflix_titles_cleaned.csv
├── netflix_data_cleaning.ipynb
├── README.md
├── requirements.txt
├── before_cleaning.png
└── after_cleaning.png
```

---

## Output

A cleaned and standardized Netflix dataset ready for exploratory data analysis and visualization.

---

## Author

**Vivek Vardhan Gubbala**
