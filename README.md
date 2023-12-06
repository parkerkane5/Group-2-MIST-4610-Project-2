# Group 2 MIST 4610 Project 2




## Team Name
29704 Group 2

## Team Members
Enzo Vasallo [@enzovasallo](https://www.github.com/enzovasallo)  <br>
Parker Kane  [@parkerkane5](https://www.github.com/parkerkane5) <br>
Kaylie Chin [@kayliechin](https://www.github.com/kayliechin)  <br>
Clint Kitchens  [@clintkitchens](https://www.github.com/clintkitchens) <br> 
Ore Pratt [@nathanp2020](https://github.com/nathanp2020) <br> 
Jazlyn Piedra  [@mjp44773](https://github.com/mjp44773) <br> 

## Dataset
The dataset used was obtained from the US Data gov website : https://catalog.data.gov/dataset

Our data set is on the 2009-2010 Award Year Federal Family Education Loan Volume by School and it was obtained on the Data.gov website. 


Below are the columns and their definitions, that details what information is filled within the rows. 




Field Name:      Definition

OPE ID:          An 8-digit code identifying the school at its main branch <br>

School:          The name of the school associated with the OPE ID <br>

State:           The state in which the main campus is located <br>

Zip Code:        The zip code of the main campus <br>

School Type:     Indicates the control or ownership of the school.   <br>

Recipients:      The number of loan recipients for the loan type during the award year for the time period reported on the spreadsheet.  For Subsidized, Unsubsidized, and Graduate PLUS loans, this is a count of student borrowers.  For Parent PLUS loans, this is a count of the students on whose behalf the loan was taken.  Since students can have multiple loan types in the same award year, you cannot sum the recipient counts from the four categories to obtain an accurate count of total recipients for the loan program during that award year. <br>

'# of Loans Originated':
The number of loans initiated for the loan type during the award year for the time period reported on the spreadsheet.  <br> 

$ of Loans Originated:
The dollar amount of the loans initiated for the loan type during the award year for the time period reported on the spreadsheet.  This is the expected total loan amount if the loan is fully disbursed.  <br>

"# of Loans Disbursed":
The number of disbursements made for the loan type during the award year and quarter reported on the spreadsheet.   <br>

$ of Loans Disbursed

The dollar amount of disbursements made for the loan type during the award year for the time period reported on the spreadsheet.   <br>

Receipts, # of Loans Originated,	 $ of Loans Originated, # of Disbursements, and $ of Disbursements are repeated within the table for the Different types of loans such as FFEL SUBSIDIZED, FFEL UNSUBSIDIZED, FFEL PARENT PLUS, FFEL GRAD PLUS.	
## Questions
1) What is the average loan amount per recipient for Georgia and how does it compare to other Southeast states?


2) How do subsidized and unsubsidized originated and disbursed loans vary between public and private schools?

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

Question 1

![Screenshot (136)](https://github.com/parkerkane5/Group-2-MIST-4610-Project-2/assets/148779254/71e03ba0-d3e7-4a5a-9ee1-b1686580be55)

In Georgia, the average loan amount per recipient is $2330 unsubsidized and $1864 subsidized. Among other southeastern states, it is very close to North Carolina at 5th place.
Louisiana residents on average receive more money from federal loans than any other southeastern state at $3193 unsubsidized and $2329 subsidized. 
This may indicate that both the standard of living and the standard of education in Georgia and states with lower average federal loan amounts is higher than Louisiana and other states that had higher average loan amounts.

Question 2

![Screenshot (139)](https://github.com/parkerkane5/Group-2-MIST-4610-Project-2/assets/148779254/41a7af75-1fbe-4586-a897-2c445fa0cd52)

For private and public schools respectively, Emory University and Kennesaw State University received the highest amount of loans across all four categories (Sub/Unsub, Originated/Disbursed). This suggests that these schools have a significant number of students that rely on federal student loans to finance their education. This also indicates the high cost of attendance including tuition and other expenses and need for federal aid. 

