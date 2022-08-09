#	Prosper loans project
This project was created during Data Analyst Nanodegree by Udacity Visit Udacity Data set was downloaded form Udacity site

#	This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

I've picked only some of variables including : 


ListingKey : Unique key for each listing, same value as the 'key' used in the listing object in the API.

Term : The length of the loan expressed in months.

BorrowerAPR : The Borrower's Annual Percentage Rate (APR) for the loan.

BorrowerRate : The Borrower's interest rate for this loan.

ProsperScore : A custom risk score built using historical Prosper data. The score ranges from 1-10, with 10 being the best, or lowest risk score. Applicable for loans originated after July 2009

Occupation: The Occupation selected by the Borrower at the time they created the listing.

IsBorrowerHomeowner : A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide documentation confirming they are a homeowner.

DebtToIncomeRatio: The debt to income ratio of the borrower at the time the credit profile was pulled. This value is Null if the debt to income ratio is not available. This value is capped at 10.01 (any debt to income ratio larger than 1000% will be returned as 1001%).

#	Then I've cleaned it creating new dataset with informations on 74127 diffrent loans to try to anwser following questions:

1. Are people who own property are more willing to take loans?

2. Is specific occupations are more willing to take loans, and which one has the highest debts (Income to debt ratio)?

3. What affects the borrower’s APR or interest rate?


#	And this is my findings:

1. Yes. Most of borrowers got a property. Diffrence is not huge less then 10%.

2. Professionals are by far the most popular occupation among borrower with almost triple of occurs of the second one on list Executive. We got similar levels of loans among places 2 and 10. Most borrowers have a debt to income ratio between 0.2 and 0.3. Teacher's Aides are willing to spend over 45% of their salaries for loan installments. Students as a group tends to have very high income to debt ratio except for the ones in technical schools which have the lowest average debt to income ratio among dataset.

3. What affect Borrowers ARP the most is Prosper Score. Different occupations get different Prosper Scores of average. Owning a property does not affect our loan ARP or Prosper Score much. Term of loan sometimes could have effect on loan. Peoples with high Prosper Scores got lower Debt to Income Ratio on average.