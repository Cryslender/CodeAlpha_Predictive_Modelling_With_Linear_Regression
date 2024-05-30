# CodeAlpha_Predictive_Modelling_With_Linear_Regression

## 1. Introduction
This project aimed to predict the selling price of cars. The following structured approach was used to achieve this objective.

## 2. Ask Question
The analytical process begins with a question to be answered. In this project, the central question is: "What is the car selling price?"

## 3. Get Data
This step involves locating and obtaining relevant data, followed by assessing if there is enough data to perform the analysis. For this project, car data were acquired from Kaggle.

## 4. Investigate Data
Data can come in various forms and from multiple sources. This step involves assessing if the data is complete and contains the necessary information for analysis.

## 5. Prepare Data
This phase, also known as "data cleaning," involves transforming the data into a suitable format for analysis. This includes rectifying issues such as missing values and obvious errors to ensure the data is ready for analysis. In this project, the following steps were taken:

* Checked the shape of the data to understand the number of columns and rows.
*Verified column names to ensure the data was suitable for answering the project question.
* Verified column data types to ensure correctness.
* Checked for null values and none were found.
* Checked for duplicates and 2 were found and deleted.
* Identified the unique values in the dataset.
* Obtained data information to understand its structure and types.
* Generated a statistical summary to understand the distribution of numerical data.

## 6. Analyze Data
This step involves exploratory data analysis (EDA) to gain more insight from the data. Visualization tasks are used to uncover patterns, correlations, and relationships, allowing for a deeper understanding of the data.

## 7. Preprocessing
To predict the car selling price, the project applied an Label Encoder to convert categorical variables to numeric values suitable for machine learning. Furthermore, applied Standard Scaler to "Car_Name","Year","Selling_Price","Present_Price", and "Driven_kms" columns to mormalize the data be between 0 and 1. The training data was split into independent and dependent variables and further divided into training (80%) and validation (20%) sets.

## 9. Model Design
This step involves designing the structure of the model. A Linear Regression was used for this project.

## 10. Model Training
In this phase, the model was trained on the training dataset. 

## 11. Model Testing
The model was evaluated on the validation data, achieving an 85% accuracy rate..and then created a dumy new car data to predict the selling price 
