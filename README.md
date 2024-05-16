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

The mint function creates new tokens and assigns them to the specified address.

Parameters:
_address: The address to which the newly created tokens will be assigned.
_value: The number of tokens to be created.

```

### burn

```solidity
function burn(address _address, uint _value) public

The burn function destroys existing tokens from the specified address.

Parameters:

_address: The address from which the tokens will be burned.
_value: The number of tokens to be burned.
Conditions:

The address must have a balance greater than or equal to the number of tokens to be burned.






