# Project Name
Lending Club Case study


## Table of Contents
* [General Info](#general-information)
* [Observations](#observations)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
This Project is about giving suggestions to the investors who is ready to fund the borrowers via lending club data.
Based on the suggestions the investors should be able to decide whether they need to fund the requested borrower or not. 
The lending club have provided the data to us, to do the analysis from which the suggestions can be derived.
The business problem what the client facing here is the chances of giving loan to the wrong persons who will never pay the loan are high ie providing loan to the defaulters.
And also the chances of not giving loan to the right person may result in loss of business for the investors.
The data set we used to analysis this issue is the loan.csv file which has the history of previously loan availed borrowers data 

## Observations
 People who have 1-10 years of work experience have taken more loans compared to other categories (other categories: Less than 1 year and more than 10 years)
 In the given data set, the maximum number of bankruptcies reported is two and there are five members for whom 2 bankruptcies are reported
 From the frequency plot of the 'purpose' variable, we can observe that people have taken loans mainly for debt_consolidation 
 People who own a house have barely taken loan for any purpose
 Borrowers with grade A and B have Fully Paid the loan compared to G and F. Also the ratio between Fully Paid and charged off is less in grade 'C'
 75% of the Loan amount requested by borrowers with 60 months term is less than or equal to 20000. On the other hand with term 30 months people have requested less amount
 
## Recommendations
- Borrowers where two bankruptcies are reported, 5 borrowers in our case can be directly blacklisted for giving further loans
- People who take loan for the purpose of debt_consolidation should be scrutinized properly
- If a borrower owns a home his loan can be approved
- from the data analysis , borrowers with grade 'C' should be verified more strictly as they have a greater chance of charge off
- People with 1-10 years of work experience could be given priority will approving loans

## Technologies Used
Pandas libray \
numpy libray \
matplotlib libray \
missingno library \
hvplot library \
seaborn library 



## Acknowledgements
This Project was made based on the previous modules information and live sessions


## Contact
Sumithra
Priya
