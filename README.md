# Insurance Premium Amount Prediction
A machine Learning project aimed at predicting the Insurance Premium Amount from given key features such as Annual Income, Education Level, Occupation, Credit Score,etc.

## Table of contents
+ Project Overview
+ Installation
+ Usage 
+ files

### Project Overview
The project was done for submission in the Kaggle Regression With an Insurance Dataset Playground Competition - Season 4, episode 12. The objectives of this challenge is to predict amount of insurance premiums given various features. The evaluation metric the competition body required was Root Mean Squared Logarithmic Error (RMSLE).
The steps taking in creating the model:

- **Exploratory Data Analysis**: Which involves going through the data, it's columns and it's rows checking for missing data, correlation, relationships and patterns
- **Filling Missing Data**: This is a crucial part of the model creation purpose, Models cannot thoroughly learn from Nan values. The method of filling is crucial.
- **Converting categorical data into Numerical form and encoding them**: As the intro says,this section involves converting all categorical and all object dtypes into Numerical dtypes. This is crucial as Machine learning Models only learn from Numerical data.
- **Modelling**: This section involving applying machine learning models to our already clean datase. In this project Xgboost Regressor and Ensemble's Random Forest Regressor were both evaluated and tuned to find which found more pattern and learned better on the data. Xgboost learned better and produced a better RMSLE score of `1.05770`.

### Installation
1. **Clone The Repository**
	```bash
	git clone https://github.com/Darc-lord/Insurance-Premium-Amount-Prediction.git
	cd Insurance-Premium-Amount
	```

2. **Download Dataset**
	```bash
	 https://www.kaggle.com/competitions/playground-series-s4e12/data
	```	

## Acknoledgements
+ Kaggle
+ Playground Series
+ Scikit-learn

