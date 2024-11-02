# Crypxange - Web 3.0 Blockchain Transaction Application

![Crypxange](https://i.ibb.co/DVF4tNW/image.png)

### Overview

Crypxange is a Web 3.0 application that enables users to conduct transactions using the Sepolia Ethereum test network. Leveraging Solidity, Hardhat, and MetaMask, Crypxange demonstrates the foundational elements of blockchain applications. This project serves as both a learning tool for blockchain development and as a basic, functional transaction platform.

## Features

- **Connect Wallet**: Use MetaMask to connect to the Ethereum blockchain and interact with SepoliaETH.
- **Send Transactions**: Send Ethereum between addresses with optional messages and keywords.
- **Transaction History**: View past transactions with details such as sender, receiver, timestamp, message, and amount.

## Technologies Used

- **Solidity**: Smart contract development for managing transaction logs on the blockchain.
- **React & Web3**: Provides a modern interface for seamless user interaction with the blockchain.
- **ethers.js**: JavaScript library for Ethereum blockchain interaction.
- **MetaMask**: Wallet integration for easy blockchain access.

## Running the Project Locally

### Requirements

1. **Node.js and npm**: To install and manage dependencies.
2. **Hardhat**: For smart contract testing, deployment, and management.
3. **MetaMask**: Browser extension for Ethereum wallet integration.

### Installation Steps

1. **Clone the Repository**:
    git clone https://github.com/yourusername/crypxange.git
    cd crypxange
    

2. **Install Dependencies**:
    npm install
    

3. **Compile the Smart Contract**:
    npx hardhat compile

4. **Deploy the Contract on Sepolia**:
   - Set up the `hardhat.config.js` to connect to the Sepolia test network.
    npx hardhat run scripts/deploy.js --network sepolia
    

5. **Run the Application**:
    npm start





## Project Structure

- **contracts/Transactions.sol**: Contains the Solidity contract for transaction management.
- **src/context/TransactionContext.js**: React context for managing Ethereum connection and transaction functions.

## Getting Started with Web 3.0

This project illustrates a basic but real-world application of Web 3.0, guiding you through using Solidity and MetaMask to build decentralized applications on Ethereum. You’ll learn the fundamentals of blockchain interactions, transaction handling, and front-end integrations.

## Credits

Project built with resources from JS Mastery.

