# credit-risk-classification

# Overview of the Analysis
In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis is to perdict the credit risk of loan applicants to see if they are are a high-risk or low-risk borrower.
* The financial information of the data are loan size, interest rate, borrower income, debt-to-income, number of accounts, derogatory marks, and total debt. We use these factors to predict if the applicants are a healthy loan or a high-risk loan.
* The loan status variables on the original database have value counts of healthy loan having 75,036 data points and high-risk having 2,500 data points. On the resampled database they both had 56,271 value counts
* The data was separted, then split into traing and testing datasets using train_test_split. Then created a Logistic Regression Model with both the original model and the resampled model. Finally both made predictions and a classification report to compare them to one another.

# Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:

![Screenshot 2023-05-02 at 10 58 53 PM](https://user-images.githubusercontent.com/117786548/235842641-63234501-0340-460a-b47a-84ee66fe6080.png)
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  
* Machine Learning Model 2:

![Screenshot 2023-05-02 at 10 59 20 PM](https://user-images.githubusercontent.com/117786548/235842663-5e16e0f2-f0a3-4f04-9fb0-6f9305d543ad.png)
  * Description of Model 2 Accuracy, Precision, and Recall scores.
# Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
The model using the resampled data show high accuracy in all aspects of the test proving itself useful and reliable when make a prediction for loan applicants.
