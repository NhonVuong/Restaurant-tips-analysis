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

##### 4. The main goals
Analyze tipping behavior based on customer gender to identify any patterns or differences.

Explore relationships between tip amount and other variables such as total bill, day, sex, time, size using visualizations and statistics.

Generate insights that can help understand customer behavior in a restaurant setting.

Practice data analysis skills using Python, specifically with the pandas and matplotlib libraries for data handling and visualization.

##### 5. Results
###### Tip Amount by Gender (sex)
Male customers tipped an average of ~$3.09

Female customers tipped an average of ~$2.83

-> Men tend to tip slightly more than women in absolute value.

###### Impact of Smoking Status (smoker) on Tips
Non-smokers gave higher average tips than smokers:

Non-smokers: ~$3.05

Smokers: ~$2.83

-> Non-smoking customers tend to tip more.

###### Tip Amount by Day
Average tips were highest on Weekend, and lowest on Weekday:

Weekend: ~$3.12

Weekday: ~$2.76

-> Weekends are associated with higher tipping.

###### Tip Amount by Time of Day
Dinner time had higher average tips than Lunch:

Dinner: ~$3.10

Lunch: ~$2.73

-> Customers at dinner tend to leave larger tips than those at lunch.

###### Multivariate Insight
The group that tipped the most on average: Male, non-smokers, dining at dinner on Sunday

The group with the lowest average tips: Female, smokers, dining at lunch on Thursday
