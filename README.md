# Functions_and_Errors_ETH-AVAX 
In this I am creating a smart contract following the guidelines of module 1 of the project requirements.
Functionality
1. Contract successfully uses require()
2. Contract successfully uses assert()
3. Contract successfully uses revert() statement
   
## Description
Here I have created smart contract named LibraryManagement which is demonstrating the use of error handlers require(), assert(), and revert() statements.

### Code execution
For executing the code i have used remix ide [https://remix.ethereum.org/].
![image](https://github.com/Surbhi268/Eth-Avax-intermediate1/assets/138808811/1a10f333-7621-4c49-9627-b8024e22d60b)

### Code Explanation
This Solidity smart contract implements a library system with an owner who can register members and add books. Members with valid memberships can borrow available books, which are tracked using mappings. The `borrowBook` function uses `require` to ensure membership validity and book availability, and `assert` to confirm the book's status change. The `returnBook` function allows members to return books, updating their status and using `assert` to verify availability. The owner can revoke membership privileges if the member has returned all borrowed books, using `revert` to prevent revocation if books are still borrowed.
![image](https://github.com/Soyam2405/Functions_and_Errors_ETH-AVAX/assets/120269736/34922a7b-9436-4d13-81bb-a4daf012069f)
#### Execution steps on remix ide online
1. Firstly compile the written code on the remix ide.
   ![image](https://github.com/Soyam2405/Functions_and_Errors_ETH-AVAX/assets/120269736/8fe941a7-fff6-4da2-915e-9c8243c730a6)
2. Secondly check the version of solidity compiler must ensure it will be as per the code
   ![image](https://github.com/Soyam2405/Functions_and_Errors_ETH-AVAX/assets/120269736/3684b0a0-070b-4898-a511-decc54d90970)
3. Then deploy the code and test the reults under deploy and transcations field.
  ![image](https://github.com/Soyam2405/Functions_and_Errors_ETH-AVAX/assets/120269736/75a293f0-d1dd-44aa-9f51-d4114c53b387)

  ![image](https://github.com/Soyam2405/Functions_and_Errors_ETH-AVAX/assets/120269736/2277f431-32fb-425a-b57c-7524d2c03ad3)
## Authors
Soyam Kumar Gupta
email-[guptaji240504@gmail.com]
### License
Project is licensed under the MIT License
