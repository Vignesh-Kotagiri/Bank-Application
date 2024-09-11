# Bank-Application

This project is a simple Python program simulating basic banking operations. Users can check their balance, make deposits, withdraw money, or exit the system. The program provides an interactive menu for users to choose from, with input validation to ensure correct operations.

## **Features**

- **Show Balance**: Displays the current balance in the account.
- **Make Deposit**: Allows the user to deposit a valid amount into the account.
- **Withdraw Money**: Enables the user to withdraw money if there are sufficient funds.
- **Exit**: Exits the banking system.

## **How It Works**
The program offers the following options in a loop until the user decides to exit:

1. **Show Balance**:  
   Displays the current account balance.
2. **Make Deposit**:  
   Prompts the user to enter an amount to deposit. If the amount is valid, it is added to the balance.
3. **Withdraw Money**:  
   Prompts the user to enter an amount to withdraw. If sufficient funds are available, the balance is deducted; otherwise, an error message is displayed.
4. **Exit**:  
   Ends the program.

### **Sample Output:**

markdown
Copy code
# Banking Application

This is a simple banking application written in Python where users can perform the following actions:
1. Show Balance
2. Make Deposit
3. Withdraw Money
4. Exit

## Sample Output

Banking

Show Balance
Make Deposit
Withdraw Money
Exit
Enter your choice (1 to 4): 1

Your Balance is 0 rupee

markdown
Copy code

## Getting Started

### Prerequisites
- Python 3.x installed on your machine.

### Running the Program

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/banking-system.git
Navigate to the project directory:

bash
Copy code
cd banking-system
Run the program:

bash
Copy code
python banking_system.py
Code Explanation
check_balance(balance): Displays the current balance in rupees.
deposit(): Takes user input for deposit and validates if the amount is positive.
withdraw(balance): Allows the user to withdraw money, ensuring there is enough balance.
main(): The main function that handles the menu and controls the flow of the program.
Example Usage
Start the program, and you'll see a menu with four options.
Choose 1 to check the balance, 2 to deposit money, or 3 to withdraw.
The program continues to prompt the user until option 4 (Exit) is chosen.
Contributing
Feel free to submit pull requests or open issues if you find any bugs or have suggestions for improvements.


