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

#### Age
- plotting a bar chart for age group

  ![image](https://github.com/user-attachments/assets/ee987200-ddc1-4f42-8d04-9b6c362f24f7)

  ![image](https://github.com/user-attachments/assets/80b918c0-8d6b-4c87-a3e5-08289228f698)

- Total Amount vs Age Group

  ![image](https://github.com/user-attachments/assets/60930746-ada3-4056-a5a8-8c95b52be604)

  ![image](https://github.com/user-attachments/assets/7ccc2ec5-fb8d-482f-8e4b-7df4df5de736)

#### State
- total number of orders from top 10 states

  ![image](https://github.com/user-attachments/assets/b613522a-f357-4195-90b8-62cfd87f5034)

  ![image](https://github.com/user-attachments/assets/2da61742-d94b-45cc-8557-20b78da40aaf)

- total amount/sales from top 10 states

  ![image](https://github.com/user-attachments/assets/68bd8775-7a77-430f-a72b-8a9e5ed0cdb8)

  ![image](https://github.com/user-attachments/assets/5afdb9d0-24f1-43c9-af10-bf0bcea2efa9)

#### Martial status
- plotting a bar chart for martial status

  ![image](https://github.com/user-attachments/assets/278ec6fe-112f-40e8-b76d-450c5d9e9cd9)

  ![image](https://github.com/user-attachments/assets/58a49516-7492-43ee-84a0-3941efaced0b)



  
