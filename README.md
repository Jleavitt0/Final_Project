# Final_Project

# Loan Prediction Model Analysis
## Overview
This repository contains an analysis of a loan prediction model, exploring various factors that contribute to decrease loan defaults. The analysis is performed using Python libraries such as Matplotlib and Pandas for data visualization and manipulation, and the results are presented in Tableau for interactive visualizations.

# Table of Contents

- Dataset
- Analysis
- Data reprocessing
- Loan Prediction Model
- Visualization in Tableau
  
## Dataset
The dataset used for this analysis is loan default prediction dataset, which includes information on loan applicants, their financial details, and whether their loan applications were approved or rejected. The dataset is available at https://www.kaggle.com/datasets/nikhil1e9/loan-default/.

## Analysis
Exploratory Data Analysis (EDA)
The exploratory data analysis phase involves using Pandas for data manipulation and Matplotlib for data visualization. Key aspects explored include:

- Age of applicants
- Income levels of applicants
- Number of credit lines
- Loan Amount
- Credit score

## Data Preprocessing
Data preprocessing steps include handling missing values, converting categorical variables, and scaling numerical features. Pandas is utilized for these tasks to ensure the data is ready for modeling.

## Loan Prediction Model
A machine learning model is built using TensorFlow, and its performance is evaluated. Visualizations using Matplotlib are employed to illustrate the model's predictions and highlight key features influencing loan approval.

## Visualization in Tableau
The analysis is complemented by interactive visualizations created in Tableau. These visualizations provide a more comprehensive and user-friendly view of the patterns and insights uncovered during the analysis.

https://public.tableau.com/app/profile/leo.antinozzi/viz/Project4workbook_17011366201590/Sheet4?publish=yes

## Analysis Results
While the purpose of this was to demonstrate how a model can be built using the data, it is noted that the insights for this data are specific to this set. The other purpose was to demonstrate the proverbial "gut check" on the data, that preliminary viewing of the data can help determine if/how the data set may be useful. 

Ultimately this machine learning model determined that for the loans within this dataset the top 5 most important factors when it came to predicting a defaulting loan would be Age, interest rate, income, months employed, and loan amount, in that order. Our graphs were more limited in their effectiveness, simply because they were hampered by how consistent this dataset was in its distrubion. Many of the high-level summary statistics we acquired via Pandas and PySpark demonstrated how close/similar many of the records were, 

This may also have been the intent of this dataset and the importance of a well developed machine learning model: That machine learning models are adept at isolating and then predicting specific factors that otherwise would be difficult to determine or isolate. 
