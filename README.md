This `README.md` provides an overview of the `MyToken` contract, explains its features and functions, and includes instructions for deployment and interaction.

# MyToken

MyToken is a simple ERC20-like token contract implemented in Solidity. This contract allows for minting and burning tokens, and keeps track of the total supply and individual balances.

## Features

- Public variables for the token name, abbreviation, and total supply.
- Mapping to track balances of addresses.
- Mint function to create new tokens.
- Burn function to destroy existing tokens.

## Contract Details

- **Token Name:** FLORENCE
- **Token Abbreviation:** FLO
- **Compiler Version:** 0.8.18
- **License:** MIT

## Functions

### mint

```solidity
function mint(address _address, uint _value) public
