# PRODIGY_DS_03

# Customer Purchase Prediction using Decision Tree Classifier
### Project Overview
This project aims to build a predictive model using a Decision Tree Classifier to determine whether a customer will purchase a product or service based on demographic and behavioral data. The dataset includes various features related to customer characteristics and previous interactions, enabling the model to learn and make predictions.

### Dataset
The dataset used for this project consists of customer demographic and behavioral data. It includes features such as age, job, marital status, education, account balance, and past marketing campaign results. The target variable indicates whether a customer made a purchase.

### Features
| Variable Name | Type        | Description                                          |
|---------------|-------------|------------------------------------------------------|
| age           | Integer     | Age of the customer                                   |
| job           | Categorical | Occupation type (e.g., admin, blue-collar, etc.)    |
| marital       | Categorical | Marital status (e.g., married, single, etc.)        |
| education     | Categorical | Education level (e.g., high school, university, etc.)|
| default       | Binary      | Has credit in default? (Yes/No)                      |
| balance       | Integer     | Average yearly balance in euros                       |
| housing       | Binary      | Has a housing loan? (Yes/No)                         |
| loan          | Binary      | Has a personal loan? (Yes/No)                        |
| contact       | Categorical | Contact communication type (e.g., cellular, telephone)|
| day           | Integer     | Last contact day of the month                        |
| month         | Categorical | Last contact month                                   |
| duration      | Integer     | Duration of the last contact in seconds               |
| campaign      | Integer     | Number of contacts performed during this campaign     |
| previous      | Integer     | Number of contacts performed before this campaign     |
| poutcome      | Categorical | Outcome of the previous marketing campaign            |
| y             | Binary      | Target variable (Purchased: Yes/No)                  |


### Modeling
A Decision Tree Classifier was implemented using the following steps:

Data Preprocessing: Data was cleaned and transformed to prepare it for modeling.
Train-Test Split: The dataset was split into training (70%) and testing (30%) sets.
Model Training: The Decision Tree Classifier was trained on the training set.
Model Evaluation: The model was evaluated using accuracy, precision, recall, F1-score, and support metrics.
Results
Accuracy: 86%
Precision:
Class 0 (Did Not Purchase): 92%
Class 1 (Purchased): 38%
Recall:
Class 0: 92%
Class 1: 39%
F1-Score:
Class 0: 92%
Class 1: 39%

### Conclusion
The model demonstrates strong performance in identifying non-purchasers but faces challenges in accurately predicting purchasers. Further improvements can be made through hyperparameter tuning and exploring other modeling techniques.

### Installation
To run this project, you'll need to have Python and the following libraries installed:

pandas
numpy
scikit-learn
matplotlib (for any visualizations)
