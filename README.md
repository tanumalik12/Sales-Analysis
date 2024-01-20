# Sales-Analysis



**Project Overview**  ----
Task : Data Exploration and Summary 
Description: Explore a dataset and summarize its key characteristics. 
Task Documentation: 
Dataset Selection: 
● Choose a dataset for analysis, such as a CSV file containing sales data. 
Data Loading: 
● Load the dataset into a suitable tool like Python using libraries like pandas. 
Overview and Summary: 
● Display the first few rows and basic summary statistics of the dataset. 
Data Types: 
● Identify the data types of different columns (numeric, categorical, datetime, etc.). 
Missing Values: 
● Identify columns with missing values and decide on handling strategies 
(imputation, removal, etc.). 
Data Visualization: 
● Create visualizations like histograms, scatter plots, and bar charts to understand 
the data distribution. 
Documentation: 
● Describe the dataset's purpose, your initial observations, and the summary

For this task, I have chosen the "Titanic" dataset from Kaggle. The dataset contains information about the passengers who were aboard the Titanic, including their demographics, cabin class, ticket fare.

**Data Loading** ---
I loaded the dataset into a Google Colab using the pandas library.
I also loaded various libraries of python like: numpy, pandas, matplotlib, seaborn, etc.

**Codes and Resources Use** ---
I used Python to code my project.
Resource: Google Colab.

**Python Packages Used** ---
packages used as -
Data Manipulation: Packages used for handling and importing dataset such as pandas, numpy and others.
Data Visualization: Include packages which were used to plot graphs in the analysis or for understanding the ML modelling such as seaborn, matplotlib and others.

**Data Preprocessing**
Missing Values:
I identified columns with missing values using the isnull() function and calculated the percentage of missing values in each column.

Data Visualization:
I created visualizations like histograms, scatter plots, and bar charts to understand the data distribution. Here are a few examples:
-Histogram of Age distribution
-Bar chart of the number of passengers in each cabin class
-Scatter plot of age vs fare

**Code structure** ---
Here is the basic suggested skeleton for my data analytics repo 
├── data
│   ├── data1.csv
│   ├── cleanedData
│   │   ├── cleaneddata1.csv
├── data_acquisition.py
├── data_preprocessing.ipynb
├── data_analysis.ipynb
├── data_visualisation.ipynb
├── README.md

**Results and evaluation** ---
n class, ticket fare, and whether or not they survived the disaster. The dataset has 891 rows and 12 columns. The data types of different columns include integer, float, and object. The column "Age" has 19.87% missing values, "Cabin" has 77.10% missing values, and "Embarked" has 0.22% missing values. From the initial exploration of the dataset, we can see that the majority of the passengers were in third class, and there were more male passengers than female passengers. The age distribution is slightly right-skewed, with most passengers being between 20 and 40 years old. We can also see that there is a positive correlation between age and fare.
