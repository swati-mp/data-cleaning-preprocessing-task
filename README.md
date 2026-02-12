# 📊 Data Cleaning and Preprocessing – Internship Task 1

## 🧾 Objective

The goal of this task is to clean and preprocess a raw dataset containing missing values, duplicates, and inconsistent formats, and prepare it for analysis or modeling.

---

## 📂 Dataset Used

Netflix Movies and TV Shows Dataset (Kaggle)

---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- Jupyter Notebook  

---

## 📁 Project Structure

data-cleaning-preprocessing-task/

data/  
- netflix_raw.csv  

cleaned_data/  
- netflix_cleaned.csv  

data_cleaning.ipynb  
README.md  

---

## ✅ Data Cleaning Steps Performed

1. Loaded dataset using Pandas.
2. Identified missing values using isnull().
3. Filled missing text columns (director, cast, country) with "Unknown".
4. Removed rows with missing date_added.
5. Removed duplicate records using drop_duplicates().
6. Standardized text columns (converted to lowercase).
7. Cleaned and converted date_added to datetime format.
8. Renamed column headers to lowercase with underscores.
9. Fixed data types (release_year converted to integer).
10. Saved the cleaned dataset to a new CSV file.

---

## 📌 Key Challenges Faced

- Inconsistent date formats  
- Leading spaces in date values  
- Missing values in multiple columns  

These were handled using:

- str.strip()  
- pd.to_datetime(errors='coerce')  
- dropna()  
- fillna()  

---

## 📈 Outcome

A clean, structured dataset ready for data analysis or visualization.

This task helped in understanding real-world data issues and applying preprocessing techniques using Pandas.

---

## 🚀 Conclusion

This project demonstrates essential data cleaning skills such as handling missing values, removing duplicates, standardizing formats, and preparing datasets for analysis.
