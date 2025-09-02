# Car Evaluation Classification

This project focuses on building and evaluating classification models to predict car evaluations based on various attributes. The goal is to determine the acceptability of a car based on its features.

## Dataset

The dataset used in this project is the Car Evaluation Data Set. It contains 1728 instances and 7 attributes:

*   `buying`: buying price
*   `maint`: maintenance cost
*   `doors`: number of doors
*   `persons`: capacity in terms of persons to carry
*   `lug_boot`: size of luggage boot
*   `safety`: estimated safety of the car
*   `class`: car acceptability (target variable)

The target variable 'class' has four categories: unacc (unacceptable), acc (acceptable), good, and vgood (very good).

## Project Structure

The project includes the following steps:

1.  **Data Loading and Exploration:** Loading the dataset and performing initial exploratory data analysis (EDA) to understand the data distribution and characteristics.
2.  **Data Preprocessing:** Handling categorical variables using Label Encoding and scaling numerical features using StandardScaler.
3.  **Model Training:** Training three classification models: Decision Tree, Random Forest, and AdaBoost.
4.  **Model Evaluation:** Evaluating the performance of each model using metrics such as accuracy, confusion matrix, and classification report.
5.  **Feature Importance Analysis:** Identifying the most important features for predicting car evaluation using the Random Forest model.

## Models Used

*   Decision Tree Classifier
*   Random Forest Classifier
*   AdaBoost Classifier

## Results

The models were evaluated based on their testing accuracy. The results are as follows:

| Model           | Training Accuracy | Testing Accuracy |
| :-------------- | :---------------- | :--------------- |
| Decision Tree   | 98.55%            | 97.40%           |
| Random Forest   | 100.00%           | 97.98%           |
| AdaBoost        | 84.59%            | 85.26%           |

The Random Forest model achieved the highest testing accuracy.

## Feature Importances

According to the Random Forest model, the most important features for predicting car evaluation in decreasing order are:

1.  Safety
2.  Persons
3.  Buying Price
4.  Maintenance Cost
5.  Luggage Boot Size
6.  Doors

Thank you 🙌
