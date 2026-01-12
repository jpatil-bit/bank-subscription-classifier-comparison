Classifier Comparison - This project predicts whether a bank client will subscribe to the campaign of the bank-product using client demographics, past campaign interactions, and economic indicators. The goal is to help the bank optimize its marketing efforts, reduce costs of unsuccessful calls, and increase subscription success rates.

The main goal is to compares and optimize the classifiers **K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines.**
                        

**Tools and Libraries Used**** : sklearn , pandas , time.

**Dataset :** https://github.com/jpatil-bit/bank-subscription-classifier-comparison/blob/main/data/bank-additional-full.csv

**Key Features:** destination passanger weather temperature coupon expiration gender age maritalStatus has_children education occupation income car Bar CoffeeHouse Y Where 1 means accepted and 0 implies rejected.

**Analysis and hypothesis ***** Jupyter file containes all the EDA's , Train/Test data model to compare the classifiers. ***

https://github.com/jpatil-bit/bank-subscription-classifier-comparison/blob/main/classifier_comparision.ipyn


**Prerequisites** Ensure you have Python 3.x installed and the necessary dependencies:

**Clone the repository:**

git clone https://github.com/jpatil-bit/bank-subscription-classifier-comparison.git

**Conclusion**
* The dataset collected is related to 17 marketing campaigns , that occurred between May 2008 and November 2010 corresponding to a total of 79,354 contacts.
* Splited the dataset into train and test sets (70% train, 30% test).
* Baseline accuracy (majority class): 0.8873
* ## Model Performance Comparison
**Metrics : Before the optimization of the model:** 
| Model               | Train Time (s) | Train Accuracy | Test Accuracy |
|---------------------|----------------|----------------|---------------|
| Logistic Regression | 0.32           | 0.88           | 0.88          |
| SVM                 | 3.44           | 0.88           | 0.88          |
| KNN                 | 0.002          | 0.89           | 0.87          |
| Decision Tree       | 0.04           | 0.91          | 0.86           | 

**Metrics(Hyperparameter) : After the optimization of the model:** 
| Model               | Train Time (s) | Train Accuracy | Test Accuracy |
|---------------------|----------------|----------------|---------------|
| Logistic Regression | 0.13           | 0.91           | 0.91          |
| Decision Tree       | 0.02           | 0.90           | 0.90          |
| SVM                 | 52.9           | 0.95           | 0.90          |
| KNN                 | 0.009          | 0.94           | 0.90          |  

Hyperparameter tuning significantly improved model performance, but Logistic Regression offers the best balance of accuracy, efficiency, and generalization.
It is the most suitable model for predicting whether a bank customer will subscribe to a term deposit.

**Prediction of which customer will subscribe to the subscrioption**
Customers contacted via cellular channels, with longer call durations, no existing housing or personal loans, and employed in administrative or professional roles. 
