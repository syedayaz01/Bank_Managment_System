# Bank_Managment_System

Here's a README for your GitHub repository that describes your project. Feel free to customize it further if needed:

---

# Bank Management System

## Overview

The **Bank Management System** is a simple Java-based application that allows users to manage basic banking operations such as creating accounts, depositing and withdrawing money, checking account balances, and viewing account details. The system uses a console-based interface where users can interact with the system through a menu-driven approach.

## Features

- **Create Account**: Allows users to create a new bank account with an initial deposit.
- **Deposit Money**: Enables users to deposit money into an existing account.
- **Withdraw Money**: Allows users to withdraw money from their account, ensuring sufficient balance.
- **Check Balance**: Users can check the balance of their account.
- **View Account Details**: Displays detailed information about the user's account, such as account holder's name, account number, and balance.
- **Exit**: Exits the application gracefully with a thank-you message.

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/Bank_Management_System.git
   ```

2. Open the project in your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).

3. Run the `Main` class, which contains the `main()` method that starts the application.

4. Follow the on-screen menu to perform various operations:
   - **1**: Create a new account.
   - **2**: Deposit money into an account.
   - **3**: Withdraw money from an account.
   - **4**: Check your account balance.
   - **5**: View your account details.
   - **6**: Exit the application.

## Code Structure

- **Main.java**: The entry point of the application that contains the main menu and user interactions.
- **BankAccount.java**: A class that represents a bank account with methods for depositing, withdrawing, and displaying account details.
- **Bank.java**: A class that manages multiple bank accounts, allows creation of new accounts, and handles transactions.

## Example

Here’s an example of how the system works:

```plaintext
--- Banking Management System ---
1. Create Account
2. Deposit Money
3. Withdraw Money
4. Check Balance
5. View Account Details
6. Exit
Enter your choice: 1
Enter Account Holder Name: John Doe
Enter Initial Deposit: 5000
Account created successfully! Account Number: 1001

--- Banking Management System ---
1. Create Account
2. Deposit Money
3. Withdraw Money
4. Check Balance
5. View Account Details
6. Exit
Enter your choice: 2
Enter Account Number: 1001
Enter Deposit Amount: 2000
Amount deposited successfully! New Balance: 7000
```

## Installation

1. Ensure you have Java installed on your system. You can download and install Java from the official website: [Oracle JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
2. Compile and run the `Main.java` class:
   ```bash
   javac Main.java
   java Main
   ```
