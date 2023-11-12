# My Token Project

## Table of Contents

- [Description](#description)
- [Installing](#installing)
- [Contract Details](#contract-details)
- [Functions](#functions)
- [Authors](#authors)
- [License](#license)

## Description

This repository contains the contract called myToken.sol

The `MyToken` contract provides a minimalistic ERC-20-like token. With myToken, we can mint, and burn tokens, view the number of tokens an address has and also view the name, abbreviation and total supply of the token available in the contract. Here are the details below:

- Token name: "SAMSON TOKEN"
- Token abbreviation: "SMT"
- Total supply
- Minting Function
- Burning Function

## Contract Details

- **Solidity Version**: 0.8.18
- **License**: MIT
  
## Installing
To deploy and interact with the `MyToken` contract, you can follow these steps:

1. **Clone the Repository**: Clone this repository to your local environment.

2. **Compile and Deploy**: Compile the contract using a Solidity compiler and deploy it to an Ethereum network of your choice. You can use development tools like Remix.

### Mint Function

- **Description**: Mint new tokens and add them to the total supply and the minter's address balance.
- **Parameters**:
  - `_address` (data type: address): The address of the account minting the tokens.
  - `_value` (data type: uint): The number of tokens to mint.
- **Visibility**: Public

### Burn Function

- **Description**: Burn a specific number of tokens from the sender's balance, reducing the total supply.
- **Parameters**:
- `_address` (data type: address): The address of the account burning the tokens.
- `_value` (data type: uint): The number of tokens to burn.
- **Visibility**: Public

## Authors
Samson Ajulor  
[@samsonajulor](https://twitter.com/samsonajulor)


## License
This project is learning purpose only.
