![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)
# Mid-term Project: Modeling on wine quality data
Authors: Inga Eichhorn & Nelson Lage

This project was developed for the Data Analytics Course on Ironhack (Berlin campus - Oct2021 Full-time)

**Objective**:

Find a model that predicts the wine quality based on its physicochemical properties.

**Data**:
Source: [Wine quality dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality) 

Two datasets are included, related to red (1599 entries) and white wine (4898 entries) samples from the demarcated region of *vinho verde* (northeast region of Portugal).

Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol

Output variable (based on sensory data):
12 - quality (score between 0 and 10)



**Brief description of the work procedure**:

1. Exploratory data analysis (EDA)
 - Check for outliers
 - Check the data types
 - Check if the values are consistent
 - Check for normality
 - Find correlations

2. Data cleaning
 - Standardize text data
 - Deal with missing values

3. Data transformation
 - Bucketing
 - Standardize the values
 - X/Y split
 - Encode categorical features

4. Modeling
 - Test the model
 - Improve the model based on the values of accuracy

5. Vizualisation
 - Scatter plots to check for correlations
 - Box-plots for outliers
 - Histograms to check how the values are distributed
 - Vizualisation of the regression plot / model
 - Highlight some other interesting patterns in the data
