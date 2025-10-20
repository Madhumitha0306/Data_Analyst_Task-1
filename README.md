# Data_Analyst_Task-1

 Customer Personality Analysis – Data Cleaning & Preprocessing
 
📘 Overview
* This project focuses on cleaning and preprocessing the Customer Personality Analysis dataset from Kaggle.
The dataset contains customer demographic and behavioral information used to understand marketing strategies and customer segmentation.

* The main goal of this task is to prepare the raw dataset by handling missing values, removing duplicates, fixing inconsistent formats, and standardizing data types — ensuring the dataset is ready for further analysis and modeling.

🎯 Objectives
* Identify and handle missing values
* Remove duplicate entries
* Standardize categorical variables and text formatting
* Convert date columns to proper datetime types
* Ensure column names are consistent and clean
* Export a final cleaned dataset for analysis

🧰 Tools & Libraries Used
* Python 3.x
* Pandas – for data manipulation and cleaning
* NumPy – for numerical operations
* Google colab – for implementation and testing

🗂️ Dataset Information
* Dataset Name: Customer Personality Analysis
* Source: Kaggle Dataset 

Key Columns:
* ID, Year_Birth, Education, Marital_Status, Income
* Kidhome, Teenhome, Dt_Customer, Recency
* MntWines, MntFruits, MntMeatProducts, NumDealsPurchases, etc.

⚙️ Data Cleaning Steps
* Loaded Dataset using pd.read_csv() with sep='\t' to correctly separate tab-delimited columns.
* Removed Duplicate Rows using .drop_duplicates().
* Handled Missing Values – Filled missing Income values with column mean.
* Standardized Text Columns – Cleaned and formatted Education and Marital_Status values.
* Fixed Inconsistent Categories – Merged similar values like "Alone", "YOLO", "Absurd" → "Single".
* Converted Date Columns – Dt_Customer converted to datetime format.
* Renamed Columns – All column names changed to lowercase and snake_case.
* Saved Final Cleaned Dataset as customer_personality_cleaned.csv.

💡 Key Learnings
* Importance of consistent formatting before analysis
* Handling missing and inconsistent data
* Efficient use of Pandas for preprocessing large datasets
* Preparing data for further stages like EDA and modeling
