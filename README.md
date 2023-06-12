# Data Analysis with Python Project for IBM

This project focuses on data analysis using Python within the context of IBM. It aims to demonstrate how to perform various data analysis tasks, including data cleaning, exploratory data analysis (EDA), feature engineering, and building predictive models.

## Objective

The objective of this project is to showcase the application of Python in data analysis and provide insights into the data being analyzed. The project covers various aspects of the data analysis process, including data preprocessing, visualization, statistical analysis, and model development.

## Dependencies

The following dependencies are required for this project:

- pandas
- matplotlib
- numpy
- seaborn
- sklearn.pipeline
- sklearn.preprocessing
- sklearn.linear_model

Please make sure to have these dependencies installed before running the code.

## Dataset

The project utilizes a dataset containing housing data. The dataset is imported from the following URL:

'https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DA0101EN/coursera/project/kc_house_data_NaN.csv'


## Questions Solved

1. Display the data types of each column using the attribute dtypes.
2. Drop the columns "id" and "Unnamed: 0" from axis 1 using the method drop() and obtain a statistical summary of the data using the describe() method.
3. Count the number of houses with unique floor values using the value_counts() method and convert it to a dataframe using the to_frame() method.
4. Produce a boxplot using the seaborn library to compare price outliers between houses with and without a waterfront view.
5. Use the regplot function in the seaborn library to determine the correlation between the feature "sqft_above" and the price.
6. Fit a linear regression model to predict the price using the feature "sqft_living" and calculate the R^2 value.
7. Fit a linear regression model to predict the price using a list of selected features.
8. Create a pipeline object that scales the data, performs a polynomial transform, and fits a linear regression model. Calculate the R^2 value.
9. Create and fit a Ridge regression object with a regularization parameter of 0.1 and calculate the R^2 value.
10. Perform a second-order polynomial transform on the data, create and fit a Ridge regression object with a regularization parameter of 0.1, and calculate the R^2 value.

Please refer to the Jupyter Notebook file for the complete code and execution of the solutions to the above questions.

## Author

Fahad Hossain
