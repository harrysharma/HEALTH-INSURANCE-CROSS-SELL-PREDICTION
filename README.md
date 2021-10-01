# Insurance Cross-Sell Prediction
This project is a part of [AlmaBetter Premium Program](https://www.almabetter.com/), Banglore, Karnataka, India
- Project status [completed]

## Project Summary:
### Problem Statement:
The objective is to build a predictive model to prognosticate whether policy holder from past year  will additionally be intrigued with the Vehicle insurance provided by the company.
### About the Data:
The dataset consist data of policy holders having the feaures like- Age, Annual Premium, Driving License etc. We have target variable as 'Response' which is customer choice for vehicle insurance (yes/no).

##Approach Taken in This Project

* About this Project
* Problem Statement
* Bussiness Goal
* Approach Taken in this Project
  * Understanding the given Data

* Initial Code : Initliaing the Data and Modules
  * Installing and Importing Libraries
  * Import Dataset and Initial Data Checks

* Data Preparation and Cleaning
* Exploratory Data Analysis
  * Initial Macro-Level Data Analysis
  * Variable wise EDA
    * Target Variable (Response)
    * Age variable
    * Annual_Premium
    * Gender variable
    * Driving License
    * Previously Insured
    * Vehicle Age
    * Vechicle damage
    * Vintage
    * Region Code
    * Policy Sales Channel
  * Correlation Plot for Numeric Features
* Data Preprocessing and Feature Engineering
	* Outlier Treatment in feature : Annual_Premium
	* Label Encoding
	* Target Mean Encoding
	* Cleaned Data Exporting

* Building Prediction Systems using ML Models
	* Import cleaned final data
	* Classifier Performance Reporting Function
		* Overfitting Underfitting Debugging Notes
		* Metrics to be used during HyperParameter
		* Random Forrest Specific Cutom Defined Metrics
		* Function Definations for Analytics report generation

	* Logistic Regression Classifier Algorithm
		* LR Classifier Generator Function
		* LR Hyper Parameter Tuning : GridSearch
		* Final Logistic Regression Training run
	* K Nearest Neighbours Classifier Algorithm
		* Default Parameters : KNeighborsClassifier
		* KNN Model Generator Funciton
		* KNN Hyper Parameter Tuning : GridSearch
		* Final KNN Training run
	* Random Forrests of Decsision Trees
		* Default Parameters : RandomForestClassifier
		* Base Estimator Generator Function
		* HyperParameter tuning using GridSearchCV
		* Final Training Run
	* Gradient Boosted Trees using XGBoost Library
		* XGBoost algorithn training and tuning notes
		* XGBoost Estimator Instance Generator Function
		* HyperParameter tuning using BayesSearchCV
		* Final Training Run for XGBoost
		* Feature Importance
	* Categorical Gradient Boosted Trees using CatBoost Library
		* Cleaning Raw Data with Categorical Encoding
		* CatBoost Estimator Instance Generator Function
		* Model Evaluation
		* Final Training Run for CatBoost
		* Feature Importance

* Inferences and Conclusions
* What Worked? What Did Not Work?

### Target Variable :

- Response: Yes/No



### Python Libraries used
Datawrangling :

- Numpy
- Pandas
For Graphing :

- Matplotib
- Seaborn
Machine learning :

- Scikit-Learn
- SK-Opt
- XGBoost
- CatBoost

### Miscellaneous :

Jupiter/Google colab tools

### Contributing Team Members:
|Name	| Email |
|-----|---------|
|Hari Om Bharadwaj(https://github.com/harrysharma)|	herrysharma5050@gmail.com|
|Mayank Kumar|	mayankkumar77952@gmail.com|
|Shivam Mishra|	smmishra8298@gmail.com|
|Sarvesh Yadav	|skyttsearch@gmail.com|
|Saifuddin Raja(https://github.com/saif-raja)|	saifuddin.raja24@gmail.com|
