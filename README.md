# Train, Test and Publish a Regression Model using Azure Machine Learning Platform

## Project Overview

In this project, Azure Machine Learning (AML) studio is utilized for data pre-processing, and for subsequent training, evaluation, and deployment of a machine learning model as a web service for future predictions using Excel Online. The dataset which is used for this project is “Flight Delays Data”, a built-in dataset in AML studio. The built-in “Flight Delays Data” in AML studio consists of 2,719,418 rows (observations) and 14 columns (variables). A more detailed overview for this dataset is provided in Activity 2 of the attached project report (DSE0322A-Lee Jack Shiang-Project.docx).

For this project, a machine learning model which is aimed to predict how many minutes a flight will be delayed or early is built (hence the dependent variable is ArrDelay column of the dataset). Since ArrDelay is a variable of continuous value, hence this is a regression problem, and the machine learning model shall be based on regression algorithm. Subsequently, the trained model is published as a web service and can be shared with others, for which future predictions for ArrDelay based on other set of data can be readily made using Excel Online.

## Objectives of the Project
The following are the objectives of the project:
1.	Create a machine learning model in AML for predicting how many minutes a flight will be delayed or early.
2.	Deploy the trained model in AML as a web service and predictions for new data can be readily made using Excel Online.

## Project Outline
To start building the model in AML, the built-in “Flight Delays Data” is first loaded into the AML experiment file. Prior to training the model, some data pre-processing (eg. joining of 2 datasets, data cleansing, standardization for selected numerical variables etc.) and some data visualization (using the Execute R Script module in AML studio) shall be done.
After completing the data-preprocessing and data visualization, a regression model can be built in AML studio. Boosted decision tree regression is selected for the model, and 70% of the dataset is used for training, and the remaining 30% is used for testing. The model is evaluated based on both train and test data since for a good model, its accuracy shall be as high as possible and performance between train and test data shall be as close as possible. Finally, the trained model is published as a web service and can be shared with others, for which future predictions for ArrDelay based on other dataset can be readily made using Excel Online.

Note: The regression model obtained at the end of this project can be further improved using techniques for improving model from further module and it is provided in another repository named “Prediction of Regression Model using Azure Machine Learning Platform”.

The following document is provided in this repository:
  1. DSE0322A-Lee Jack Shiang-Project.docx: Word document for the project report
