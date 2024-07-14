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

### Data Visualization And Insights
Data visualization is crucial for gaining insights from your data and communicating findings effectively. In Python, libraries like matplotlib and seaborn provide powerful tools for creating various types of visualizations.

### Exploratory Data Analysis
#### Gender
 - plotting a bar chart for Gender and it's count
    ![Screenshot 2024-07-14 161014](https://github.com/user-attachments/assets/c3a9ec07-c69b-4578-8e6c-f284f968c6c3)

   ![Screenshot 2024-07-14 161303](https://github.com/user-attachments/assets/4335f4d0-c28d-4a5a-b27f-b2fd4ebe6c4f)

- plotting a bar chart for gender vs total amount
  ![image](https://github.com/user-attachments/assets/b2ffa89a-52d8-4fb2-94e0-fe4f79aaf328)

  ![image](https://github.com/user-attachments/assets/c30b8063-ae09-4a91-9800-99060cf17dcf)

