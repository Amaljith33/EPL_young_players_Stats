# From Scouting to Science: Comparing Models for Under-25 Player Performance Prediction
This project aims to predict the performance of football players under 25 years old using various machine learning models, including Support Vector Regression (SVR), Random Forest, XGBoost, and custom neural networks. The analysis is based on historical performance data, including metrics such as goals, assists, passing accuracy, and defensive actions.

# Purpose
The purpose of this code is to preprocess the data, engineer features, train machine learning models, and evaluate their performance in predicting player metrics. It is intended to assist in player development, team strategy, and scouting by providing data-driven insights into player performance.

# Input Data
The code processes data from multiple Excel files containing various football metrics:

Standards.xlsx: Standard player statistics.
AdvGk.xlsx: Advanced goalkeeper metrics.
Def Action.xlsx: Defensive actions.
Gk.xlsx: Basic goalkeeper metrics.
Miscellaneous.xlsx: Miscellaneous player stats.
Passing.xlsx: Passing accuracy and attempts.
Possession.xlsx: Possession metrics.
Shooting.xlsx: Shooting accuracy and attempts.
Output
The output of the code includes predictions of player performance metrics such as goals per 90 minutes, assists, shot accuracy, and more. The results are saved into Excel files for both outfield players and goalkeepers.

# Parameters in Defined Functions

## Preprocessing Functions:

numeric_columns: List of columns that are coerced to numeric type for consistent data processing.
GK_U25_selected: Data cleaning by removing duplicated columns and filling missing values.

## Model Training:

Uses hyperparameter tuning (e.g., GridSearchCV, RandomizedSearchCV) for models like Random Forest and XGBoost.
Neural networks are defined with specific layers, activation functions, dropout rates, and compiled with the Adam optimizer.
Evaluation:

Models are evaluated using Mean Absolute Error (MAE) and R-squared (R²) to determine the accuracy and predictive capability.
## How to Use
Data Preparation: Ensure all Excel files are available and correctly formatted.
Run the Script: Execute the script to preprocess data, train models, and generate predictions.
Evaluate Results: Review the output Excel files for predicted performance metrics.
For detailed instructions on running the script and additional functionalities, please refer to the comments within the code.
