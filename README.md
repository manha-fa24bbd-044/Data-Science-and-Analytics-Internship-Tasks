# Data-Science-and-Analytics-Internship-Tasks
This repository contains the tasks given based on my internship in data science and analytics

○ **Task Objective**

The objective of this project was to perform exploratory data analysis (EDA) and build a foundational understanding of datasets for data science tasks. Specifically:

Analyze the Iris dataset to understand feature relationships and distributions through visualization
Work on a credit risk (loan prediction) dataset to handle missing values and explore factors affecting loan approval
Extract meaningful insights that support data-driven decision-making

○ **My Approach**

Data Loading & Inspection
Loaded datasets using Pandas and Seaborn
Explored dataset shape, columns, and sample records
Data Cleaning
Identified missing values in the loan dataset
Handled missing data:
Numerical features 
→ filled with median
Categorical features 
→ filled with mode
Exploratory Data Analysis (EDA)
Used Matplotlib and Seaborn for visualization
Created:
Scatter plots (feature relationships)
Histograms (distribution analysis)
Count plots (categorical comparisons)
Box plots (outliers & spread implied)
Feature Analysis
Examined relationships between variables like income, loan amount, and loan status
Compared categorical features (gender, education, property area, etc.) against loan approval

○ **Results and Insights**

**Iris Dataset**

Clear separation between species based on petal and sepal measurements
Certain features (like petal length) are strong indicators for classification

**Loan Dataset**

Missing data was successfully handled, improving dataset quality
Income and loan amount show skewed distributions, indicating variability among applicants
Credit history appears to be a strong factor influencing loan approval
Categorical features (e.g., marital status, property area) show noticeable patterns in loan outcomes

**Overall Insight**

Data visualization helped uncover hidden patterns and relationships
Proper data cleaning significantly improves analysis reliability
Feature-level insights can support predictive modeling for credit risk
