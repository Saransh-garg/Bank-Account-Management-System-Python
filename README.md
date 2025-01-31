# Python Bank Account Management System
## Objective:

Build a fully functional bank account management system using Python that supports creating bank accounts, performing transactions, storing data using file handling, and generating reports.

### Account Management

### Functions to Implement:

- **create_account():**
  - Takes user input for account holder’s name and account type.
  - Generates a unique account number.
  - Sets an initial balance.
  - Stores account details in a dictionary.
- **view_account_details(account_number):**
  - Retrieves and displays the account holder's details (name, account number, account type, and balance).
### Transactions

### Functions to Implement:

- **deposit(account_number, amount):**
  - Adds the specified amount to the account balance.
  - Updates the transaction history.
- **withdraw(account_number, amount):**
  - Deducts the specified amount from the account balance, ensuring the balance doesn’t go negative.
  - Updates the transaction history.
- **transfer(from_account, to_account, amount):**
  - Transfers the specified amount from one account to another, ensuring sufficient balance in the sender’s account.
  - Updates both accounts’ balances and transaction histories.
### File Handling (Using pickle)

- Store account details and transaction history in a file.
- Use pickle to load data at the start and save it at the end.
### Functions to Implement:

- **save_data():** Saves account details and transaction history to a file.
- **load_data():** Loads account details and transaction history from a file at the start of the program.
### Reports

### Functions to Implement:

- **view_transaction_history(account_number):**
  - Displays a specific account’s transaction history, including the date, type of transaction (deposit, withdrawal, transfer), and amount.
- **generate_summary(account_number):**
  - Total deposits
  - Total withdrawals
## User Interaction (Interactive Menu)

### Menu Options:

- **Open a New Account**

- **View Account Details**

- **Perform Transactions**
  - Deposit
  - Withdraw
  - Transfer
- **Exit**

### Error Handling

- Ensure that deposit and withdrawal amounts are positive.
- Handle cases where the user tries to withdraw more money than available.
- Check for valid account numbers during transactions.
### Bonus (Optional)

- **Login System:**
  - Implement a login system with a username and password for each account holder.
  - Use file handling to store and retrieve login credentials.
- **Lambda Functions:**
  - Use lambda functions to simplify calculations, such as applying transaction fees or calculating total deposits/withdrawals.
