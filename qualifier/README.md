# Project Title
The Loan Qualifier  

The loan Qualifier application allows the end-users to analyze a multitude of loans in seconds while taking the stress out of the loan shopping experience. The user-friendliness of the application’s interface keeps the user at ease while entering private financial data. The application is able to quickly cross-examine loan and financial information to best match the user’s current circumstances which otherwise would be a timely endeavor. 


## Technologies

Python 3.7.10 64-bit needed in order to properly open the Loan Qualifier application. In order to run the Loan Qualifier fire 0.3.1, and questionary libraries will need to be uploaded into the python enviroment which is being used. Any test should be done using the pytest 5.4.2 framework. The output file will be written via Python's csv inbuilt module. 

---

## Installation Guide

The qualifier folder needs to be instarlled in your pc allong with the proper libraries. Please refer to Technologies section for more on libraries needed. 

---


## Examples

Sample if no qualifying loans are found

? Enter a file path to a rate-sheet (.csv): qualifier\data\daily_rate_sheet.csv
? What's your credit score? 500
? What's your current amount of monthly debt? 100
? What's your total monthly income? 2000
? What's your desired loan amount? 10000
? What's your home value? 20000
The monthly debt to income ratio is 0.05
The loan to value ratio is 0.50.
Found 0 qualifying loans
Sorry not qualifying loans

Sample if qualifying loans are found
? Enter a file path to a rate-sheet (.csv): qualifier\data\daily_rate_sheet.csv
? What's your credit score? 800
? What's your current amount of monthly debt? 100
? What's your total monthly income? 10000
? What's your desired loan amount? 10000
? What's your home value? 200000
The monthly debt to income ratio is 0.01
The loan to value ratio is 0.05.
Found 24 qualifying loans
? Would you like to save a copy of your qualified loan?   Yes
? Name your save file: Loan list
Saving file...


---

## Usage
Please refer to "qualifier_usage" PNG file

---

## Contributors
The Columbia Fintech Bootcamp team

Jose Sampedro
Cell:973-704-0729
sampedro.jose.a@gmail.com
---

## License
This project will be distributed under the GNU GPL. This will assert copyright, and give legal permission to others to copy, distribute and/or modify it.
 
Please refer to "LICENSE" document. 
