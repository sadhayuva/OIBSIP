Data Cleaning Project – Airbnb NYC Dataset
Project Overview

This project focuses on data cleaning and preprocessing using the Airbnb New York City dataset (AB_NYC_2019.csv). Data cleaning is a crucial step in data analysis because raw datasets often contain missing values, duplicates, inconsistent formats, and outliers.

The goal of this project is to ensure data integrity, consistency, and reliability before performing any analysis or machine learning tasks.

Dataset

Dataset used in this project:

AB_NYC_2019.csv

The dataset contains information about Airbnb listings in New York City including:

Listing name

Host name

Neighbourhood

Room type

Price

Reviews

Availability

Dataset Source:

New York City Airbnb Open Data

Objectives

The main objectives of this project are:

Ensure data integrity and accuracy

Handle missing values

Remove duplicate records

Standardize dataset formatting

Detect and handle outliers

Data Cleaning Steps
1. Data Exploration

Loaded the dataset using Python Pandas

Checked dataset structure using .info() and .describe()

2. Handling Missing Values

Missing values were identified and handled using:

Filling text columns with "Unknown"

Replacing numeric missing values using the median

3. Removing Duplicates

Duplicate rows were detected and removed to maintain data uniqueness.

4. Standardization

Column names converted to lowercase

Date columns converted into datetime format

5. Outlier Detection

Outliers in the price column were detected using the Interquartile Range (IQR) method and removed.

Technologies Used

Python

Pandas

NumPy

Jupyter Notebook / Google Colab

Project Structure
Data-Cleaning-Project
│
├── dataset
│   └── AB_NYC_2019.csv
│
├── code
│   └── airbnb_data_cleaning.py
│
├── output
│   └── cleaned_airbnb_data.csv
│
└── README.md
Output

After cleaning, a new dataset cleaned_airbnb_data.csv is generated which is ready for further analysis and visualization.
