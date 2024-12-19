Overview of the Project

*****PREDICTIVE MODELING WITH LINEAR REGRESSION*****

**Objective:**
Implement a simple linear regression model using a dataset with continuous target variables. Split the data into training and testing sets, train the model on
the training data, evaluate its performance using metrics like mean squared error or R-squared, and make predictions on the test set. Visualize the
regression line and actual vs. predicted values to assess the model's accuracy.

**Key features**

1.Data Loading and Inspection:

Loaded the dataset containing information on heart disease.
Inspected the data to understand its structure and identify relevant features.

2.Data Preprocessing:

Selected the age column as the predictor (feature) and the chol column as the target variable.
Handled missing values by dropping rows with any missing values in the selected columns.

3.Data Splitting:

Split the data into training and testing sets (80% training and 20% testing).

4.Model Training:

Trained a simple linear regression model using the training data.

5.Model Evaluation:

Made predictions on the test set.
Evaluated the model using Mean Squared Error (MSE) and R-squared (R²) metrics to assess performance.

6.Visualization:

Visualized the regression line to understand the relationship between age and chol.
Compared actual vs. predicted values to assess the model's accuracy.

**Technologies Used:**
1.Python: The primary programming language used for this task.
2.Pandas: For data loading, preprocessing, and manipulation.
3.NumPy: For numerical operations.
4.Scikit-learn (sklearn):
   train_test_split: To split the dataset into training and testing sets.
   LinearRegression: To create and train the linear regression model.
   mean_squared_error and r2_score: For model evaluation metrics.
5.Matplotlib: For creating visualizations of the regression line and actual vs. predicted values.
