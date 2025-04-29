# TASK--3-ELEVATE-LABS
This project demonstrates a simple Linear Regression workflow using Python and scikit-learn. It covers importing and preprocessing data, training a model, evaluating its performance, and visualizing results.

📂 Steps Followed:
1. Import and Preprocess the Dataset
Loaded the dataset using pandas.
Handled missing values and ensured proper data formatting.
Selected appropriate feature(s) and target variable for modeling.

2. Split Data into Train-Test Sets
Used train_test_split from sklearn.model_selection.
Split the data into 80% training and 20% testing to validate the model's generalization ability.

3. Fit a Linear Regression Model
Imported LinearRegression from sklearn.linear_model.
Trained the model on the training set using the .fit() method.
Retrieved the model coefficients (slope and intercept) for interpretation.

4. Evaluate the Model
Evaluated the model's performance on the test set using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score (Coefficient of Determination)
These metrics helped assess how accurately the model predicts unseen data.

5. Plot the Regression Line
Created a scatter plot of the data points.
Plotted the regression line showing the relationship between the feature and the target.
Visualized how well the model fits the data and discussed the meaning of the coefficients.
