
# Double-Entry Bookkeeping Bakwan Application

Simple accounting software, written in [Singkong](https://github.com/nopri/nopri.github.io) programming language .


## Table Of Contents

  1. [What is *_Double-Entry Bookkeeping_* ?](#what-is-double-entry-bookkeeping)
  2. [Links](#links)
  3. [Development Phases](#development-phases)
  4. [Application User Guide](#application-user-guide)
  5. [Reference](#reference)


## What is *_Double-Entry Bookkeeping_* ?

**_Double-entry bookkeeping_**, also known as the double-entry or paired bookkeeping system, is a system of recording transactions in two aspects: debit and credit, always with a balanced orientation. Debits are recorded on the left, and credits on the right.

In double-entry bookkeeping, each transaction is recorded in two accounts, namely a debit account and a credit account. For example, if a company borrows Rp 3,000,000, the debit side will have a cash account of Rp 3,000,000, and the credit side will have a debt account of Rp 3,000,000. Debits and credits must balance. Double-entry bookkeeping also adheres to the formula that assets equal liabilities plus equity


## Links

- Singkong Programming Language : https://nopri.github.io/Singkong.jar
- Double-Entry Bookkeeping Bakwan Application : https://github.com/nopri/bakwan


## Development Phases

- Version 1.0 (October 30, 2023)
    - Uses Singkong Version 8.3
    - Can Input Company Name and Fiscal Date.

- Version 1.2 (November 08, 2023)
    - Added a simple template feature for the Chart of Account and its table.
    - Added new, edit, and delete buttons that are not yet functional.

- Version 1.3 (November 11, 2023)
    - Uses Singkong Version 8.4.
    - Styling changes on the date picker for uniformity with other buttons.
    - Draft dialog for new account in the Chart Of Account, containing account type, account code, and description.

- Versi 1.4 (12 November 2023)
    - Adjustment of variable names for mnemonics.
    - Proposed account code according to the new account type.
    - Reset button.

- Versi 1.5 (13 November 2023)
    - Uses Singkong Version 8.5.
    - Alignment of account codes in the New Account dialog.

- Versi 1.6 (17 November 2023)
    - Addition of a dialog on the new, edit, and delete buttons on the Chart Of Account table.

- Versi 1.7 (20 November 2023)
    - Creation of a user interface for preparing the database connection.

- Versi 1.8 (21 November 2023)
    - Creation of a test database connection that is functional.

- Versi 1.9 (27 November 2023)
    - Uses Singkong Version 8.6.
    - Created a loop that will work when the database configuration is not available because the application cannot be used without a database configuration.
    - The application will exit the loop if closed with the save button or if the configuration is already available
    - No grid added to the frame in setup.
    - Bug fix for fixing when you exit the app and can not login.


## Application User Guide
 
1. Users can check whether the [**Java**](https://www.java.com/download/ie_manual.jsp) programming language is installed on their computer, as Singkong is an interpreter compatible with the Java programming language.

2. Users can download the latest version of  [**Singkong**](https://nopri.github.io/Singkong.jar) and [**Bakwan**](https://github.com/nopri/bakwan) application from the provided links.

3. Open file main.singkong downloaded from  https://github.com/nopri/bakwan. Then run the file.
   
4. Users will be presented with the Account Setup interface, where they can fill in the company name, determine the fiscal year, and add, edit, or delete accounts

5. In the account table, there will be Type, Code, and Description. Users can :
     - **add** an account with the New button, where they will be prompted to fill in the Account Type, Code, and Description. 
     - To **edit** an account, users must select the desired row and choose the Edit button, which will modify the desired part of these three details. 
     - To **delete** an account, users need to select the desired row before using Delete.

6. Once finished, users can press the Save button.


## Reference

- Epstein, L. (2007). _Bookkeeping Workbook_ For Dummies. Wiley.