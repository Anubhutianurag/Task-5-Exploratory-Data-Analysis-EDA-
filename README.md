# Task-5-Exploratory-Data-Analysis-EDA-
Project Overview
This repository contains the complete exploratory data analysis (EDA) of the Titanic dataset. The main focus is to extract meaningful patterns, identify potential survival factors, and prepare the data for further analysis or modeling.

Tools Used
Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook

Objectives
Analyze the distribution of key features in the dataset.
Identify relationships and trends that influence survival.
Visualize important feature interactions.
Summarize key findings to guide future predictive modeling.

Repository Structure
plaintext
Copy
Edit
├── data/
│   └── train.csv              # Titanic dataset used for EDA
├── summary.pdf                # Detailed summary of all findings and insights
├── Titanic_EDA.ipynb          # Complete Jupyter Notebook for the analysis
├── README.md                  # Project documentation (this file)
└── requirements.txt           # List of Python libraries required

Key Steps Performed
1. Data Loading & Cleaning
Missing values in the Age column were filled with the median age.
Missing values in the Embarked column were filled with the most frequent port of embarkation.
The Cabin column was dropped due to excessive missing values.

2. Univariate Analysis
Age: Majority of passengers were between 20 to 40 years.
Fare: Distribution was highly right-skewed, with a few passengers paying very high fares.
SibSp & Parch: Most passengers traveled alone or with small families.
Categorical Counts:
Highest proportion of passengers were in 3rd class.
More males than females on board.
Majority of passengers embarked from Southampton.

3. Bivariate & Multivariate Analysis
Survival Trends:
Higher survival rates observed among passengers who paid higher fares and those in 1st class.
Females and children had higher chances of survival.
Correlation Findings:
Strong negative correlation between Fare and Pclass.
Positive correlation between family-related features (SibSp and Parch).

Visual Confirmations:
Pairplots, heatmaps, scatterplots, and boxplots were used to validate feature relationships and trends.

Final Findings
A comprehensive summary of all key observations, patterns, and visual insights is provided in summary.pdf.

Acknowledgements
This analysis is based on the Titanic dataset provided by Kaggle.










