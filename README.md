# E-commerce-Linear-Regression-Project
This project focuses on analyzing and predicting the yearly amount spent by customers in an E-commerce business. The dataset used for this analysis is named 'Ecommerce Customers.csv', containing various features such as average session length, time spent on the app and website, length of membership, and the yearly amount spent by each customer.

## Tools and Libraries Used
1. Pandas: For data manipulation and analysis.
2. NumPy: For numerical computations and array operations.
3. Matplotlib: For data visualization, including histograms, scatter plots, and regression plots.
4. Seaborn: For enhanced data visualization and statistical plotting.
5. Scikit-learn: For implementing the linear regression model, splitting data into training and testing sets, and evaluating model performance metrics.

## Project Overview
1. Data Exploration:
Imported the dataset using Pandas.
Explored the dataset to understand its structure, including data types, null values, and summary statistics.

2. Data Visualization:
Utilized Matplotlib and Seaborn to create visualizations such as histograms, joint plots, pair plots, and heatmaps to explore data distributions and correlations.

3. Linear Regression Modeling:
Selected relevant features (independent variables) such as average session length, time on app and website, and length of membership.
Split the data into training and testing sets using Scikit-learn's train_test_split function.
Created a linear regression model using Scikit-learn's LinearRegression class and trained the model on the training data.

4. Model Evaluation:
Evaluated the model's performance using metrics such as mean absolute error (MAE), root mean squared error (RMSE), and R-squared (R2) score.
Visualized the predicted values vs. actual values using scatter plots and regression plots to assess the model's fit.

6. Predictions:
Tested the model by making predictions on new data inputs, demonstrating how the model can predict the yearly amount spent based on specific customer attributes.

## Conclusion
This project demonstrates how linear regression can be applied to predict customer behavior and inform business decisions in an E-commerce setting. It provides a comprehensive analysis of customer spending patterns and insights into factors influencing purchase decisions.
