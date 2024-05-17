# Predicting Titanic Passenger Survival Rate
The goal of this assignment is to create a machine learning model able to predict the survival rate of Titanic passengers. A provided dataset will be used to train a regression model able to achieve considerable accuracy in predicting heart failure. The main objective is to get familiar with the preliminary steps of any ML model training.

## Main Steps
- **Data loading**
- **Exploratory Data Analysis (EDA)** 
- **Data transformation**
- **Data cleaning**
- **Feature engineering**
- **Model training**
- **Model Evaluation**

## Analysis

In this section, there is present the visualizations and results obtained from the analysis:

### Gender-wise Survival Distribution

![Gender-wise Survival Distribution](https://github.com/RC2303/MachineLeaning/blob/main/Images/1.png)

*Figure 1: Distribution of survival by gender. It can be observed that there were more female survivors compared to male survivors.*

### Model Training

### Logistic Regression Model

#### Model Definition
Logistic regression is a statistical method used for binary classification tasks. It models the probability that an instance belongs to a particular class using the logistic function.

#### Model Evaluation
Based on the evaluation metrics shown in Figure 2, the logistic regression model demonstrates satisfactory performance in predicting Titanic passenger survival rates. However, due to the bias towards female passengers in the dataset, further analysis was conducted to address this issue.

![Logistic Regression Model Evaluation](https://github.com/RC2303/MachineLeaning/blob/main/Images/3.png)

*Figure 2: Evaluation metrics for the logistic regression model.*


### Best Model Selection using Grid Search
The grid search technique is used to find the best hyperparameters for a given machine learning model by exhaustively searching through a specified parameter grid and evaluating model performance using cross-validation.

![Best Model Selection using Grid Search](https://github.com/RC2303/MachineLeaning/blob/main/Images/2.png)

*Figure 3: Grid search results for selecting the best model. The dataset bias towards women is considered in the model selection process.*

### Role of Random Forest in Bias Mitigation

The bias towards female passengers in the dataset presented a challenge in accurately predicting survival rates. To mitigate this bias and improve the model's performance, Random Forest was employed as a key solution.

Random Forest is well-suited for handling imbalanced datasets and biased data distributions. By constructing multiple decision trees and aggregating their predictions, Random Forest reduces the impact of data bias and improves the model's ability to generalize to unseen data.

#### Model Selection
![Best Model Selection using Grid Search](https://github.com/RC2303/MachineLeaning/blob/main/Images/4.png)

*Figure 4: Results of grid search for selecting the best model.*

### Conclusion

Upon analysis, it was discovered that the dataset exhibited a bias towards female passengers, potentially affecting the performance of the initial logistic regression model in predicting Titanic passenger survival rates. To mitigate this bias and enhance the model's robustness, Random Forest was introduced as a key solution.

Random Forest, with its ability to handle imbalanced datasets and biased data distributions, emerged as a crucial tool in addressing this issue. By constructing multiple decision trees and aggregating their predictions, Random Forest effectively reduced the impact of data bias and improved the model's generalization to unseen data.

Through the utilization of grid search, the best model was selected, considering the bias towards women in the dataset. The results of the grid search confirmed that the Random Forest model outperformed other models, demonstrating promising performance in mitigating bias and accurately predicting survival rates.

Hence, the deployment of the Random Forest model is recommended for its effectiveness in handling the dataset bias and its ability to provide accurate predictions of Titanic passenger survival rates.

