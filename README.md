# data-analysis-midterm-project
Python-based data analysis project demonstrating multi-file ingestion, data preprocessing, and exploratory data analysis using Pandas.
📊 Data Analysis Midterm Project (Python)
📌 Project Overview

This repository contains my midterm data analysis project, completed as part of my MBA (Business Analytics) coursework.
The project demonstrates my ability to programmatically handle multiple datasets, perform data preprocessing, and conduct exploratory data analysis (EDA) using Python.

The notebook reflects practical, industry-relevant skills expected of a Data Analyst / Data Science Intern, including file handling, data merging, and structured analysis.


🎯 Project Objectives

-> Load and manage multiple CSV files from a directory

-> Automate data ingestion using Python

-> Merge datasets into a single consolidated DataFrame

-> Inspect and understand data structure and content

-> Prepare clean data for further analysis and visualization


🛠️ Tools & Technologies

--Python

--Jupyter Notebook

--Pandas – data loading, concatenation, manipulation

--NumPy – numerical computations

--OS module – directory and file handling

--Lets-Plot / ggplot-style visualization tools

--Numerize – formatting large numerical values


📂 Repository Structure
📁 Repository
 ┣ 📄 LSE_ME2024_2026_Midterm_1P25MB029.ipynb
 ┗ 📄 README.md


🔍 Methodology

-->Imported and configured required Python libraries

-->Programmatically accessed datasets using directory traversal

-->Loaded multiple CSV files into Pandas DataFrames

-->Concatenated datasets into a unified structure

-->Performed preliminary data inspection (head(), shape, structure)

-->Created a clean base dataset for further analysis


🔧 Data Cleaning & Preprocessing 
🧹 Price Standardization

-> Implemented a custom price-cleaning function to convert heterogeneous price formats into numeric values

-> Handled multiple price representations including:

Pound (£) values

Pence (p) values converted to decimal format

Estimated prices (e.g., each est.)

Price ranges (hyphen-separated values).


Standardized all prices to a float data type for numerical analysis

Insight:

-> Standardizing price formats ensured consistency across the dataset and enabled accurate statistical analysis.


🗑️ Data Deduplication & Column Pruning

-> Removed duplicate records to prevent biased analysis

-> Dropped irrelevant metadata columns that were not required for analytical objectives.


Renamed columns to clear, human-readable labels for better interpretability

Insight:

-> Removing redundant data and unnecessary attributes improved dataset clarity and reduced noise.


🔢 Data Type Optimization

-> Converted product identifiers to 32-bit integers to optimize memory usage


Ensured correct data types across numerical and categorical columns

Insight:

-> Proper data typing improves performance and aligns with best practices in data engineering.

📏 Handling Range-Based Attributes

-> Identified rows containing range-based price values

-> Extracted and retained the lower bound of price ranges for consistency


Synchronized related attributes (such as product size) to maintain data integrity

Insight:

->  Handling range-based values prevented ambiguity and ensured one-to-one alignment between price and size attributes.

📊 Statistical Summary Refinement

-> Renamed percentile columns (25%, 50%, 75%) to Q1, Median, and Q3


Improved readability of summary statistics for business interpretation

Insight:

-> Clear statistical labels make exploratory findings more accessible to both technical and non-technical stakeholders.


Data Type Distribution:
--Insight

-->The dataset consists of a mix of numerical and categorical variables, requiring different preprocessing strategies for analysis and modeling.


📈 Results & Insights

--Successfully combined multiple raw datasets into a single, analysis-ready DataFrame

--Improved efficiency by automating file reading instead of manual uploads

--Identified the overall structure and key attributes of the merged dataset

--Established a strong foundation for:

--Exploratory Data Analysis (EDA)

--Statistical analysis

--Visualization and reporting

--Demonstrated real-world data handling practices commonly used in analytics projects


🚀 How to Run the Project

Clone this repository or download the notebook

Open the .ipynb file using Jupyter Notebook / Jupyter Lab

Install required libraries if needed

Run cells sequentially to reproduce results


👩‍🎓 Author

Robisha R P
MBA – Business Analytics
Aspiring Data Analyst / Data Scientist


📌 Academic & Career Note

This project was developed for academic evaluation, but it also reflects industry-relevant data analysis skills, including:

Data ingestion pipelines

Dataset consolidation

Analytical thinking using Python
