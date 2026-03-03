# youtube-dataset-wrangling-pandas
Dataset Cleaning Using Python Script

🧹 Massive YouTube Dataset Cleaning & Wrangling Pipeline

📌 Overview
This project focuses on transforming a massive, highly unstructured YouTube dataset (**250,000+ rows**) sourced from Kaggle into a clean, structured, and analysis-ready format. The primary goal was to perform heavy data wrangling to prepare the raw data for advanced engagement analytics and SQL querying.

🛠️ Tech Stack Used
Language: Python
Libraries: Pandas, NumPy
Database: SQL (for final structured queries and validation)

⚠️ The Data Challenges
The raw 400MB dataset contained numerous real-world data inconsistencies:
* Thousands of Null/missing values in critical engagement columns.
* Duplicate video entries skewing the metrics.
* Inconsistent data types (e.g., Dates formatted as strings, View counts containing text characters).
* Unstructured text in titles and descriptions.

🚀 The Cleaning Process
I built a robust Python pipeline to automate the cleaning process:
1. Data Ingestion & Inspection: Efficiently loaded the massive CSV file using Pandas.
2. Handling Missing Data: Imputed or dropped missing values logically without losing statistical relevance.
3. Data Type Conversion: Standardized Date/Time objects and stripped non-numeric characters from Views, Likes, and Comments columns.
4. Deduplication: Identified and safely removed duplicate rows.
5. Exporting: Saved the finalized, pristine dataset into a lightweight format, ready for direct SQL database integration.

📁 Note on Dataset
The original raw dataset is over 400MB and is not hosted in this repository due to GitHub limits. You can find the original raw data on Kaggle. I have included a clean_sample.csv (Top 100 rows) in this repository to showcase the final structured output.

 How to Run
1. Clone this repository.
2. Ensure you have the required libraries: pip install pandas numpy
3. Run the cleaning script: python [tumhari_script_ka_naam].py
