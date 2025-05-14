# README: Customer Churn Prediction Project

## Overview
This project focuses on predicting customer churn for a telecommunications company. By identifying customers likely to leave, the company can implement strategies to retain them, thus enhancing customer satisfaction and profitability.

## Business and Data Understanding
### Stakeholder
The primary stakeholder for this project is a telecommunications company that aims to reduce customer churn. Understanding which customers are at risk of leaving is crucial for developing effective retention strategies.

### Dataset Choice
The dataset used in this analysis includes various features related to customer accounts, such as account length, service plans, usage behavior, and previous interactions with customer service. This information is key for predicting churn.

## Modeling
The analysis involved building classification models to predict whether a customer would churn. Two types of models were developed:
1. **Logistic Regression**: A simple model to establish a baseline for performance.
![image](https://github.com/user-attachments/assets/7973761d-2914-419d-933c-d58625d1f3c3)

2. **Decision Tree**: A more complex model with better accuracy and interpretability.
   
 **Decision Tree (Baseline)**
![image](https://github.com/user-attachments/assets/31012479-2fde-4b1b-9b31-e83f8fbd624e)

4. **Decision Tree (Tuned)**
![image](https://github.com/user-attachments/assets/017c0384-a2d9-4ecd-9c7f-01f57e55ec89)

## Evaluation
Model performance was evaluated using several metrics:
- **Accuracy**: The percentage of correct predictions the model makes.
- **Precision**: The proportion of true positive predictions with all positive predictions made.
- **Recall**: The ability of the model to identify all relevant cases (actual churners).
- **F1-Score**: A balance between precision and recall.

The decision tree-tuned model outperformed the logistic regression model, indicating it was better at identifying customers likely to churn.

![image](https://github.com/MegAtaro/PHASE_3_PROJECT/blob/aa67bbcab61f1f2e12818099be3b5949e2f53eab/MODEL%20COMPARISON%20SUMMARY.PNG)

## Conclusion
The project successfully developed a predictive model for customer churn in the telecommunications sector. Key recommendations were made to help the company retain at-risk customers, such as targeted marketing campaigns and improved customer service .

## Links
- [Download Presentation](link_to_presentation)
- [Source Dataset](https://www.kaggle.com/becksddf/churn-in-telecoms-dataset)

## Navigation Instructions
To navigate this repository:
1. Clone or download the repository to your local machine.
2. Open the Jupyter Notebook file to view the analysis and code.
3. Refer to the presentation for a summary of findings and recommendations.

## Author
* Meggy Donna Ombwayo

