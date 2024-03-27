# Solidity Vault Readme
## Introduction
This project consists of two Solidity smart contracts:

ERC20: An implementation of the ERC20 standard token with basic functionalities such as transfer, approve, mint, and burn.
Vault: A smart contract that acts as a vault to deposit and withdraw ERC20 tokens while minting and burning corresponding shares.
ERC20 Contract
The ERC20 contract implements a basic ERC20 token with the following functionalities:

# Transfer tokens between accounts.
Approve spending tokens by another account.
Transfer tokens on behalf of another account.
Mint new tokens.
Burn tokens.
Vault Contract
The Vault contract provides a secure way to deposit and withdraw ERC20 tokens while maintaining a share-based system. Key features include:

Deposit: Users can deposit ERC20 tokens into the vault, receiving shares equivalent to their deposited amount.
Withdraw: Users can withdraw ERC20 tokens from the vault by providing the number of shares they wish to redeem.
Share Calculation: Shares are calculated dynamically based on the total supply and the current balance of ERC20 tokens in the vault.
Total Supply and Balance Tracking: The contract maintains the total supply of shares and the balance of shares for each user.
# Usage
ERC20 Contract
Deploy the ERC20 contract, specifying the initial parameters such as name, symbol, and decimals.
Use the provided functions to interact with the ERC20 token, including transfer, approve, mint, and burn.
Vault Contract
Deploy the Vault contract, providing the address of the ERC20 token to be used in the vault.
Deposit ERC20 tokens into the vault using the deposit function, which mints shares based on the deposited amount.
Withdraw ERC20 tokens from the vault using the withdraw function, specifying the number of shares to redeem for tokens.
