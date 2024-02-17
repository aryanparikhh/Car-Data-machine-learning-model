# Car-Data-machine-learning-model

The provided Python code utilizes a Random Forest Regressor to predict car selling prices based on various features. Here's a summary of the code:

Import Libraries:

The necessary libraries are imported, including Pandas for data manipulation, train_test_split for data splitting, RandomForestRegressor for modeling, and metrics such as mean_squared_error and r2_score for evaluation.
Load and Explore Dataset:

The car dataset is loaded from the specified path, and the first few rows are displayed to understand its structure.
info() is used to explore the dataset, including data types and missing values.
Select Features and Target Variable:

Relevant features ('Year', 'Present_Price', 'Driven_kms', 'Fuel_Type', 'Selling_type', 'Transmission', 'Owner') and the target variable ('Selling_Price') are selected.
Data Preprocessing:

Categorical variables are converted into dummy/indicator variables using pd.get_dummies().
Data Splitting:

The dataset is split into training and testing sets (80% training, 20% testing) using train_test_split.
Model Training:

A Random Forest Regressor model is instantiated with 100 estimators and then trained on the training set.
Prediction and Evaluation:

The model is used to make predictions on the test set.
Mean Squared Error (mse) and R-squared Score (r2) are calculated to evaluate the model's performance.
Visualization:

A scatter plot is created to visualize the predicted selling prices against the actual selling prices in the test set.
In summary, this code demonstrates the application of a Random Forest Regressor for predicting car selling prices, including data loading, exploration, preprocessing, model training, evaluation, and visualization. The chosen evaluation metrics provide insights into the model's accuracy and performance.
