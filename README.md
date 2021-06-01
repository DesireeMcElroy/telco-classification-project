# Telco Classification Project
 
# Plan -> Acquire -> Prepare -> Explore -> Model & Evaluate -> Deliver


# Objectives:
- Document all my code for data acquisition, data preparation, exploration, model & evaluation in a jupyter notebook.
- Create and use functions that automate my process.
- Construct a machine learning model that can predict customer churn via classification technique.
- Deliver a 5 minute presentation via a jupyter notebook walkthrough for my audience, the data science team at CodeUp.
- Answer questions about my code, process, model and summary.

# Business Goals:
- To find drivers of churn for the Telco company.
- Create a machine learning model that can predict customer churn.
- Document my process and findings in a clean readable notebook.





### Data Dictionary
---
| Attribute | Definition | Data Type |
| ----- | ----- | ----- |
|payment\_type\_id |How a customer pays their bill each month | int64 |
|contract\_type\_id|Which contract type a customer has | int64 |
|internet\_service\_type_id|Type of internet service a customer has | int64 |
|customer\_id|Alpha-numeric ID that identifies each customer| object |
gender|Gender of the customer| object |
senior_citizen|If customer is 65 or older| int64 |
partner|If customer is married| object | 
dependents|If a customer lives with dependents| object |
tenure|The length of a customers relationship with Telco™ measured in months|  int64 |
phone_service|If a customer has phone service| object |
multiple_lines|If a customer has multiple phone lines| object |
online_security|If a customer has online security add-on| object |
online_backup|If a customer has online backups add-on| object |
device_protection|If a customer has a protection plan for Telco™ devices| object |
tech_support|Whether a customer has technical support add-on| object |
streaming_tv|If a customer uses internet to stream tv| object |
streaming_movies|If a customer uses internet to stream movies| object |
paperless_billing|If a customer is enrolled in paperless billing| object |
monthly_charges|The amount a customer pays each month| object |
total_charges|The total amount a customer has paid for Telco™ services| object |
|internet\_service\_type|Type of internet service a customer has| object |
|contract_type|The type of contract a customer has| object |
|payment_type|How a customer pays their bill| object |

| Target | Definition | Data Type |
| ----- | ----- | ----- |
|churn|Indicates whether a customer has terminated service| object |


# Key Findings
- A chi2 statistics test confirms having a partner and paperless billing has an association to customer churn.
- A two sample one tailed ttest confirmed an association with monthly charges to customers churn.
- Visualizations and correlation numbers confirm additional features such as contract type and having a dependent is associated to churn.


# Model
- Logistic Regression gave us the worst accuracy overall.
- Decision Tree was a close second choice.
- Random Forest Model 3 is best performed model.
- Random Forest Model 3 gaves us a 75% accuracy on the test set.

# Recommendations:
- Offer incentives targeting churned customers with common features.
- Improve model performance by focusing on specific features such as contract type.
- Offer discounted services the first 6 months to improve tenure.
- Offer exit surveys to departing customers to improve or add more features to increase model performance.

# How to recreate this project:
- You need:
 - Python
 - SQL
 - classification models

 - Libraries:
 - pandas 
 - numpy 
 - matplotlib/seaborn
 - sklearn 
 - stats 

Clone this repository:
$ git clone git@github.com:DesireeMcElroy/telco-classification-project.git
