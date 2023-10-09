# Market_Basket_Analysis_Using_Groceries_Dataset
1 Introduction
1.1 Dataset Overview
The dataset has 38,765 entries and 3 columns.
There are no missing values in the dataset.
The columns are as follows:
Member_number: The identification number of the member (Integer type)
-Date: The date of the transaction (Object type, should be converted to DateTime)

item description: Description of the item purchased (Object type)

1.2 Goal
The project involves analyzing the Kaggle Groceries dataset to study sales forecasting. Aiming to use and understand time-series analysis to forecast the sales of the most frequently purchased items. This helps in inventory management and promotional planning.

1.3 Load The Data

2 Exploratory Data Analysis
2.1 Data Overview
The dataset comprises 3 variables, encompassing 2 categorical and 1 numerical attribute, across a total of 38,765 observations. Presented below is a concise overview of the dataset.
2.2 Data Cleaning and Transformation
Transformed the 'Date' column to datetime format and resampled the data to a daily frequency for time-series analysis. Filled any missing values with zeros.
2.3 Visualization
To understand the data structure, use suitable plots like line graphs or bar charts, taking into account the variable types in the time series.

3 Modeling
3.1 Model Selection and Tuning

