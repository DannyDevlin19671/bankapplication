# 🏦 Student Group Programming Task: Basic Banking App

## Scenario

Your team is working for a new digital bank. You’ve been asked to design a simple banking system that allows customers to create accounts, deposit and withdraw money, and keep track of their transactions.

---

## Classes Required

- **Bank**
- **Customer**
- **Account**
- **Transaction**

---

## Team Roles & Individual Responsibilities

Split your group so that each member is responsible for implementing and testing one of the main classes. You must work together to ensure your classes interact properly.

### 1. Bank Class (Team Lead)

- Manages all customers and accounts.
- Allows creating new customers and accounts.
- Can find a customer or account by ID.
- Keeps a list of all transactions.
- *Stretch:* Can generate a summary report of all accounts and their balances.

### 2. Customer Class

- Stores customer details (name, unique ID, list of accounts).
- Can request to open a new account.
- Can get a list of all their accounts and balances.

### 3. Account Class

- Stores account details (account number, type, balance, transaction history).
- Can deposit and withdraw money (validates sufficient funds).
- Records all transactions to the transaction history.

### 4. Transaction Class

- Represents a single transaction (amount, type [deposit/withdrawal], date/time, transaction ID).
- Can generate a summary/statement line.

---

## Requirements

- **Interaction:** Classes must use constructors, getters, setters, and relevant methods to interact.
- **Testing:** Each member must write a main/test method to demonstrate their class works, and then run integrated tests as a group.
- **OOP Principles:** Apply encapsulation, use of collections (e.g., ArrayList), and `toString` for useful output.
- **Documentation:** Each member should comment their code and write a short summary of their class and its methods.

---

## Extension Ideas (Optional)

- Add account types (savings, checking).
- Implement account-to-account transfers.
- Add interest calculation for savings accounts.
- Create a simple text-menu interface for demo.

---

## How to Submit

- Each member commits their class with comments and a test file.
- As a team, provide a README explaining the architecture and how to run the program.
