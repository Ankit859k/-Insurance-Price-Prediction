🏥 Insurance-Price-Prediction
This project focuses on building a Machine Learning model to predict medical insurance charges based on customer demographic and health-related attributes. The complete workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling.


📊 Project Overview

Medical insurance costs vary significantly depending on factors such as age, BMI, smoking habits, and region. The objective of this project is to analyze these patterns and develop a regression model that can accurately estimate insurance charges for new individuals.

🔎 Exploratory Data Analysis (EDA)

Comprehensive EDA was performed to understand data distributions and relationships:
Checked missing values and data types
Univariate analysis (age, BMI, children, charges)
Categorical analysis (sex, smoker, region)
Correlation analysis to identify key predictors
Visualizations to detect trends and outliers
Key insight: Smoking status and BMI show strong influence on insurance charges.

⚙️ Feature Engineering

Categorical variables encoded using one-hot encoding
BMI grouped into health categories
Irrelevant or redundant features removed
Features scaled where necessary

🤖 Model Building

Multiple regression models were tested to achieve optimal performance:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Models were evaluated using:
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
The final model provides reliable predictions and demonstrates how healthcare costs can be estimated using data-driven methods.

🛠 Tech Stack

Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn


