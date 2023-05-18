# Predicting Term Deposits - Classification Project

## Overview
Welcome to the "Predicting Term Deposits" project repository! This project demonstrates the implementation of classification algorithms, specifically Decision Trees and k-Nearest Neighbors (kNN), using R. The goal is to predict whether a customer will subscribe to a term deposit based on various features from a bank dataset.

## Data
The Bank Marketing dataset used in this project is sourced from the UCI Machine Learning Repository. It contains information about a bank's telemarketing campaigns and whether or not the clients subscribed to a term deposit. The dataset consists of 16 input variables and one binary output variable indicating the subscription status (0/1). It is commonly used for binary classification tasks in machine learning.

To access the dataset and learn more about its attributes, you can visit the following link:

https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

### Attribute information:

Here is the description of all the variables :

**Input variables:**
1. Variable: Definition
2. ID: Unique client ID
3. age: Age of the client
4. job: Type of job
5. marital: Marital status of the client
6. education: Education level
7. default: Credit in default.
8. housing: Housing loan
9. loan: Personal loan
10. contact: Type of communication
11. month: Contact month
12. day_of_week: Day of week of contact
13. duration: Contact duration
14. campaign: number of contacts performed during this campaign to the client
15. pdays: number of days that passed by after the client was last contacted
16. previous: number of contacts performed before this campaign
17. poutcome: outcome of the previous marketing campaign

**Output variable (desired target):**

18. y: has the client subscribed a term deposit? (binary: “yes”,“no”)
  

## Project Structure
The repository is organized into several sections:

1. Data: This section provides an overview of the dataset, including the input variables and the target variable. It describes the attributes and their meanings, helping you understand the data better.

2. Exploratory Data Analysis: Here, we explore the dataset, visualize key features, and uncover any interesting insights. Data preprocessing and cleaning steps are also explained, if performed.

3. Decision Tree Classification: This section focuses on the implementation of Decision Tree models. Two models are showcased: one using the unmodified dataset and another using the SMOTE technique for handling imbalanced data. The models are trained, evaluated, and the results are presented.

4. k-Nearest Neighbors (kNN) Classification: In this section, we cover the implementation of kNN models. It includes data preprocessing steps specific to kNN, followed by two models: one using the original dataset and another using SMOTE for imbalanced data handling. Model training, evaluation, and results are discussed.

5. Conclusion: The conclusion section provides a summary of the project, highlighting key findings and insights. It also suggests possible areas for future improvement or research.

The detailed project report can be found in the output folder. It is available in HTML format, providing comprehensive analysis, insights, and conclusions derived from the classification models.

## Usage
To run the code and reproduce the results, you need to have R installed on your machine along with the necessary libraries specified in the code. Make sure to set the working directory correctly and run the scripts in the provided order to ensure proper execution.


## Contributions
Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or submit a pull request. Let's collaborate and make this project even better!


## References
  [1] Kaggle Datasets
  
  [2] UCI Machine Learning Repository
