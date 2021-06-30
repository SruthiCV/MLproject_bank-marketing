Introduction
•The data set is related to marketing campaigns of a bank.
•The marketing campaigns were conducted through phone calls to market a product (bank term deposit) to existing bank clients who had or had not taken up previous term deposit products.
Problem Overview
•Numerous repetitive bank marketing campaigns over time has reduced its desired effect on its success rates.
•For economical reasons, banks hope to execute marketing call campaigns directly on better groups of potential clients.
•Not costs effective to make direct contact with all existing clients
•Lesser contact-calls should be conducted but with higher success rates
Project Objective
Experimenting Various Binary Classifiers
•To determine key characteristics of clients who will be potential product subscribers to bank products so as to make future marketing campaigns successful ones.
Primary Objective
•The classification goal is to predict whether a client will subscribe to the product i.e. bank term deposit, which is denoted as variable “y” in the data set.

Data Attributes - Overview
Number of Observations : 45211, Number of attributes : 17
Bank client data:
•age (numeric)
•job : type of job (categorical: ‘admin.’,‘blue-collar’,‘entrepreneur’,‘housemaid’,‘management’,‘retired’,‘self-employed’,‘services’,‘student’,‘technician’,‘unemployed’)
•marital : marital status (categorical: ‘divorced’,‘married’,‘single’)
•education (categorical’unknown’,’secondary’,’primary’,’tertiary’)
•balance: average yearly balance in euros (numeric)
•default: has credit in default? (categorical: ‘no’,‘yes’)
•housing: has housing loan? (categorical: ‘no’,‘yes’)
•loan: has personal loan? (categorical: ‘no’,‘yes’)
Related with the last contact of the current campaign:
•contact: contact communication type (categorical: ‘cellular’,‘telephone’,’unknown’)
•month: last contact month of year (categorical: ‘jan’, ‘feb’, ‘mar’, …, ‘nov’, ‘dec’)
•day: last contact day of the month (numeric)
•duration: last contact duration, in seconds (numeric).
Other attributes:
•campaign: number of contacts performed during this campaign and for this client (numeric)
•pdays: days passed after the client was contacted from previous campaign (numeric)
•previous: number of contacts performed before this campaign and for this client (numeric)
•poutcome: outcome of the previous marketing campaign (categorical)
Output variable (desired target):
•y : has the client subscribed a term deposit? (binary: ‘yes’,‘no’)
