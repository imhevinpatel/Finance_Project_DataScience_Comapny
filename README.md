# Finance_Project_DataScience_Comapny

Credit Card Approval Shiny App

Overview

The Credit Card Approval Shiny App is designed to analyze and visualize the factors that influence the approval of credit card applications. By leveraging various data mining techniques, the app allows users to explore how attributes like gender, age, income, years employed, and more impact the likelihood of credit card approval.

Features

Interactive Visualizations: Explore the influence of different attributes on credit card approval through interactive scatter plots, histograms, and box plots.
Data Preprocessing: The dataset undergoes several preprocessing steps, including handling missing values, transforming categorical variables, and renaming attributes for clarity.
Exploratory Data Analysis (EDA): Analyze the distribution of key variables and their relationships with the credit card approval outcome.
Predictive Insights: Gain insights into the most significant factors affecting credit card approval, such as employment status, income, credit score, and prior defaults.
Dataset

The dataset used in this project contains 690 records, each representing an individual applying for a credit card. It includes 16 variables:

The first 15 variables represent attributes such as gender, age, marital status, years employed, etc.
The 16th variable is the outcome of the application (approved or rejected).
Data Preprocessing

Several preprocessing steps were performed on the dataset:

Categorical Transformation: Converted categorical variables to binary values (e.g., 't' and 'f' to 1 and 0).
Missing Data Treatment: Imputed missing values using median values for numerical fields and mode for categorical fields.
Data Cleaning: Removed or transformed irrelevant fields like ZipCode.
Attribute Renaming: Renamed attributes for clarity and confidentiality.
Exploratory Data Analysis (EDA)

Continuous Variables: Initial plots showed that variables like age, debt, credit score, income, and years employed have skewed distributions. Log transformations were applied to reduce skewness.
Discrete Variables: Variables like prior default and employment status were found to significantly impact credit approval outcomes.
Pairwise Comparison: Scatter plots were used to compare all fields, revealing that years employed has the highest linear correlation with credit approval.
Conclusion and Future Work

The initial analysis identifies employment status, income, credit score, and prior default as the most significant factors in credit card approval. Future work may involve building predictive models based on these insights and incorporating additional variables such as criminal records, health information, and net balance between monthly income and expenses.
ggplot2: Visualization library for creating plots.
dplyr and tidyr: Data manipulation packages for cleaning and transforming data.
