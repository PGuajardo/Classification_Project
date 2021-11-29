# Classification Project - By Paige Guajardo

## Goals defined by Telco!

#### 1: Finding out what are the drivers of churn at Telco (Why are customers churncing)?
#### 2: Create a ML(using classification algorithms) and create a model that accrately predicts churn!
#### 3: Deliver report of step by step process, what steps where taken, why and what the outcomes were!


# Project Goals: 

*The goal of this project is to define the key drivers of churn, which customers are at risk of churning, and make recommendations for changes using a classifcation ML on the Telco data set provided to create the best fit model that identifies, and gives results of churn based on the findings to help reduce churn and increase customer retaention, and a step by step process of the steps taken and the outcomes of the findings.*


# Project Description:

*The Churn rate at Telco is increasing and our customer retaention is decreasing, we want to find out why churn is increasing, why our customers will retain,
and how to keep our monthly program. If we do not find this reason we'll lose more profits and continue to lose our main clients. We will analyze customers who aare more likely to churn, and develop a model for predicting churn based on those findings, and develeop a recommendation for future programs taht will be able to assist and predict the likely hood of customer churning and decrease in retention (via csv)*

# Initial Questions:

*Is the payment type 'Electric Check' a major cause for churn?*
*Does the internet service type 'Fiber' a major cause for churn?*
*Is being a senior citizen a reason for churn?*

# Data Dictionary:

|  something | else |
_________________________
| data 1  |   variable |
##### Come back
customer_id  | ID of customers
gender | gender of customer (Male or Female)
senior_citizen | encoded value where 0 is false and 1 is true for being a senior citizen
partner| yes or no if customer has a partner (married)
dependents | yes or no if cusomer has dependents
tenure | How many months a customer has been paying for
phone_service | yes or no if customer chose phone service
multiple_lines | customers chosen phone service (Multiple, single, none)
online_security | customer chosen security (yes, )
online_backup |
device_protection |
tech_support |
streaming_tv |
streaming_movies |
paperless_billing |
monthly_charges |
total_charges |
churn | Yes or no if customer has churned
contract_type |
internet_service_type |
payment_type |
is_male | encoded value
has_partner | encoded value
has_dependent | encoded value
phone_service_Yes | encoded value
multiple_lines_No phone service | encoded value
multiple_lines_Yes | encoded value
online_security_No internet service | encoded value
online_security_Yes | encoded value
online_backup_No internet service | encoded value
online_backup_Yes | encoded value
device_protection_No internet service | encoded value
device_protection_Yes | encoded value
tech_support_No internet service | encoded value
tech_support_Yes | encoded value
streaming_tv_No internet service | encoded value
streaming_tv_Yes | encoded value
streaming_movies_No internet service | encoded value
streaming_movies_Yes | encoded value
paperless_billing_Yes | encoded value
has_churn | encoded value
contract_type_One year | encoded value
contract_type_Two year | encoded value
internet_service_type_Fiber optic | encoded value
internet_service_type_None | encoded value
payment_type_Credit card (automatic) | encoded value
payment_type_Electronic check | encoded value
payment_type_Mailed check | encoded value

# Steps to reproduce:


*You will need an env.py file that contains the hostname, username and password of the mySQL database that contains the telco_churn.customers , telco_churn.internet_service_types, telco_churn.contract_types, telco_churn.payment_types tables. Store that env file locally in the repository*

*Clone the repo from github(including all the files acquireTelco.py and prepTelco.py) (confirm .gitignore is hiding your env.py file)*
*Libraries needed are pandas, matplotlib, seaborn, numby, sklearn*
*After so you will be able to run telco_report*

# The Plan:

Your readme should include a project plan which helps guide both the user and yourself through the different stages of the pipeline and steps you took to get to your conclusion.

## Hyptheses:


# Wrangle: 

 *Modules : acquireTelco.py and prepTelco.py*

test acquire function
add to acquire.py module
write code to clean data in notebook
merge code into a single function & test
write code to split data in notebook
merge code into a single function & test
merge functions in a single function & test
Add all 3 functions (or more) to prepTeclo.py file
import into notebook and test functions


# Data Split (prepare.py (def function), report.ipynb (run function))

This function takes in a dataframe, the name of the target variable
(for stratification purposes)
and splits the data into train, validate and test. 
Test is 20% of the original dataset, validate is .3 * .8 = 24% of the 
original dataset, and train is .7 * .80= 56% of the original dataset. 
The function returns, in this order, train, validate and test dataframes. 


# Explore

Is electric checking a large cause for churn rate?

Is fiber optics another large cause for churn?

Is being a senior citizen a reason for churn?

Is having a dependent a reason for churn?

