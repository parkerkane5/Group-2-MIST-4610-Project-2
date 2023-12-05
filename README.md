
# Group 2 MIST 4610 Project 2




## Team Name
29704 Group 2

## Team Members
Enzo Vasallo @enzovasallo ('<br>')
Parker Kane @parkerkane5 ('<br>')
Kaylie Chin @kayliechin ('<br>')
Clint Kitchens @clintkitchens('<br>')
Ore Pratt @nathanp2020('<br>')
Jazlyn Piedra @mjp44773('<br>')

## Dataset
The dataset used was obtained from the US Data gov website : https://catalog.data.gov/dataset

Our data set is on the 2009-2010 Award Year Federal Family Education Loan Volume by School and it was obtained on the Data.gov website. 


Below are the columns and their definitions, that details what information is filled within the rows. 




Field Name:      Definition
OPE ID:          An 8-digit code identifying the school at its main branch
School:          The name of the school associated with the OPE ID
State:           The state in which the main campus is located
Zip Code:        The zip code of the main campus
School Type:     Indicates the control or ownership of the school.  
Recipients:      The number of loan recipients for the loan type during the award year for the time period reported on the spreadsheet.  For Subsidized, Unsubsidized, and Graduate PLUS loans, this is a count of student borrowers.  For Parent PLUS loans, this is a count of the students on whose behalf the loan was taken.  Since students can have multiple loan types in the same award year, you cannot sum the recipient counts from the four categories to obtain an accurate count of total recipients for the loan program during that award year.

'# of Loans Originated':
The number of loans initiated for the loan type during the award year for the time period reported on the spreadsheet.  

$ of Loans Originated:
The dollar amount of the loans initiated for the loan type during the award year for the time period reported on the spreadsheet.  This is the expected total loan amount if the loan is fully disbursed.

"# of Loans Disbursed":
The number of disbursements made for the loan type during the award year and quarter reported on the spreadsheet.  
$ of Loans Disbursed

The dollar amount of disbursements made for the loan type during the award year for the time period reported on the spreadsheet.  

Receipts, # of Loans Originated,	 $ of Loans Originated, # of Disbursements, and $ of Disbursements are repeated within the table for the Different types of loans such as FFEL SUBSIDIZED, FFEL UNSUBSIDIZED, FFEL PARENT PLUS, FFEL GRAD PLUS.	
## Questions
1) What is the average loan amount per recipient for Georgia and how does it compare to other Southeast states?


2)How do subsidized and unsubsidized originated and disbursed loans vary between public and private schools?

## Data Manipulation/Filters
Question 1:
Filters:
School Type: Public
State: AR, LA, MS,TN,KY,NC,SC,GA,FL,AL (South-East)
Calculations
Average Subsidized Loan (per recipient)
[FFEL Subsidized $ of Disbursements]/[FFEL Subsidized Recipients]
Average Unsubsidized Loan (per recipient)
[FFEL Unsubsidized $ of Disbursements]/[FFEL Unsubsidized Recipients]

## Analysis and Results
