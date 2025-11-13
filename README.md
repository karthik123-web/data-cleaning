# Data Cleaning and Preprocessing - Medical Appointment Dataset

## Objective
The goal of this project is to clean and prepare the raw *Medical Appointment No Shows* dataset for analysis. The dataset originally contains missing values, duplicate rows, inconsistent formatting, and mixed data types. Cleaning the dataset ensures it is structured, consistent, and ready for further analysis or modeling.

## Tools Used
- *Python 3*  
- *Pandas* library for data manipulation  
- *Google Colab* as the development environment  

## Dataset
- *Raw Dataset:* Medical_Appointment_No_Shows.csv  
- *Cleaned Dataset:* Medical_Appointment_Cleaned.csv  

The cleaned dataset is free from duplicates, missing values have been handled, text and date formats standardized, and data types corrected.

## Summary of Cleaning Steps
1. *Removed duplicate rows* to avoid redundant data.  
2. *Handled missing values:* Filled missing entries in the gender column with 'unknown'.  
3. *Standardized text values:* Converted the gender column to lowercase to ensure consistency.  
4. *Renamed columns:* Converted all column names to lowercase and replaced spaces with underscores.  
5. *Date conversion:* Converted appointment_date to a consistent datetime format.  
6. *Numeric conversion:* Ensured the age column is of integer type.  

## Files in Repository
- data_cleaning_medical_appointments.ipynb → Notebook containing the Python code and detailed steps for data cleaning.  
- Medical_Appointment_Cleaned.csv → Cleaned dataset ready for analysis.  
- README.md → This file containing project overview and summary.

## How to Use
1. Open data_cleaning_medical_appointments.ipynb in Google Colab or Jupyter Notebook.  
2. Run all the cells to replicate the cleaning process.  
3. Download the Medical_Appointment_Cleaned.csv for analysis or modeling.  

---

*Repository Link Example:*
