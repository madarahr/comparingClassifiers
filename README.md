# comparingClassifiers
The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit.

## Introduction

The goal is to compare and understand the right classifier to use to predict if a client of a bank will subscribe to a term deposit based on results of marketing campaign.  The results of this analysis can help achieve the right clients to approach.

* age
* type of job  
* marital status.    
* education     
* credit default    
* average yearly balance  
* has housing loan
* has personal loan 
* contact type
* contact day of week   
* contact month of year
* contact duration  
* number of contacts performed during campaign
* number of days that passed by after the client was last contacted from a previous campaign 
* number of contacts performed before this campaign  
* outcome of the previous marketing campaign
* has the client subscribed a term deposit? 

Four classifers were used to compare the prediction.
* k-nearest neighbors
* LogisticRegression
* Decision Tree Classifier
* Support Vector Machines

  
## Technology Used

* python
* Jupyter Notebook
* sklearn libraries within python
* Matplotlib for charts and images

## Approach

Data was cleaned to remove unnecessary columns prior to applying classifiers.  The ideal K value was determined before the classifiers were looped with the train-test data to make a comparison.  The results used for comparison were:

* Training Time Seconds
* Training Accuracy
* Testing Accuracy
* Precision no
* Precision yes
* F1 Score No
* F2 Score Yes
* Recall No
* Recall Yes

![image](https://github.com/user-attachments/assets/90217b67-1384-4fe0-837e-b123e4fe25c9)


## Conclusions

![image](https://github.com/user-attachments/assets/d1bbeb72-c2d1-4ea1-99ff-8cca1c5cb8dc)

* Computing Time:  The Logistic Regression had the least computing time and the SVM had the most computing time.

* Accuracy Score:  All of the classifiers haev a high accuracy score nidicating that the proportion of the correctly classified instances out of the total instances in the dataset.  All of the models had a high precision score for the clients that will not subscribe to the term deposit indicating a high confidence in the predictions made.  However, the classifiers were not accurate in predicting the clients that would subscribe to the term deposit expecially with the decision tree being below 50% accuracy.

* Recall:  The models are good at predicting a good proportion of the clients that will not subcribing to the term deposit.  However, they are very poor in predicting clients who will subscribe to term deposit.  SVM performed the worst close to 0 for clients who will subscribe to term deposit.

* F1 Score:  All the classifiers have a high F1 score for clients that will not subscribe to the term deposit, indicating a good balance between precision and recall.  All he classifiers have low F1 score for predictiing clients subscribing to term deposit suggesting a poor balance or poor performance on both metrics. 

Overall the Decision Tree Classifier has the best balance among the classifiers in predicting the clients who will subscribe to a term deposit.

## Findings

* Previous marketing campaigns that led to a successful outcome will need to be analyzed as this feature seemed to have the best impact in predicting the behavious of the clients.
* The contact duration has also been shown to have a high impact on predicting the outcome of the client subscribing to the term deposit.
* The contact month of March has had a positive impact on the decisions that the client will subscribe to a term deposit.

CLearly, marketing campaigns have helped and contacting the clients during the month of March and a higher duration of contact has led to a successful outcome of subscription. 
