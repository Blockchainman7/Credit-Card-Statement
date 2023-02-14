# Credit-Card-Statement
Creating a balance variable that calculates the running balance of the user’s account
If the field says CREDIT, then add the amount to the balance
If the field says DEBIT, then subtract the amount to the balance
If the final amount is greater than zero, charge a 10% fee and warn the user
If the final amount is zero, thank the user for their payments
If the final amount is less than zero, thank the user for their payment and display their overpayment

In this code, we assume that the CSV file has three columns: date, amount, and type (CREDIT or DEBIT). You can modify the code to match the actual columns and format of your CSV file.

The code reads the CSV file line by line and extracts the amount and type of each transaction. It then updates the balance variable accordingly.

After processing all transactions, the code checks the final balance and displays a message based on the rules you specified. If the balance is positive, a 10% fee will be charged, and a warning message is displayed. If the balance is zero, a message of thanks is displayed. If the balance is negative, the overpayment is calculated and displayed in the message.

Note that this code is a simplified example that assumes the CSV file is well-formed and all transactions are valid. In a real-world application, you may need to add more error handling and validation logic to ensure the input data is correct and safe to use
