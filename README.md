# 2506-02_Task-1-Data-Cleaning-and-Preprocessing
Elavate Lab Data Analysis 
# 📊 Task 1 – Data Cleaning & Preprocessing (Netflix Dataset)

## 🧑‍💻 Internship: Data Analyst | Task by [Your Company/Organization Name]

---

## 🎯 Objective

The goal of this task is to clean and preprocess the **Netflix Movies and TV Shows dataset** by:
- Identifying and handling missing values
- Removing duplicate records
- Standardizing and formatting text data
- Converting inconsistent data formats
- Renaming columns to a uniform structure
- Preparing the dataset for analysis

---

## 🛠 Tools & Technologies Used

- **Google Colab** (Python Environment)
- **Python 3**
- **Pandas** for data manipulation
- **NumPy** for numerical operations

---

## 📁 Dataset Source

[Netflix Movies and TV Shows – Kaggle](https://www.kaggle.com/datasets/rahulvyasm/netflix-movies-and-tv-shows)

---

## ✅ Cleaning Steps Performed

1. **Loaded dataset** using Pandas.
2. **Handled missing values** using `fillna()` with placeholder values.
3. **Removed duplicate rows** using `drop_duplicates()`.
4. **Standardized text columns** (e.g., `country`, `rating`) using string methods.
5. **Converted date formats** using `pd.to_datetime()` for `date_added`.
6. **Renamed column headers** to lowercase with underscores.
7. **Checked and corrected data types** (e.g., converted `release_year` to `int`).
8. **Exported** the cleaned dataset to a new CSV file.

---

## 📂 Repository Structure

