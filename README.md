# ATM-Interface
The given code is an implementation of a simple ATM machine program in Java. It allows users to perform basic operations like withdrawing money, depositing money, checking the account balance, and viewing previous transactions.

The program begins by asking the user to enter a 4-digit PIN. If the entered PIN does not match the predefined PIN (1301 in this case), the program displays an error message and exits. Otherwise, it enters into a loop that presents the main menu to the user.

The main menu provides the following options:

Withdraw: Allows the user to withdraw money from their account. It checks if the account balance is sufficient and deducts the withdrawn amount if valid.
Deposit: Allows the user to deposit money into their account. It adds the deposited amount to the account balance if valid.
Check Balance: Displays the current account balance.
View Previous Transactions: Currently, this option displays a message indicating that no previous transactions are available. It can be expanded to keep track of transactions in a data structure.
Exit: Terminates the program.
After executing the selected operation, the program prompts the user whether they want to continue or not. If the user enters anything other than 'Y' or 'y', the program displays a farewell message and exits.

The isValidPin() method is not used in the code and can be removed unless it is intended to be used for custom PIN validation.
