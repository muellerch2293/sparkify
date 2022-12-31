# Sparkify - Udacity DATA SCIENTIST CAPSTONE 
## Overview and Motivation

In this project the user data of a ficitional music streaming app called Sparkify was used to develop ML models that predict the customer churn of sparkify.

According to https://www.qualtrics.com/uk/experience-management/customer/customer-churn/ Customer Churn is defined as follows:
"Customer churn, also known as customer attrition, is when someone chooses to stop using your products or services. In effect, it's when a customer ceases to be a customer. "

Beeing able to predict whether a user will churn or not is important. If the business reacts appropriately it can apply countermeasures to "prevent" the user from leaving the app. Furthermore valuable insights are gained by analysing the reasons why users leave the app. Using this information the user-experience can be improved st less users leave the app.

## Results

|   |  Gradient Boost Classifier |  Random Forest Classifier | Logistic Regression  |
|---|---|---|---|
| f1_score  |   0.4375 | 0.4444  | 0.3999  |
| accuracy  |  0.739 |0.7826   | 0.7826   |
| predicted user churn   |  0.188 | 0.1159  | 0.0869  |

*actual user churn ratio: 0.28

## Files
The project consists of two files:
<ol>
  <li>Sparkify.ipynb: notebook used to develop ML models</li>
  <li>mini_sparkify_event_data.json: file containing the user activity log data</li>
</ol>

## Libraries
pyspark, numpy, sklearn, seaborn, matplotlib, pandas



