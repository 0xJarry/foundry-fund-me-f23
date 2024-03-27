# FundMe Contract

This repository contains a Solidity smart contract for funding Ethereum addresses and converting the received Ether to USD using Chainlink's price feed. The contract includes two main components: `FundMe` and `PriceConverter`.

## FundMe.sol

### Variables
- `i_owner` is an immutable address that represents the owner of the contract who can withdraw funds from it after deployment.
