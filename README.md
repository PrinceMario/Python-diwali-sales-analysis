# Python-diwali-sales-analysis

## Project Overview
 This project is to analyze sales data during the Diwali season to understand trends, patterns, and customer behavior, in order to optimize marketing strategies and maximize revenue for future Diwali seasons.

 ## Project Goals
 - Determine which product categories achieved the highest sales during the Diwali season.
 - Explore which age groups and genders made the most purchases during Diwali.
 - Identify and rank the 10 products that sold the highest quantities during the Diwali sales period.

## Steps Taken
### Data Preprocessing 
- First, importing the necessary libraries for data manipulation and visualization:
    - import pandas as pd
    - import numpy as np
    - import matplotlib.pyplot as plt
    - import seaborn as sns 
- Loading my raw data from a CSV file into a pandas DataFrame:
    - df = pd.read_csv('your_dataset.csv') 
- Exploreing the structure and contents of your dataset using pandas functions:
    - print(df.head())
    - print(df.shape)
    - print(df.describe())
    - print(df.isnull().sum()) 
- Removeing rows or columns with a significant number of missing values to ensure data integrity:
    - df.dropna(inplace=True)
    - df.dropna(axis=1, inplace=True) 
