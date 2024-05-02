# Boston-Housing-data-Analysis-Python

## Overview
Pandas and NumPy are powerful Python libraries for data analysis and manipulation. In this project, we will explore various functionalities of these libraries using real-life data from the Boston Housing dataset. This dataset contains information collected by the U.S Census Service concerning housing in the area of Boston, Massachusetts.

![image](https://github.com/Ajaj583/Boston-Housing-data-Analysis-Python/assets/158480555/7102b13b-ca4f-4f5f-abf2-2a35931558ff)


## Dataset
The dataset can be found [here](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices). It includes the following features:
- CRIM: Per capita crime rate by town
- ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS: Proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- NOX: Nitric oxides concentration (parts per 10 million)
- RM: Average number of rooms per dwelling
- AGE: Proportion of owner-occupied units built prior to 1940
- DIS: Weighted distances to five Boston employment centers
- RAD: Index of accessibility to radial highways
- TAX: Full-value property tax rate per $10,000
- PTRATIO: Pupil-teacher ratio by town
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT: Percentage of lower status of the population
- MEDV: Median value of owner-occupied homes in $1000s

## Questions Explored
1. **Data Loading:** Load the Boston Housing dataset into a Pandas DataFrame. Display the first 5 rows of the DataFrame.
2. **Data Exploration:** Use Pandas functions to explore the dataset. Find out the number of rows and columns, column names, data types of the columns, summary statistics, and check for missing values.
3. **Data Manipulation:**
   - Add a new column to the DataFrame that categorizes the ‘MEDV’ (median value of owner-occupied homes) column into ‘Low’, ‘Medium’, and ‘High’.
   - Replace the ‘CHAS’ column (Charles River dummy variable) with ‘Yes’ if CHAS = 1 and ‘No’ if CHAS = 0.
   - Rename the column ‘RM’ to ‘Rooms’.
4. **Data Analysis:**
   - Find out the average number of rooms (‘Rooms’ column) per dwelling for each category of ‘MEDV’ (Low, Medium, High).
   - Find out the percentage of houses that bound the Charles River.
5. **NumPy Operations:** Convert the ‘AGE’ column (proportion of owner-occupied units built prior to 1940) from the DataFrame to a NumPy array and perform operations like computing the mean, standard deviation, and normalization.

## Conclusion
Through this analysis, we gained valuable insights into the Boston Housing dataset. We observed correlations between various features and housing prices, identified trends and patterns, and performed basic data manipulations and operations. The findings from this analysis can be used to inform decision-making processes in the real estate industry and contribute to a better understanding of housing market dynamics in the Boston area.
## My Project
[You can chek here](https://github.com/Shirin997/Boston-Housing-Data-Analysis-Python/blob/main/Boston_Housing_data_EDA%20(1).ipynb)
## Authors

- [@Shirin997](https://github.com/Shirin997)

Shirin- Data Analyst - Shirin- All work

