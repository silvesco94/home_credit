# home_credit
# Overview
This project, titled "Capstone Model," is designed to predict credit default risk using various machine learning models. The analysis is based on the Home Credit dataset, which includes a comprehensive range of attributes about loan applicants. This project involves extensive data cleaning, feature engineering, and model evaluation to understand and predict credit default risks effectively.

# Objective
The primary objective of this project is to utilize financial and personal data from loan applicants to predict their likelihood of defaulting on a loan. The project aims to enhance loan decision processes by identifying risk factors and predicting outcomes based on comprehensive data analysis.

# Data
The dataset used in this project includes the following files:

application_train.csv: Training data with details on each loan application.
application_test.csv: Test data for model validation.
Project Structure
#Data Cleaning: Initial handling of missing values, encoding categorical variables, and normalization of numerical data.
#Feature Engineering: Creation of new variables to improve model performance.
#Model Development: Training of several models including decision trees, logistic regression, and polynomial models.
#Evaluation: Assessment of model performance using ROC-AUC and other relevant metrics.
#Installation and Usage
## Dependencies
This project requires R and the following R packages:

caret
tidyverse
rpart
ggplot2
skimr
mice
ROSE
rpart.plot
rminer
ModelMetrics
RWeka
pROC
cluster
To install the necessary R packages, run the following command:

R
Copy code
install.packages(c("caret", "tidyverse", "rpart", "ggplot2", "skimr", "mice", "ROSE", "rpart.plot", "rminer", "ModelMetrics", "RWeka", "pROC", "cluster"))
Scripts and Execution
Data Loading and Cleaning:
R
Copy code
application_train <- read.csv('application_train.csv')
application_test <- read.csv('application_test.csv')
# Follow the steps in the R script to clean and preprocess the data.
Model Training:
R
Copy code
# Load and run the model training scripts provided in the project files.
# Each script corresponds to a different modeling approach as detailed in the project report.
Model Evaluation:
R
Copy code
# Evaluate the models using the scripts that generate performance metrics.
Contributing
Contributions to this project are welcome. Please fork the repository and submit pull requests to the develop branch.
