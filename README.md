Cab Fare Prediction
This project aims to build a machine learning model to predict the fare amount for taxi rides in New York City based on factors like distance, pickup and drop-off location, and time of travel.

📋 Project Overview
Goal: Predict the taxi fare amount given pickup and drop-off information.

Dataset: NYC Taxi Fare Prediction dataset.

Tech Stack:

Python

Pandas, NumPy

Seaborn, Matplotlib

Scikit-learn (sklearn)

🔥 Key Steps Performed
Data Cleaning:

Removed missing values.

Handled outliers in fare_amount and distance.

Filtered invalid latitude and longitude values.

Feature Engineering:

Extracted useful time-based features (e.g., hour, day of the week).

Calculated distance between pickup and drop-off using Haversine formula.

Applied log transformation to normalize skewed features (fare_amount, distance).

Exploratory Data Analysis (EDA):

Visualized the distributions of key features.

Checked correlations between variables.

Model Building:

Built regression models to predict cab fare.

Tried different algorithms (Linear Regression, Decision Tree, Random Forest, etc.).

Tuned hyperparameters for better model performance.

Evaluation:

Used metrics like RMSE (Root Mean Squared Error) and R² Score.

Compared different models to select the best one.
