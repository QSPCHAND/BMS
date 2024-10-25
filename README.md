# BMS
A compact Bank Management System in Java is structured to automate essential banking functions efficiently. Here’s a concise breakdown of its core components:

1. **User Management**:
   - **Roles**: Admins, Tellers, and Customers, each with defined permissions.
   - **Authentication**: Secure login for all users.

2. **Account Management**:
   - **Types**: Supports Savings, Checking, and Fixed Deposits.
   - **Details**: Customer information (name, ID, contact details) and account balance.

3. **Transaction Handling**:
   - **Deposits & Withdrawals**: Basic account operations.
   - **Fund Transfers**: Account-to-account within the bank.
   - **History**: Stores all transactions (amount, date, account IDs).

4. **Loan Processing**:
   - **Application & Approval**: Allows loan requests, approval, or rejection.
   - **Repayment Tracking**: Monitors installments and outstanding balance.

5. **Database Integration**:
   - **Storage**: Relational database (e.g., MySQL) via JDBC for customer, account, and transaction data.

6. **Reporting**:
   - **Statements**: Generates monthly statements for customers.
   - **Loan & Transaction Reports**: Summaries for admins.

7. **User Interface**:
   - **Console or GUI**: Basic console-based commands or Java Swing/JavaFX for a simple interface.

8. **Security**:
   - **Encryption**: Protects sensitive data.
   - **Audit Logs**: Tracks user activity for compliance.

### Technologies Used
- **Java Core, JDBC, JavaFX/Swing (for GUI)**, and **MySQL (database)**. 

This streamlined system covers the essential functions of bank operations, keeping the design simple yet effective.
