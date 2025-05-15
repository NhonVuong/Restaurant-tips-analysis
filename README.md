# Restaurant-tips-analysis
##### 1. Project Title
Restaurant tips analysis
##### 2. A brief description of what your project does
This project analyzes restaurant tipping behavior using a dataset containing information such as total bill, tip amount, customer gender, smoking status, day, time, and party size. The goal is to uncover insights and patterns in tipping habits—such as whether gender influences tipping, how tip amounts relate to total bills, and how other factors like smoking or time of day affect tips. The project includes data cleaning, exploratory analysis, visualizations, and statistical testing to support data-driven conclusions.
##### 3. A description of the data it uses, including
###### Source of the Data:
The dataset was collected independently and saved as a CSV file [https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv](https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv)

###### Description of the Dataset:
The dataset includes records of dining transactions, capturing details about the bill, tip amount, customer demographics, and other context-related information.
| Column Name | Description |
| --- | --- |
| id | Unique identifier for each transaction |
|total_bill  | 	Total bill amount (USD) |
|tip  | 		Tip amount given (USD) |
| sex | Gender of the customer (Male, Female) |
|smoker  |Whether the customer is a smoker (Yes/No)  |
| day | Day of the week (Thur, Fri, Sat, Sun) |
| time |Time of day (Lunch, Dinner)  |
|size  | Number of people in the dining party |
###### How to Access the Data:
```
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv("https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv")
```
