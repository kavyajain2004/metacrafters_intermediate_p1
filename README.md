# Error Handling in Solidity

This Solidity smart contract, named Account, is designed to manage account balances in a secure and robust manner.
It includes methods for depositing and withdrawing funds while addressing potential overflow and underflow vulnerabilities.
It include require(),assert() and revert() function.

## Description

This Solidity project employs the require, assert, and revert functions to implement a secure fund management system. The smart contract, named Account, features functions for depositing and withdrawing money while actively safeguarding against underflow and overflow conditions

## Getting Started

### Installing

Ensure you have Solidity installed on your system. This project uses version 0.8.20. Follow the official installation guide for Solidity installation.s

## Features
# Deposit Funds
The deposit function allows users to add funds to their account balance. It safeguards against overflow vulnerabilities by validating that the new balance is greater than or equal to the old balance.

# Withdraw Funds
The withdraw function enables users to remove funds from their account, ensuring that the balance is sufficient to cover the requested withdrawal. It also protects against potential underflow issues.



## License

This project is licensed under the MIT License.
