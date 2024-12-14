# Supermarket-Sales-AnalysisProject Title: Supermarket Sales Data Analysis and Predictive Modeling
Overview
This project involves the exploratory data analysis (EDA) and predictive modeling of supermarket sales data. The primary objectives are:
1.	To perform in-depth EDA to uncover insights about customer behavior, product sales, and trends.
2.	To preprocess and prepare data for machine learning.
3.	To implement and evaluate multiple machine learning models for regression and classification tasks.
Key Features
•	Exploratory Data Analysis (EDA):
o	Visualizations of distributions, relationships, and correlations.
o	Analysis of categorical and numerical variables.
o	Insights into customer segmentation and rating patterns.
•	Data Preprocessing:
o	Handling missing values and feature selection.
o	Log transformation of skewed columns.
o	One-hot encoding for categorical variables.
o	Data standardization for optimal model performance.
•	Predictive Modeling:
o	Linear Regression: For predicting numerical outcomes like ratings.
o	Logistic Regression: For binary classification of customer types.
o	Decision Tree and Random Forest Models: For improved classification accuracy.
o	Performance Metrics: Root Mean Square Error (RMSE), Confusion Matrices, Accuracy Scores, and Classification Reports.
Requirements
The following Python libraries are required to run the project:
•	pandas
•	numpy
•	matplotlib
•	seaborn
•	scikit-learn
•	xgboost
•	lightgbm
•	statsmodels
Install dependencies using:
bash
Copy code
pip install -r requirements.txt
Data Source
The dataset used is Supermarket Sales Data, including variables such as:
•	Branch, City, Customer Type, Gender
•	Product Line, Unit Price, Quantity, Tax, Total, Payment Method
•	Gross Income, Rating, etc.
Highlights of Analysis
1.	Visualizations:
o	Heatmaps for correlations.
o	Countplots and boxplots for categorical variables.
o	Histograms and scatterplots for numerical variables.
2.	Data Transformation:
o	Skewed data was log-transformed to normalize distributions.
o	Categorical columns were encoded using one-hot and label encoding.
3.	Machine Learning Models:
o	Regression models to predict numerical ratings.
o	Classification models to segment customers (e.g., "Normal" vs. "Member").
4.	Evaluation Metrics:
o	For Regression: RMSE and R-squared values.
o	For Classification: Confusion matrices, accuracy scores, and classification reports.
Usage
1.	Clone the repository:
bash
Copy code
git clone https://github.com/username/final-python-project.git
cd final-python-project
2.	Load the notebook file python_final_project.ipynb.
3.	Follow the instructions in the notebook to run EDA, preprocessing, and modeling.
Outputs
•	Visualizations for EDA.
•	Predictions for regression and classification tasks.
•	Model evaluation metrics displayed in tables and plots.
Future Work
•	Implement additional machine learning models such as XGBoost and LightGBM.
•	Conduct hyperparameter tuning for improved model performance.
•	Extend the analysis to include customer retention strategies.

