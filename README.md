# 🏦 Bank Marketing

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. Using classification algorithms, like Naive Bayes, Logistic Regression, Random Forest, Decision Tree, Support Vector Machine and Gradient Boosting, the goal of this project is to predict if the client will subscribe a term deposit (variable y).


At the end of this project, the following conclusions were reached:


- Random Forest Classifier was the model that achieved the best accuracy, with 96.23%;


- From the model, it will be possible to predict whether or not the customer will subscribe a term deposit, placing all the necessary variables for the classification test;


- The 'duration' outliers could be removed, such as values equal to zero, which indicates that there was no contact with the customer, so consequently there was no term deposit. But this could damage the entire structure of the models, so they were kept for the algorithms to learn. In this case, there would need to be an agreement with the bank's business area, which would (or not) guide the deletion of this data, in case they were unnecessary;


- The same case would apply to the 'unknown' values, found in several columns of the dataset. Who should decide the exclusion or imputation of these data would be the business area;


- Other models can and should be tested;
