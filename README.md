# Absenteeism Prediction Project

## Introduction
This project focuses on predicting employee absenteeism from work using machine learning techniques. 
The goal is to develop a model that can predict both the likelihood of an employee being absent and the duration of their absence.

## Installation Instructions
To run this project, you will need the following dependencies:
- pymysql: [Installation instructions here](https://pypi.org/project/PyMySQL/)
- SQL Workbench: [Download and installation instructions here](https://www.sql-workbench.eu/downloads.html)
- Tableau: [Download and installation instructions here](https://www.tableau.com/)
- Jupyter Notebook: [Installation instructions here](https://jupyter.org/install)
- Python file: [Python Downloads](https://www.python.org/downloads/).
  
 ## Usage

- Imported the necessary libraries and classes into the Python file or Jupyter Notebook.

- Created an instance of the "absenteeism_model" class, providing the model and scaler files.

- Loaded and preprocessed the data using the "load_and_clean_data" method.

- Utilized the model's methods for making predictions and customizing as needed.

- Additionally, I created a logistic regression model:
   - Prepared the absenteeism dataset.
   - Split the dataset into training and testing sets.
   - Created and trained the logistic regression model.
   - Made predictions on the testing data.

## Results
Based on the analysis, the most critical factors for excessive absenteeism include:
- The reasons for absence, with poisoning being the top reason.
- Transportation expense.
- Having children and pets.
- Education.

Key insights:
- Poisoning is the primary reason for excessive absenteeism, followed by various diseases.
- Pregnancy and giving birth are also significant but to a lesser extent.
- Standardization improves accuracy but sacrifices interpretability.
- Consider both standardized and non-standardized models for a balanced understanding.
- The intercept adjusts predictions but lacks a specific meaning.

## Contact Information
For questions or feedback, please contact [fatema.sorna@gmail.com].

## Acknowledgments
I would like to acknowledge the Udemy course "Integrating Python, SQL, and Tableau" for providing valuable guidance 
and knowledge that contributed to the completion of this project.




