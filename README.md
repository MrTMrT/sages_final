# sages_final
Final_project

PROJECT:
The purpose of the project is to determine whether given set of variables can be be used as a predictor in the probability of default modeling.I've appended readily available data-set of loans issued by one of the P2P lending operator in US with recourse and non-recourse states classification to determine whether those variables combined have any reliable predictive power. Well established weight of evidence concepts was used to shortlist variables before proceeding with logistic regression model

DATA:
I decided to compile two data sets: Lending Club Loan Data available at https://www.kaggle.com/wendykan/lending-club-loan-data with own elaboration of US recourse/non-recourse states classification as determined by Ghent and Kudlyak in Ghent, Andra C. and Kudlyak, Marianna, Recourse and Residential Mortgage Default: Evidence from U.S. States (February 25, 2011). Federal Reserve Bank of Richmond Working Paper No. 09-10R. Available at SSRN: https://ssrn.com/abstract=1432437 or http://dx.doi.org/10.2139/ssrn.1432437¶

CONCLUSIONS:
Recourse and non-recourse classification of the geographical location of any particular loan origination turned out to have very limited predictive power. The overall real life model usability is relatively low with AUCROC of just short of 70%
