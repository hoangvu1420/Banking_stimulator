# Bank stimulator program

**This is a program that simulates the banking system with some simple functions that demonstrate some of the functions of a savings account at a bank. The program is written using the C++ programming language and uses a basic console input/output interface.**

## Structure

- The program uses a linked list data structure to store account information. Each account will include account number, password, username, ID number, account balance, balance fluctuations history, current account status, account creation date.

- Each record in the balance fluctuations history including 
- There are 3 main functions in the operation of the program

## Functions

### 1. Login

- Log in to an existing account or creating a new account.
- Too many false log in attempts will lead to account being locked.
- A new account will have an account number being randomly generated.

### 2. Transfer

- There are 2 kinds of tranfer: deposit and withdraw.
- Every time an account perform a transaction, the detail of the transaction will be store in the transaction history of the account (bdsd).
- Cannot withdraw an amount of money that greater than the current balance of the account.

### 3. Information

- Display all informations of the current account including base informations and balance fuctuation history of the account.

## Demonstration
- The features and funtions of the application are shown in this video [Demo video](https://husteduvn-my.sharepoint.com/:v:/g/personal/vu_hn215171_sis_hust_edu_vn/EZ0BqyzvfuNFvkUeXXCmk_kBm41q6tQMxNSzsbtevmXTbA?e=Yba6x8)