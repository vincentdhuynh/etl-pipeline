![image](https://github.com/<h1>Set Up an ETL Pipeline with Manual Steps</h1>

Goals - Build a manual ETL process where I  extract data from Excel, transform it in SQL, and load it into a reporting dashboard in Tableau.

This dataset represents salaries gathered through an online survey and is continuously growing as new users submit their salary information. 
Datasource: [https://oscarbaruffa.com/messy/](https://docs.google.com/spreadsheets/d/1IPS5dBSGtwYVbjsfbaMCYIWnOuRmJcbequohNxCyGVw/edit?resourcekey#gid=1625408792)

# of rows (Begin): 11,588
# of rows (Current): 28,118
# of Rows (After Cleaning):

Data Cleaning Process
- Remove duplicate data
- Address missing and null values
- Standardize/reformat data
- Eliminate outliers
- Validate data accuracy

  Survey Questions 
  - Timestamp: Time each response was submitted (DateTime)
  - How old are you?: Age range
  - What industry do you work in?
  - Job title	If your job title needs additional context, please clarify here:
  - What is your annual salary? (You'll indicate the currency in a later question.
  - If you are part-time or hourly, please enter an annualized equivalent -- what you would earn if you worked the job 40 hours a week, 52 weeks a year.)
  - How much additional monetary compensation do you get, if any (for example, bonuses or overtime in an average year)? Please only include monetary compensation here, not the value of benefits.
  - Please indicate the currency
  - If "Other," please indicate the currency here:
  - If your income needs additional context, please provide it here:
  - What country do you work in?
  - If you're in the U.S., what state do you work in?	What city do you work in?
  - How many years of professional work experience do you have overall?
  - How many years of professional work experience do you have in your field?
  - What is your highest level of education completed?
  - What is your gender?
  - What is your race? (Choose all that apply.)
