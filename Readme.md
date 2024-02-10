# Vault and Token contract
These smart contract, allows users to deposit and withdraw ERC20 tokens while maintaining a share-based system. Users deposit tokens to mint shares and can later withdraw tokens by burning shares. The Erc20 allows for the transfer, minting, approval, and burning of token"

## Usage
- Deploy the Vault contract, providing the address of the ERC20 token to be used.
- Users can deposit tokens using the deposit function, minting shares based on the deposited amount.
- Users can withdraw tokens using the withdraw function, burning shares based on the withdrawn amount.

## Vault Functions
- _mint: Private function to mint shares for a given address.
- _burn: Private function to burn shares for a given address.
- deposit: External function allowing users to deposit tokens, minting shares accordingly.
- withdraw: External function allowing users to withdraw tokens, burning shares accordingly.