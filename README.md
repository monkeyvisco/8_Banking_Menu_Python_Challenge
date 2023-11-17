# customer_banking
Ai BootCamp Module 3 Challenge Customer Banking System by Aaron Wood

Script customer_banking.py allows users to calculate and output interest earned on savings and CD accounts. By running this application, users will be able to enter their savings and CD account information, see the interest earned, and view the updated balances after a speci ed number of months.

Accounts.py creates a Class called Account with arguments balance and interest.

cd_account imports the Account class and creates a function that:
    . creates a CD account instance
    . calculates interest earned based on user input
    . updates account balance w/ interest earned and updated balance
    . returns updated balance and interest earned.

savings_account.py accomplishes the same for a Savings account.

customer_banking.py imports the cd_account and savings_account functions, prompts the user for function-required input, calls those functions and displays the results: interest earned and new balance
