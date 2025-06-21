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

Modeling:
• Use of multiple machine learning models.
• Cross-validation of models.
• Grid search hyperparameters.
• Appropriate interpretation of coefficients in models.
• Appropriate interpretation of an evaluation metric.
• Clear identification of an evaluation metric.
• Clear rationale for use of the given evaluation metric.

Findings:
• Clearly stated business understanding of the problem.
• Clean and organized notebook with data cleaning.
• Correct and concise interpretation of descriptive and inferential statistics.
• Clearly stated findings in their own section with actionable items highlighted in appropriate language for a nontechnical audience.
• Next steps and recommendations.
