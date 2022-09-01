# Train, Test and Publish a Regression Model using Azure Machine Learning Platform

* Introduction

In this project, Azure Machine Learning (AML) studio is utilized for data pre-processing, and for subsequent training, evaluation, and deployment of a machine learning model as a web service for future predictions using Excel Online. The dataset which is used for this project is “Flight Delays Data”, a built-in dataset in AML studio. The built-in “Flight Delays Data” in AML studio consists of 2,719,418 rows (observations) and 14 columns (variables). A more detailed overview for this dataset is provided in Activity 2 of the attached project report (.docx).

* Data Pre-processing, Cleansing and Model Building

For this project, a machine learning model which is aimed to predict how many minutes a flight will be delayed or early is built (hence the dependent variable is ArrDelay column of the dataset). Since ArrDelay is a variable of continuous value, hence this is a regression problem and the machine learning model shall be based on regression algorithm. However, prior to training the model, some data pre-processing (eg. joining of 2 datasets, data cleansing, standardization for selected numerical variables etc.) and some data visualization (using the Execute R Script module in AML studio) shall be done. After completing the data-preprocessing and data visualization, a regression model can be built in AML studio.

* Deployment of the Trained Model

Finally, the trained model is published as a web service and can be shared with others, for which future predictions for ArrDelay based on other set of data can be readily made using Excel Online.

The following document is provided in this repository:
  1. DSE0322A-Lee Jack Shiang-Project.docx: Word document for the project report
