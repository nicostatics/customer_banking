# Module 3 Challenge
## Objective
The objective of this challenge was to use everything we learned about object-oriented programming to build a solution that allows a user to input values and have the new savings account balance as well as CD balance be output.  

## Code Details 
This program has 4 files:  
1. `Accounts.py`
    This file has the class definition and two methods under it that sets the balance and sets the interest rate
2. `cd_account.py`
    This file has a single function that sets and updates the CD balance given a certain interest APR.  With the APR, it calculates the interest earned and uses that to update the balance.  The function returns the interest earned and the updated balance.
3. `savings_account.py`
    This file has a single function sets and updates the savings account balance given a certain interest APR.  With the APR, it calculates the interest earned and uses that to update the balance.  The function returns the interest earned and the updated balance.
4. `customer_banking.py`
    This is the main file that has a single main function.  It prompts the user to enter the original balances for both the savings account and the CD account, the APR for both accounts, and the number of months.  The output of this is print statements that show the interest earned and the new balance for both.  
