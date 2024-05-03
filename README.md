Boston Housing Dataset Analysis and Linear Regression
Overview
This repository contains Python code for analyzing the Boston Housing Dataset using statistical methods and building a linear regression model to predict house prices. The dataset is loaded from a CSV file (housing.csv) and includes various features such as crime rate, average number of rooms, and property tax rate, along with the target variable, median house price.

Features
Data Loading: The dataset is loaded from the provided CSV file using pandas.
Data Exploration: Exploratory data analysis (EDA) techniques are employed to understand the dataset's characteristics, including summary statistics, visualization of feature distributions, and correlation analysis.
Linear Regression Modeling: A linear regression model is trained using scikit-learn to predict house prices based on the dataset's features.
Model Evaluation: The trained model's performance is evaluated using root mean squared error (RMSE) on both training and testing datasets.
Ethical Considerations
Note: The use of the Boston Housing Dataset has ethical concerns due to the engineered variable "B" and the dataset's origin. This repository aims to demonstrate data analysis techniques while raising awareness of ethical issues in data science and machine learning.
Usage
Clone the repository: git clone https://github.com/aditsinsinwal/Boston_housing_price_estimator.git
Install the required dependencies: pip install -r requirements.txt

References
Dataset Source: Kaggle - Boston Housing Dataset
Ethical Concerns: Medium - Racist Data Destruction?
Original Research Paper: Harrison Jr, David, and Daniel L. Rubinfeld. "Hedonic housing prices and the demand for clean air." Journal of environmental economics and management 5.1 (1978): 81-102.
