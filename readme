MyToken Smart Contract

This is a simple Solidity smart contract for a basic  token, called MyToken. 
The contract allows for minting and burning tokens, making it suitable for learning and experimentation with Ethereum smart contracts.

Overview

This contract includes:
1. Public variables for token name, abbreviation, and total supply.
2. A mapping to track balances associated with each address.
3. Functions to mint and burn tokens, affecting both the total supply and individual balances.

Features

- Token Name: META
- Token Abbreviation: MTA
- Initial Supply: 0 (new tokens must be minted)

Functions

Public Variables

- tokenName: Stores the name of the token.
- tokenAbbrv: Stores the abbreviation for the token.
- totalSupply: Tracks the total token supply in circulation.

Mapping

- balances: Maps each address to its token balance.

Mint Function
solidity
function mint(address _address, uint _value) public

- Increases `totalSupply` by `_value`.
- Adds `_value` to the balance of `_address`.

Burn Function

solidity
function burn(address _address, uint _value) public


- Decreases `totalSupply` by `_value`.
- Deducts `_value` from `_address`'s balance.
- Checks that the `_address` balance is sufficient for the burn operation to prevent negative balances.

Usage

1. Mint Tokens: Use the `mint` function to create new tokens by specifying an address and a value to increase the balance of that address.
2. Burn Tokens: Use the `burn` function to reduce tokens, given that the address has a balance greater than or equal to the burn amount.
