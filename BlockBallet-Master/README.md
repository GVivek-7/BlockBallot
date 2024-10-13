# Web3 Voting Application

## Technologies, Frameworks, and Languages Utilized

- **Smart Contract**: Used to define the logic of the voting system on the Blockchain.
- **React**: Frontend framework for building the user interface of the application.
- **Truffle**: A development environment and testing framework for Ethereum smart contracts.
- **Ganache**: A local Ethereum blockchain used for testing the application.
- **MetaMask**: A browser extension that serves as a wallet for managing Ethereum-based transactions.
- **Ropsten Test Network**: A test Ethereum network used for deploying the smart contract.
- **Remix IDE**: An online editor for writing, compiling, and deploying smart contracts.

## [Live Application URL](https://web3-voting-app.netlify.app)

## Project Overview

Voting is a critical example of how Blockchain and Smart Contracts can be applied to real-world use cases. This Web3 Voting Application is designed to utilize Blockchain technology to ensure secure, transparent, and tamper-proof voting processes.

### Key Voting Principles

The Equal Justice Foundation outlines several principles that guide a secure voting process, including:

1. **Secret Ballot**: Ensuring voter privacy by keeping votes confidential.
2. **One Person, One Vote**: Every voter is allowed to vote only once, and the system reconciles the total number of votes to the eligible voter count.
3. **Voter Eligibility**: Only individuals who meet specific criteria are allowed to vote.
4. **Transparency**: The process is clear, rules are established, and the system is open to public review.
5. **Accurate Recording and Counting**: Votes are consistently recorded and tallied with results that can be audited.
6. **Reliability**: The system is resilient against errors, fraud, and security breaches.

This application implements all these principles in a Web3-based environment, allowing users to create polls or voting events and share the `contract address` with participants.

## How the Ballot Contract Upholds Voting Principles

### 1. Secret Ballot
The application only records wallet addresses and voter names. Each voter is recognized through their MetaMask wallet address. The votes are stored in a private array, ensuring that no one, apart from the ballot manager, can access individual voting details.

### 2. One Person, One Vote
The contract ensures that each participant can vote only once. Once a vote is cast, the voter's status is marked as "voted," preventing them from voting again.

### 3. Voter Eligibility
Only pre-registered MetaMask wallet addresses are permitted to vote. These addresses are added to the voters’ list before the voting process begins.

### 4. Transparency
Blockchain's immutability guarantees that each transaction and vote is permanently recorded. This transparency makes any form of manipulation nearly impossible.

### 5. Accurate Recording and Counting
The ballot goes through defined stages—from creation to opening for votes, and finally to closing and counting the results—ensuring a systematic process.

### 6. Reliability
Decentralization ensures that there is no single point of failure, as multiple nodes participate in maintaining the Blockchain.

## Application Features

### 1. Home Page
   - The main interface, featuring a menu accessible via a hamburger icon in the top-left corner.

### 2. Create Ballot
   - Enter the ballot name and proposal details, then deploy the smart contract using MetaMask.
   - Once the contract is deployed, add multiple choices and a list of eligible voters.
   - Only the listed voters can participate in the voting process, and after the voting starts, no modifications are allowed.

### 3. Voting Page
   - If you're the ballot creator, you won't be able to vote but can monitor and end the voting process.
   - Voters must enter the contract address to access the ballot. Once a vote is cast, it is irreversible.
   - Voting progress can be tracked in real-time, and the manager can close the ballot at any time.

### 4. Result Page
   - After voting ends, the results can be viewed by entering the contract address and clicking on the `Get Result` button.

## How to Use the Application

1. **Create a Ballot**: Start by creating a new ballot, deploy the contract, and define voting options and eligible voters.
2. **Voting Process**: Share the contract address with participants, who can then vote using their MetaMask wallet.
3. **View Results**: Once voting is complete, view the final results using the provided contract address.

## Conclusion

The Web3 Voting Application is a secure, transparent, and efficient solution for decentralized voting systems, fully utilizing the strengths of Blockchain technology.

**Developed by: Vivek Subramanian.G**

### Thank you for using the Web3 Voting Application!
