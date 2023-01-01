# Sparkify - Udacity DATA SCIENTIST CAPSTONE 
Medium Link: https://medium.com/@muellerch2293/please-do-not-leave-5a31644680cf
## Overview and Motivation

In this project the user data of a ficitional music streaming app called Sparkify was used to develop ML models that predict the customer churn of sparkify.

According to https://www.qualtrics.com/uk/experience-management/customer/customer-churn/ Customer Churn is defined as follows:
"Customer churn, also known as customer attrition, is when someone chooses to stop using your products or services. In effect, it's when a customer ceases to be a customer. "

Beeing able to predict whether a user will churn or not is important. If the business reacts appropriately it can apply countermeasures to "prevent" the user from leaving the app. Furthermore valuable insights are gained by analysing the reasons why users leave the app. Using this information the user-experience can be improved st less users leave the app.

## Results

|   |  Gradient Boost Classifier |  Random Forest Classifier | Logistic Regression  |
|---|---|---|---|
| f1_score  |   0.399 | 0.518  | 0.272  |
| accuracy  |  0.695 |0.811 | 0.7681  |
| predicted user churn   |  0.231 | 0.115 | 0.0434  |
| training time  | 47 s | 602 s | 24 s  |
*actual user churn ratio: 0.28

## Files
The project consists of two files:
<ol>
  <li>Sparkify.ipynb: notebook used to develop ML models</li>
  <li>mini_sparkify_event_data.json: file containing the user activity log data (not in repository due to size, provided by Udacity)</li>
</ol>

## Libraries
pyspark, numpy, sklearn, seaborn, matplotlib, pandas



