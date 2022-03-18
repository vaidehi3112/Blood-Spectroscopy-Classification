# Blood Spectroscopy Classification
DS 5220: Supervised Machine Learning and Learning Theory - Fall 2021

Problem Statement: 
Classify the blood cholesterol and hemoglobin levels in the blood as ok, high and low for each individual. 

Data Description:
Absorbance: There exists 170 columns labelled as absorbance0, absorbance1 and so on. This is an intensity spectrum of the target blood response to pointed light.
Temperature: Temperature at the time of the measurement.
Humidity: Humidity at the time of the measurement.
Id: Unique identifier assigned to each measurement.
Std: Standard deviation value.
Hdl_cholesterol_human: The level of cholesterol high. Can be low, ok or high.
Cholesterol_ldl_human: The level of cholesterol low. Can be low, ok or high.
Hemoglobin(hgb)_human: The level of hemoglobin: Can be low, ok or high

The project code consists of the following modules:

1) Feature Engineering
We provide the functions to perform the folloing operations:
- Outlier Detection and Removal for all features.
- Outlier Detection and Removal for specific features.
- SMOTE Sampling.
- Dimenssionality Reduction Techniques:
  a. Recursive Feature Elimination
  b. Recursive Feature Elimination Cross Validation
  c. Principle Component Analysis
  
2) Models:
We provide the functions to fit the following models:
- Random Forest Multioutput Classifer
- Random Forest Classifier for each target
- Random Forest Classifier for each target with grid search
- Extra Trees Classifier Each Target with Grid Search
- Gradient Boosting Classifier for each target with Grid Search
- Logistic Regression with L2 Regularisation for each target
- CatBoost with Grid Search for each target
- Radius Neighbors Classifier with Grid Search for each target

4) Metrics:
Defines function to calculate evaluation metrics - F1-Score, Precision and Re-call.

5) GenerateOutput
Defines functions to merge output obtained individually for each of the target variables and merge to generate the output in required submission format. 

6) Main:
- Imports all the other modules.
- Shows Exploratory Data Analysis for the data. 
- Train-test split.
- Comprises of function calls to all the above mentioned feature engineering and models techniques. 

Steps to run the code:
-> Run the cells of Main.ipynb 

