BANK MARKETING: Predicting Whether The Customer Will Subscribe To Term Deposit.

Introduction
Marketing is a process by which companies create value for customers and build strong customer relationships in order to capture value from customers in return. Marketing campaigns are characterized by focusing on the customer needs and their overall satisfaction. Nevertheless, there are different variables that determine whether a marketing campaign will be successful or not. There are certain variables that we need to take into consideration when making a marketing campaign.
The 4 P's of Marketing
Segment of the Population: To which segment of the population is the marketing campaign going to address and why? This aspect of the marketing campaign is extremely important since it will tell to which part of the population should most likely receive the message of the marketing campaign.

Distribution channel to reach the customer's place
Implementing the most effective strategy in order to get the most out of this marketing campaign. What segment of the population should we address? Which instrument should we use to get our message out? (Ex: Telephones, Radio, TV, Social Media Etc.)

Price:
What is the best price to offer to potential clients? (In the case of the bank's marketing campaign this is not necessary since the main interest for the bank is for potential clients to open depost accounts in order to make the operative activities of the bank to keep on running.)

Promotional Strategy: 
This is the way the strategy is going to be implemented and how are potential clients going to be address. This should be the last part of the marketing campaign analysis since there has to be an indepth analysis of previous campaigns (If possible) in order to learn from previous mistakes and to determine how to make the marketing campaign much more effective.
About The Dataset
The dataset is related with direct marketing campaigns (phone calls) of a Portuguese banking institution.The classification goal of this dataset is to predict if the client or the customer of polish banking institution will subscribe a term deposit product of the bank or not. Now the question comes what is term deposit ?

What is a Term Deposit?
A term deposit is a cash investment held at a financial institution. Your money is invested for an agreed rate of interest over a fixed amount of time, or term. Term deposits can be invested into a bank, building society or credit union.

When the money is deposited, the customer understands that the money is there for the pre-determined period which usually ranges from 1 month to 5 years and the interest rate is guaranteed not to change for that nominated period of time. Typically, the money can only be withdrawn at the end of the period – or earlier with a penalty attached.

Term deposits are popular with investors who prefer capital security and a set return as opposed to the fluctuations of, say, the share market. Many investors also use term deposits as a part of their investment mix.For more information with regards to Term Deposits please click on this link from Investopedia: https://www.investopedia.com/terms/t/termdeposit.asp
You are provided with following files:

train.csv : Use this dataset to train the model. This file contains all the client and call details as well as the target variable “subscribed”. You have to train your model using this file.

test.csv : Use the trained model to predict whether a new set of clients will subscribe the term deposit.

Dataset Attributes
Here is the description of all the variables :

Variable: Definition
ID: Unique client ID
age: Age of the client
job: Type of job
marital: Marital status of the client
education: Education level
default: Credit in default.
housing: Housing loan
loan: Personal loan
contact: Type of communication
month: Contact month
day_of_week: Day of week of contact
duration: Contact duration
campaign: number of contacts performed during this campaign to the client
pdays: number of days that passed by after the client was last contacted
previous: number of contacts performed before this campaign
poutcome: outcome of the previous marketing campaign
Output variable (desired target):
Subscribed (target): has the client subscribed a term deposit?
Tools and Algorithms Used for Analysis
Python
Numpy
Pandas
Seaborn
Logistic Regression
Decision Tree Classifier
References
Kaggle Datasets
UCI Machine Learning Repository
