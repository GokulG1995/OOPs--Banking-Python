# OOPs--Banking-Python
This project is a Banking System built in Python, showcasing fundamental concepts of programming, object-oriented design, and logical thinking. It's designed to replicate the functionality of a real-world bank, allowing users to create accounts, deposit, withdraw money, and check account details in a secure manner.
@@ -1 +1,15 @@
# OOPs-banking
# OOPs-banking
# Initialize a new bank account
account = BankAccount(account_number=12345678, pin=1234, balance=1000.0)
# Login to the account
account.login()  # Prompts for PIN and grants access upon correct input
# Deposit funds
account.deposit()  # Prompts to enter deposit amount and updates balance
# Withdraw funds
account.withdraw()  # Prompts to enter withdrawal amount, checks balance, and updates
# Check balance
account.check_balance()  # Displays the current balance
