# Task5-Titanic-Data-Cleaning

 📌 Overview
This repository contains the completed Task 5 for the Data Analyst Internship — a data cleaning project using the Titanic dataset with Python and Pandas.

 🛠️ Tools Used
- Google Colab
- Pandas
- NumPy

 🧹 Cleaning Steps Performed
1. Loaded the Titanic dataset (`train.csv`) into a DataFrame.  
2. Explored the data structure using `.head()` and `.info()`.  
3. Identified missing values using `isnull().sum()`.  
4. Dropped the `Cabin` column due to excessive missing values.  
5. Filled missing `Age` values using the median.  
6. Filled missing `Embarked` values using the mode.  
7. Encoded categorical variables (`Sex`, `Embarked`).  
8. Removed irrelevant columns (`Name`, `Ticket`).  
9. Checked and confirmed no duplicates.  
10. Saved the cleaned dataset as `titanic_cleaned.csv`.

 📁 Files Included
- `Task5_Cleaning.ipynb` — Python notebook with all cleaning steps and markdown explanation  
- `titanic_cleaned.csv` — Exported cleaned dataset

 📊 Final Outcome
The dataset is fully cleaned and ready for data analysis or machine learning tasks.

 👤 Author
Kolli Navya
