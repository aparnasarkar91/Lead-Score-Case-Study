# Lead-Score-Case-Study
## Problem Statement:

X Education is an education company that offers online courses for industry professionals. The company attracts many visitors to its website through various marketing channels, such as websites, search engines, and referrals. Some of these visitors fill out a form with their contact information and become leads for the company. The sales team then tries to convert these leads into customers by calling them, emailing them, etc. However, the company faces a problem: its lead conversion rate is very low. Out of 100 leads, only 30 become customers on average. This means that the sales team is wasting a lot of time and resources on leads that are not interested or ready to buy. 

To solve this problem, X Education wants to identify the most potential leads, also known as 'Hot Leads'. These are the leads that have a high probability of becoming customers. By focusing on these leads, the company hopes to increase its lead conversion rate and improve its efficiency. The company has hired you to help them with this task. Your job is to build a model that can assign a lead score to each lead based on various factors, such as their demographics, behavior, preferences, etc. The higher the lead score, the more likely the lead is to convert. The lower the lead score, the less likely the lead is to convert. The company's CEO has set a target of achieving an 80% lead conversion rate with this model.

## Data:

The Leads dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not. The target variable is the column 'Converted' which has a value of 1 for converted leads and 0 for non-converted leads. One thing to note is that some of the categorical variables have a level called 'Select' which indicates that the lead did not select any option from the list. This is equivalent to a missing value and should be handled accordingly.

## Goals of the Case Study:

Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

There are some more problems presented by the company which your model should be able to adjust to if the company's requirement changes in the future so you will need to handle these as well. These problems are provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. Also, make sure you include this in your final PPT where you'll make recommendations.

File Details:

- LeadScoring.ipynb : Python file containing codes for the lead scoring model and related analysis
- Lead Score Case Study Subjective Questions.pdf : Answers to subjective questions
- Lead Score Case Study Presentation.pdf : Management Presentation
- Leads.csv : Dataset worked on
- Leads Data Dictionary.xlsx : Data Dictionary
- Lead Score Case Study Summary.pdf : Summary of the .py file
