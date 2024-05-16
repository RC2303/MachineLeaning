# Predicting Titanic Passenger Survival Rate

## Introduction
The goal of this assignment is to create a machine learning model able to predict the survival rate of Titanic passengers. A provided dataset will be used to train a regression model able to achieve considerable accuracy in predicting heart failure. The main objective is to get familiar with the preliminary steps of any ML model training.

## Main Steps
- **Data loading**
- **Exploratory Data Analysis (EDA)** (data visualization and analysis)
- **Data transformation**
- **Data cleaning**
- **Feature engineering**
- **Model training**
- **Model Evaluation**

## Project Outputs

In this section, we present visualizations and results obtained from our analysis.

### Gender-wise Survival Distribution

![Gender-wise Survival Distribution](https://github.com/RC2303/MachineLeaning/blob/main/Images/1.png)

*Figure 1: Distribution of survival by gender. It can be observed that there were more female survivors compared to male survivors.*

### Best Model Selection using Grid Search

![Best Model Selection using Grid Search](https://github.com/RC2303/MachineLeaning/blob/main/Images/2.png)

*Figure 2: Grid search results for selecting the best model. The dataset bias towards women is considered in the model selection process.*

### Logistic Regression Model

#### Model Definition
Logistic regression is a statistical method used for binary classification tasks. It models the probability that an instance belongs to a particular class using the logistic function.

#### Model Evaluation
![Logistic Regression Model Evaluation](https://github.com/RC2303/MachineLeaning/blob/main/Images/3.png)
*Figure 3: Evaluation metrics for the logistic regression model.*

#### Conclusion
Based on the evaluation metrics shown in Figure 3, the logistic regression model demonstrates satisfactory performance in predicting Titanic passenger survival rates. However, further analysis is needed to assess its generalization capability on unseen data.

### Best Model Selection using Grid Search

#### Model Definition
The grid search technique is used to find the best hyperparameters for a given machine learning model by exhaustively searching through a specified parameter grid and evaluating model performance using cross-validation.

#### Model Selection
![Best Model Selection using Grid Search](https://github.com/RC2303/MachineLeaning/blob/main/Images/4.png)
*Figure 4: Results of grid search for selecting the best model.*

#### Conclusion
Based on the results of the grid search shown in Figure 4, the best model selected considering the bias towards women in the dataset is [insert name of the selected model]. This model demonstrates promising performance and is recommended for further deployment.
