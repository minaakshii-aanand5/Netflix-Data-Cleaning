# Netflix Data Cleaning Project

## Overview
This project focuses on cleaning and standardizing the Netflix Movies and TV Shows dataset using Google Sheets. The goal was to convert a messy real-world dataset into a clean, structured, and analysis-ready format.

## Dataset
The dataset used is the Netflix Movies and TV Shows dataset from Kaggle. It contains information such as title, director, country, release year, rating, duration, and date added.

## Cleaning Steps Performed
The following data cleaning steps were carried out:

- Preserved the original raw dataset in a separate sheet (Raw_Data).
- Identified missing values in columns such as director, country, date_added, and rating.
- Filled missing rating values with "Not Rated".
- Standardized text fields (title, director, and country) using trimming and proper capitalization.
- Converted date_added into a proper YYYY-MM-DD date format.
- Standardized rating values.
- Created a final Cleaned_Data sheet containing only cleaned and validated data.
- Added a Data_Quality_Notes column to document issues found in the dataset.

## Files in this Repository
- Raw_Data.xlsx – Original unmodified dataset.
- Cleaned_dataset.xlsx – Cleaned and standardized dataset.
- cleaned_dataset.csv – Cleaned dataset in CSV format for further analysis.

## Outcome
The final dataset is free from formatting issues, has standardized text and dates, and properly handled missing values. It is now ready for data analysis, visualization, or machine learning tasks.
 
**Author:** Minaakshii Aanand
