# Samson's Token Project

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Contract Overview](#contract-overview)
- [Functions](#functions)
- [Contributors](#contributors)
- [License](#license)

## Overview

Welcome to the Samson's Token project repository. In this repository, you will find the `myToken.sol` contract, which serves as the foundation for a versatile and customizable ERC-20-like token. It offers essential features, including token minting and burning, balance queries, and access to token details such as name, abbreviation, and total supply. Below, you'll find a brief summary of the key aspects of this token project:

- Token Name: "SAMSON TOKEN"
- Token Abbreviation: "SMT"
- Total Supply
- Minting Function
- Burning Function

## Contract Overview

- **Solidity Version**: 0.8.18
- **License**: MIT

## Installation

To deploy and interact with the `myToken` contract, follow these steps:

1. **Clone the Repository**: Begin by cloning this repository to your local environment.

2. **Compile and Deploy**: Use a Solidity compiler to compile the contract and deploy it to your chosen Ethereum network. You can leverage development tools like Remix for this purpose.

## Functions

### Minting Function

- **Functionality**: This function enables the creation of new tokens and the addition of these tokens to both the total supply and the minter's address balance.
- **Input Parameters**:
  - `_address` (Type: address): It represents the address of the account responsible for the minting operation.
  - `_value` (Type: uint): This parameter signifies the quantity of tokens to be minted.
- **Visibility**: Public

### Burning Function

- **Functionality**: This function allows for the reduction of the total supply by burning a specified number of tokens from the sender's balance.
- **Input Parameters**:
  - `_address` (Type: address): It denotes the address of the account initiating the token burning.
  - `_value` (Type: uint): This parameter specifies the quantity of tokens to be burned.
- **Visibility**: Public

## Contributors

- Samson Ajulor  
  [Twitter: @samsonajulor](https://twitter.com/samsonajulor)

## License

This project is intended for educational and learning purposes only.
