# CodeAlpha_Predictive_Modelling_With_Linear_Regression

## 1. Introduction
This project aims to predict the selling price of cars using a structured approach involving data analysis, preprocessing, and machine learning techniques.

## 2. Ask Question
The analytical process begins with a central question: "What is the car selling price?"

## 3. Get Data
Relevant car data were obtained from Kaggle to ensure there was enough information to perform the analysis.

## 4. Investigate Data
This step involved assessing the data's completeness and relevance to the analysis.

## 5. Prepare Data
Also known as "data cleaning," this phase involved transforming the data into a suitable format for analysis. The following steps were taken:

* Checked the shape of the data to understand the number of columns and rows.
* Verified column names to ensure the data was suitable for answering the project question.
* Verified column data types to ensure correctness.
* Checked for null values and found none.
* Checked for duplicates, found 2, and deleted them.
* Identified unique values in the dataset.
* Obtained data information to understand its structure and types.
* Generated a statistical summary to understand the distribution of numerical data.

## 6. Analyze Data
Exploratory data analysis (EDA) was conducted to gain deeper insights. Visualization tasks were used to uncover patterns, correlations, and relationships within the data.

## 7. Preprocessing
To predict the car selling price, the following preprocessing steps were applied:

Label Encoding was used to convert categorical variables to numeric values suitable for machine learning.
Standard Scaler was applied to the "Car_Name," "Year," "Selling_Price," "Present_Price," and "Driven_kms" columns to normalize the data between 0 and 1.
The data was split into independent and dependent variables and further divided into training (80%) and validation (20%) sets.
## 8. Model Design
A Linear Regression model was designed for this project.

## 9. Model Training
The model was trained on the training dataset.

## 10. Model Testing
The model was evaluated on the validation data, achieving an 85% accuracy rate. A dummy new car data was then created to predict the selling price.
