# Blood Spectroscopy Classification Challenge
 
**Members:** Apoorva Surendra Malemath, Vaidehi Pareshkumar Parikh

## Abstract

The challenge is hosted by bloods.ai. They are a team of ambitious, innovative professionals who are passionate about offering a better way to get in touch with and care for our bodies - all with the simple scan of skin. This challenge focuses on helping scientists from bloods.ai to make progress towards non-invasive blood analyses. The idea behind this is to classify the level of specific chemical compounds in samples from their spectroscopic data.

## Data Description:
- Absorbance: There exists 170 columns labelled as absorbance0, absorbance1 and so on. This is an intensity spectrum of the target blood response to pointed light.
- Temperature: Temperature at the time of the measurement.
- Humidity: Humidity at the time of the measurement.
- Id: Unique identifier assigned to each measurement.
- Std: Standard deviation value.
- Hdl_cholesterol_human: The level of cholesterol high. Can be low, ok or high.
- Cholesterol_ldl_human: The level of cholesterol low. Can be low, ok or high.
- Hemoglobin(hgb)_human: The level of hemoglobin: Can be low, ok or high

## Data Preprocessing

Data preprocessing is an essential process because it has a direct impact on the project's success rate. Steps involved:
- Checking NA values
- Outlier Detection
- Normalization
- Sampling using SMOTE

## Feature Engineering

The dataset contains 170 Absorbance columns followed by the temperature and humidity. Feature elimination was crucial due to the high number of features. Techniques used:
- Recursive Feature Elimination (RFE)
- Principal Component Analysis (PCA)

## Models

Several models were explored for this multiclass classification challenge. Some of them include:
- Logistic Regression with L2 Regularization
- Random Forest Classifier
- Extra-Tree classifier
- CatBoost Classifier

## Conclusion and Future Scope

Several conclusions were drawn after applying methodologies to the blood spectroscopic dataset. In the future, ensemble models and neural networks with dropout layers will be explored.

## Project Workflow

![Blood Spectroscopy Classification Challenge Workflow](https://showme.redstarplugin.com/d/d:uHOG0TM9)

[View the flowchart in a new tab](https://showme.redstarplugin.com/d/d:uHOG0TM9)

