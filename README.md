# Data Cleaning and Preprocessing - Medical Appointment Dataset

*Objective:*  
Clean and prepare a raw dataset with nulls, duplicates, and inconsistent formats.

*Tools Used:*  
Python (Pandas) in Google Colab

*Files in Repository:*  
- data_cleaning_medical_appointments.ipynb → Notebook with code and cleaning steps  
- Medical_Appointment_Cleaned.csv → Cleaned dataset  

*Summary of Data Cleaning:*  
- Removed duplicate rows  
- Filled missing values in 'gender' column with 'unknown'  
- Standardized text in 'gender' column (lowercase)  
- Renamed columns to lowercase with underscores  
- Converted 'appointment_date' to datetime format  
- Converted 'age' column to integer type
