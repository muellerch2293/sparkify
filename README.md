# Sparkify - Udacity DATA SCIENTIST CAPSTONE 
## Overview and Motivation

In this project the user data of a ficitional music streaming app called Sparkify was used to develop ML models that predict the customer churn of sparkify.

According to https://www.qualtrics.com/uk/experience-management/customer/customer-churn/ Customer Churn is defined as follows:
"Customer churn, also known as customer attrition, is when someone chooses to stop using your products or services. In effect, it's when a customer ceases to be a customer. "

Beeing able to predict whether a user will churn or not is important. If the business reacts appropriately it can apply countermeasures to "prevent" the user from leaving the app. Furthermore valuable insights are gained by analysing the reasons why users leave the app. Using this information the user-experience can be improved st less users leave the app.

## Results

|   |  Gradient Boost Classifier |  Random Forest Classifier | Logistic Regression  |
|---|---|---|---|---|
| f1_score  |   0.4375 | 0.4444  | 0.3999  |
| accuracy  |  0.739 |0.7826   | 0.7826   |
| predicted user churn   |  0.188 | 0.1159  | 0.0869  |

Gradient Boost Classifier
f1_score: 0.4375
accuracy: 0.7391304347826086
predicted user churn ration: 0.18840579710144928

Random Forest Classifier
f1_score: 0.44444444444444436
accuracy: 0.782608695652174
predicted user churn ration: 0.08695202898550725

Logistic Regression
f1_score: 0.39999999999999997
accuracy: 0.782608695652174
predicted user churn ration: 0.08695652173913043

*actual user churn ratio: 0.28

##Files
The project consists of two files:
<ol>
  <li>Sparkify.ipynb: notebook used to develop ML models</li>
  <li>mini_sparkify_event_data.json: file containing the user activity log data</li>
</ol>


 The repository must have a README.md file that communicates the libraries used, the motivation for the project, the files in the repository with a small description of each, a summary of the results of the analysis, and necessary acknowledgements.



