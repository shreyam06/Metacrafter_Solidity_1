# Metacrafter_Solidity_1
MyToken Contract
This Solidity contract implements a basic ERC20 token named META (MTA). It provides functionality to mint and burn tokens.

Requirements
Public variables storing details about the token (Token Name, Token Abbreviation, Total Supply).
A mapping of addresses to balances.
A mint function to increase the total supply by a specified amount and increase the balance of a given address.
A burn function to decrease the total supply and deduct tokens from a given address.
The burn function includes conditionals to ensure that the balance of the address is sufficient for burning tokens.
Usage
Deployment
You can deploy this contract on any Ethereum-compatible blockchain network.

Minting Tokens
To mint new tokens, call the mint function with the recipient's address and the amount of tokens to be minted.

Burning Tokens
To burn tokens, call the burn function with the address from which tokens will be burned and the amount to be burned. The function will check if the address has a sufficient balance before burning.

Viewing Token Details
You can access the public variables tokenName, tokenAbbrv, and totalSupply directly from the contract.
