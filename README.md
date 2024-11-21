#Documentation for Iris Dataset & Linear Regression Code


#Introduction

This code is a Python-based project that demonstrates data exploration using the Iris dataset and the application of linear regression on a mock dataset. 
It covers basic steps in data science and machine learning, 
including loading data, splitting data into training and testing sets, and evaluating model performance.

#Code Structure
1.Importing Libraries

The code begins by importing necessary Python libraries, including:

-pandas: For data manipulation.
-sklearn.datasets: To load the Iris dataset.
sklearn.model_selection: For splitting data into training and testing sets.
sklearn.linear_model: To create and train a linear regression model.
sklearn.metrics: To evaluate model performance.
numpy: For numerical operations, such as generating random data.
Dataset Exploration
The Iris dataset is loaded and converted into a Pandas DataFrame. Key operations include:

Displaying the first 5 rows of the dataset.
Checking the shape of the dataset (number of rows and columns).
Generating summary statistics (mean, standard deviation, etc.).
Data Splitting
The code selects the first two features of the Iris dataset for simplicity and splits the data into training and testing sets. This prepares the data for model training.

Mock Dataset Generation
A mock dataset is generated to simulate a linear r
