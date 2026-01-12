Classifier Comparison - This project predicts whether a bank client will subscribe to a term deposit (y = yes/no) using client demographics, past campaign interactions, and economic indicators. The goal is to help the bank optimize its marketing efforts, reduce costs of unsuccessful calls, and increase subscription success rates.
It also compares and optimize the classifiers K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines.
                        

**Tools and Libraries Used**** : sklearn , 

**Dataset :** https://github.com/jpatil-bit/bank-subscription-classifier-comparison/blob/main/data/bank-additional-full.csv

**Key Features:** destination passanger weather temperature coupon expiration gender age maritalStatus has_children education occupation income car Bar CoffeeHouse Y Where 1 means accepted and 0 implies rejected.

**Analysis and hypothesis ***** Jupyter file containes all the EDA's and plots ***

https://github.com/jpatil-bit/bank-subscription-classifier-comparison/blob/main/classifier_comparision.ipynb

**########## Hypothesize about drivers who accepted the bar coupons ##########**

Coupon rejection is more than coupon acceptance. Coupon acceptance rate is 56.8% , out of which 41.00% is the Bar coupon acceptance. Drivers over the age of 25 visit bars more frequently (more than once a month) compared to younger age groups.. Drivers with no kids and not in the occupation of farming, fishing, or forestry visit bars more frequently than parents in others.. Drivers with age <30 and income <50k , with passanger having no kids , not widowed , visits bar more frequently and visits restaurant < $20 4-8 times a months ########## Hypothesize about drivers who accepted the coffee coupons ##########

Coffee coupon acceptance rate is 49.92%. Sunny day with temperature of 30 F has more acceptance. 26 years old singles and 36 years old unmarried partner has more acceptance of coffee coupons. Male driving to non urgent destination has more acceptance than others. Visualizations Various visualizations are used in this analysis to uncover insights from the data:


**Prerequisites** Ensure you have Python 3.x installed and the necessary dependencies:

**Clone the repository:**

git clone https://github.com/jpatil-bit/bank-subscription-classifier-comparison.git
