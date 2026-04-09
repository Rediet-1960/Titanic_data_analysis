🚢 Titanic Data Analysis Project
📌 Project Overview

This project is part of a Data Science Bootcamp task.
The goal is to explore, clean, and analyze the Titanic dataset (train.csv) using Python and Pandas, and extract meaningful insights about passenger survival.

📊 Dataset Used
Source: Titanic Dataset (train.csv)
Contains passenger information such as age, sex, class, fare, and survival status.
🧰 Tools & Libraries
Python
Pandas
🔍 Project Steps
1. Data Exploration
Viewed dataset structure using .head()
Checked data types and missing values using .info()
Generated statistical summary using .describe()
2. Data Cleaning
Filled missing values in Age using median
Filled missing values in Embarked using mode
Removed Cabin column due to high missing values
Removed duplicate rows
Verified cleaned dataset
3. Feature Engineering
Created a new feature: Age_Group
Child (0–12)
Teen (13–18)
Adult (19–60)
Senior (60+)
4. Data Analysis

Used groupby() to analyze:

Survival rate by gender
Survival rate by passenger class
Average age per class
Survival rate by age group
5. Data Filtering

Extracted specific groups:

Female survivors
Children who survived
First-class passengers who survived
📈 Key Insights
Females had a higher survival rate compared to males.
First-class passengers had the highest chance of survival.
Children were given priority during rescue.
The highest survival group was females in first class.
📂 Project Structure
Titanic-Data-Analysis/
│
├── Titanic.ipynb
├── train.csv
└── README.md
🚀 How to Run
Open Jupyter Notebook or Google Colab
Upload train.csv
Run Titanic.ipynb step by step
📌 Author

Student Rediet Wondimu

⭐ Conclusion

This project demonstrates basic data analysis skills including data cleaning, grouping, filtering, and insight extraction using Pandas.
