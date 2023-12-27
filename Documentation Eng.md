
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
    - Uses **Singkong** Version 8.3
    - Can Input Company Name and Fiscal Date.

- Version 1.2 (November 08, 2023)
    - Added a simple template feature for the Chart of Account and its table.
    - Added new, edit, and delete buttons that are not yet functional.

- Version 1.3 (November 11, 2023)
    - Uses **Singkong** Version 8.4.
    - Styling changes on the date picker for uniformity with other buttons.
    - Draft dialog for new account in the Chart Of Account, containing account type, account code, and description.

- Version 1.4 (12 November 2023)
    - Adjustment of variable names for mnemonics.
    - Proposed account code according to the new account type.
    - Reset button.

- Version 1.5 (13 November 2023)
    - Uses **Singkong** Version 8.5.
    - Alignment of account codes in the New Account dialog.

- Version 1.6 (17 November 2023)
    - Addition of a dialog on the new, edit, and delete buttons on the Chart Of Account table.

- Version 1.7 (20 November 2023)
    - Creation of a user interface for preparing the database connection.

- Version 1.8 (21 November 2023)
    - Creation of a test database connection that is functional.

- Version 1.9 (27 November 2023)
    - Uses **Singkong** Version 8.6.
    - Created a loop that will work when the database configuration is not available because the application cannot be used without a database configuration.
    - The application will exit the loop if closed with the save button or if the configuration is already available.
    - No grid added to the frame in setup.
    - Bug fix for fixing when you exit the app and can not login.

- Version 2.0 (December 3, 2023)
    - Addition of credits to the Bakwan application.
    - The 'Close' button in the database settings has been changed to 'Quit' and will now immediately close the application without requesting additional confirmation.
    - The frame closure confirmation is now only displayed if the connection to the database is successful, using configuration parameters from the configuration file.
    - Addition of a status bar displaying information about the database status, date, and time.

- Version 2.1 (December 5, 2023)
    - Database has been prepared (table creation and data entry) for authentication purposes.
    - Authentication process has been successfully implemented.

- Version 2.2 (December 11, 2023)
    - Uses **Singkong** Version 8.7.
    - Automatic updates on the database, such as adding rules of association between tables (foreign key).
    - Addition of a menu bar.
 
- Version 2.3 (December 14, 2023)
    - Update of several database versions for the Bakwan application.

 - Version 2.4 (December 18, 2023)
    - Change in the name of the account table in the Bakwan database, as account is a reserved keyword in one of the database systems.

 - Version 2.5 (December 20, 2023)
    - Bakwan Database can now execute 'Create,' 'Update,' and 'Delete' commands for Chart of Accounts.

## Application User Guide
 
1. Users can check whether the [**Java**](https://www.java.com/download/ie_manual.jsp) programming language is installed on their computer, as Singkong is an interpreter compatible with the Java programming language.

2. Users can download the latest version of  [**Singkong**](https://nopri.github.io/Singkong.jar) and [**Bakwan**](https://github.com/nopri/bakwan) application from the provided links.

3. Open **Singkong.jar** that has been downloaded from https://nopri.github.io/Singkong.jar.
   
4. Open file main.singkong downloaded from  https://github.com/nopri/bakwan. Then run the file.

5. The user will be notified that the database has been successfully initialized and provided with the **username** and **default password**. The user will also receive a message that the database has been successfully updated before being prompted to enter a username and password.

6. The user inputs the provided **username** and **password** earlier.

7. The user will be presented with two menus: "**File**" and "**Help**":

   - If the user chooses "**File**," additional options will be displayed, namely "**Setting**" and "**Quit**."

     - When the user selects "**Setting**," they will be presented with the "**Account Setup**" view, where the user can input the company name, determine the fiscal year, and make changes (add, edit, or modify) to the accounts.

     - When the user selects "**Quit**," they will exit the Bakwan application.

   - If the user chooses "**Help**," they will be presented with the "**About**" option.
  
8. In the Chart Of Account table, there will be ID, Type, Code, and Description. In this table, the user can:

   - Add an account with the "**New**" button, where they will be prompted to input the Account Type, Code, and Description.
   - To edit an account, the user must select the desired row and choose the "**Edit**" button, which will modify the desired parts of these three elements.
   - To delete an account, the user needs to select the desired row before using "**Delete**", and they will be asked for confirmation before proceeding.

9. Once finished, the user can press the "**Save**" button.

10. When done using the application, the user can press the "**Quit**" button in the "**File**" menu.

## Reference

- Epstein, L. (2007). _Bookkeeping Workbook_ For Dummies. Wiley.
