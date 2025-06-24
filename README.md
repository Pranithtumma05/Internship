# Task-1

Task 1: Data Cleaning & Preprocessing


 Objective: Learn how to clean and prepare raw data for ML.
 Tools: Python, Pandas, NumPy, Matplotlib/Seaborn



Steps to be followed :
	
1.Import the dataset and explore basic info (nulls, data types).

	We'll load the Titanic.csv dataset and perform an initial 
	exploration to understand its structure, identify missing 
	values, and check data types.

 2.Handle missing values using mean/median/imputation.

	We will impute the missing values based on the column's characteristics.
	Age: This is a numerical column. We can fill the missing values with the median age. 
	The median is more robust to outliers than the mean.
	Cabin: This column is missing over 77% of its data. Imputing this many values would
	add noise. It's best to drop this column.
	Embarked: This is a categorical column with only 2 missing values. We can fill them 
	with the mode (the most frequent value).
	


 	3.Convert categorical features into numerical using encoding.
 	4.Normalize/standardize the numerical features.
 	5.Visualize outliers using boxplots and remove them.
