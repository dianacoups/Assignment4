## Assignment 4
* `Diana Imambekova`
* `David Novikov` 
* `Madina Salen` 
* `Temirlan Kabdikarim` 

### Description:
This README provides a step-by-step guide to creating a basic staking smart contract in Solidity and building a dApp to interact with it. The staking contract allows users to stake tokens, earn rewards, and withdraw their staked tokens.

## Task Steps
### Step 1: Set Up Your Development Environment
Use Hardhat to set up your development environment.

### Step 2: Define the Smart Contract
Define the staking smart contract with basic properties and functions for staking, calculating rewards, distributing rewards, and withdrawal.

### Step 3: Implement Staking Functionality
Implement the staking logic in the `stake` function, allowing users to stake tokens and recording staking start times.

### Step 4: Calculate Rewards
Create a `calculateRewards` function to compute rewards based on staked amounts and the staking period.

### Step 5: Distribute Rewards
Implement the `distributeRewards` function to distribute rewards to stakers at the end of each staking period.

### Step 6: Withdrawal Function
Create a `withdraw` function that allows users to withdraw their staked tokens and earned rewards.

### Step 7: Testing and Deployment
Test your contract using Hardhat and deploy it to a testnet for interaction with a dApp.

### Step 8: Building a Frontend
Consider building a user-friendly frontend using web development technologies (HTML, JavaScript, React, etc.) for users to interact with the staking smart contract.

## Actions Taken
Here's a summary of the steps and actions taken in creating the staking smart contract and dApp:

1. Created a new app using the NPM library and ThirdWeb source.
2. Installed Chakra-UI for building the frontend part of the dApp.
3. Connected a wallet to the ThirdWeb service.
4. Set up a regular token contract.
5. Deployed the StakeToken contract with specified parameters.
6. Minted tokens for StakeToken.
7. Deployed a token contract for rewards and minted RewardTokens.
8. Deployed the Stake contract using ERC20 token contracts.
9. Deposited some RewardTokens to the ERC20Stake token for approval.
10. Created a dApp structure using NPX and ThirdWeb.
11. Specified the Goerli testnet and Chakra-UI as the framework.
12. Specified the constant addresses of tokens and contracts.
13. Edited and customized the dApp pages.
14. Built a navbar component using Chakra-UI for wallet connection functionality.

