# **Ford Car Price Prediction Model**


 ## **Project Overview**


This project aims to predict the optimum quotation price for Ford cars in a used car dealership, based on historical sales data provided by the client. The data contains various features of the cars and their corresponding prices, and the goal is to create a model that accurately predicts the price of cars based on those features.

The project involves several key tasks, including **data cleaning, exploratory data analysis (EDA), model development, and optimization using advanced techniques like Grid Search**.


## **Key Tasks**

**Data Preparation:**

Clean the dataset by addressing missing values and removing duplicate entries.


**Exploratory Data Analysis (EDA):**

Analyze the data to draw insights and understand the relationship between features and the target variable (price).

**Specific tasks  include:**

Identifying the number of sales for each fuel type.

Identifying which transmission type has more price outliers.

Visualizing correlations between features and price.

**Model Development:**

Compare different models including linear regression, polynomial regression, and Ridge regression (both on single and multiple variables).

Fit and evaluate the models based on their performance, using metrics like R² and Mean Squared Error (MSE).

**Model Refinement with Grid Search:**

Perform Grid Search on the Ridge regression model to identify the optimal hyperparameter (alpha) for the best model performance.

Use cross-validation to ensure the model generalizes well to unseen data.

**Generative AI Assistance:**

Use Generative AI to help automate the creation of Python codes for data analysis, feature selection, and model development .

## **Dataset**

The dataset contains historical sales data of Ford cars with the following features:

**year:** Year of manufacture.

**mileage:** Total mileage of the car.

**tax:** Tax value of the car.

**mpg:** Miles per gallon (fuel efficiency).

**engineSize:** Size of the engine.

**fuelType:** Type of fuel used (e.g., Petrol, Diesel, etc.).

**transmission:** Type of transmission (e.g., Manual, Automatic, Semi-Auto).

**price:** Selling price of the car (target attribute).


**Dataset on kaggle:** https://www.kaggle.com/datasets/adhurimquku/ford-car-price-prediction


# **Results**

**Exploratory Data Analysis (EDA)** revealed insights into how fuel type, transmission type, and other features affect the car price.

**Multiple regression models (Linear, Polynomial, and Ridge)** were tested and compared, with Ridge regression showing the best performance.

**Grid Search** helped identify the optimal regularization parameter (alpha) for the Ridge regression model, improving its accuracy.
