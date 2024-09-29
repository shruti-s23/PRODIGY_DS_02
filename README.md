## Overview
This repository contains an exploratory data analysis (EDA) project on the Titanic dataset using Tableau. The project aims to explore relationships between variables, identify patterns, and visualize insights derived from the dataset.

## Dataset
The dataset used in this project is acquired from [Kaggle's Titanic competition](https://www.kaggle.com/c/titanic/data). It includes details of passengers aboard the Titanic, such as their age, gender, ticket class, fare, survival status, etc. The dataset is split into two parts: `train.csv` and `test.csv`. For this analysis, only the `train.csv` dataset is used.

## Cleaning Process
The dataset underwent a cleaning process to ensure data integrity and accuracy. Python was used in a Jupyter notebook `TASK02.ipynb` to clean the data and treat missing values. Techniques such as median imputation were used to handle missing values in variables like Age and Embarked.

## Visualization
Using Tableau, various visualizations were created to explore the relationships between variables and identify patterns and trends in the data. The visualizations include bar charts, scatter plots, histograms, packed bubbles, etc. These visualizations help in understanding the demographics of passengers, survival rates, ticket class distributions, fares, etc.

## Calculated Fields
Several calculated fields were created in Tableau to facilitate deeper analysis:
- **Age Groups**: Passengers were categorized into age groups (e.g., Child, Teen, Adult, Senior) to analyze survival rates and other metrics across different age ranges.
- **Fare Categories**: Fare amounts were divided into categories (e.g., Low, Medium, High) to study the relationship between fare price and survival.
- **Family Size**: A new field was created to represent the total number of family members aboard (siblings/spouses and parents/children) to explore its impact on survival chances.

## How to Use
1. **Accessing the Dataset**: The Titanic dataset `train.csv` can be downloaded from the Kaggle competition page [here](https://www.kaggle.com/c/titanic/data).
2. **Data Cleaning**: To replicate the data cleaning process, refer to the Jupyter notebook file named `TASK02.ipynb` provided in the repository.
3. **Visualization**: The Tableau visualization of the Titanic dataset is available in the Tableau file, in a packaged workbook named `TitanicDemographic.twbx` provided in the repository. The visualization includes multiple worksheets exploring different aspects of the dataset.
4. **Exploratory Data Analysis**: The Tableau dashboards provide insights into the Titanic dataset, exploring relationships between variables and identifying key patterns and trends. Four dashboards are included, each focusing on different aspects of the data.

