# Bank-Management-System
Bank Management System Using Java and File Handling.

A console-based "Bank Management System" implemented in Java, featuring basic banking operations with data persistence using file handling. This project allows users to create and manage accounts, perform transactions, and view account details, all stored in a text file (`accounts.txt`).

---

## Features

1. **Account Creation**:
   - Register a new user with:
     - Name
     - Account Number (supports large numbers using `long` type)
     - Age
     - Initial Balance

2. **Account Operations**:
   - Deposit Money
   - Withdraw Money (ensuring a minimum balance of ₹1000)
   - Balance Inquiry

3. **Account Management**:
   - Update Customer Details (Name, Age)
   - Delete an Account

4. **Data Persistence**:
   - Account details are stored in a file (`accounts.txt`) using file handling.
   - Supports reading and updating account data efficiently.

---

## Getting Started

### Prerequisites
- **Java Development Kit (JDK)**: Ensure JDK 8 or above is installed.
- **Text Editor/IDE**: Use VS Code, IntelliJ IDEA, or any editor of your choice.

### Running the Program

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd BankManagementSystem
   ```

2. **Compile the Code**:
   ```bash
   javac BankManagementSystem.java
   ```

3. **Run the Program**:
   ```bash
   java BankManagementSystem
   ```

4. Follow the menu-driven interface to interact with the system.

---

## File Structure

- **BankManagementSystem.java**: The main Java file containing the program logic.
- **accounts.txt**: The file where account data is stored.

---

## Sample Workflow

1. **Create an Account**:
   - Enter details such as Name, Account Number, Age, and Initial Balance.

2. **Perform Transactions**:
   - Deposit money to an account.
   - Withdraw money, ensuring a minimum balance.

3. **Manage Accounts**:
   - Update customer details like Name and Age.
   - Delete an account when no longer needed.

4. **View Account Balance**:
   - Check the current balance of an account.



## Example Account Format in `accounts.txt`
Each line represents an account:

Name,AccountNumber,Age,Balance
John,234343223443211,30,15000.50


## Future Enhancements
1. Add role-based access control.
2. Implement a GUI-based version.
3. Integrate with a database for better scalability.
4. Generate transaction history or mini-statements.


## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any improvements or new features.

---

