# Value Manager Dapp

This project demonstrates a simple Web3 application with a Solidity smart contract and a React.js frontend. The smart contract allows setting, incrementing, decrementing, and resetting a value.

## Project Overview

The project consists of:
- **Solidity Smart Contract**: Defines functions to manipulate a stored value.
- **Next.js Frontend**: Provides a user interface to interact with the smart contract.

## How to Run

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/web3-assessment-contract.git
   cd web3-assessment-contract
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Compile the Contract**

   ```bash
   npx hardhat compile
   ```
4. **Deploy the Contract**

     -Ensure Hardhat local node is running:
       ```bash
          npx hardhat node
       ```
     -Deploy the contract to the local node:
       ```bash
       npx hardhat run scripts/deploy.js --network localhost
       ```
     -Note the contract address from the deployment output.

6. **Configure the Frontend**

   Create a configuration file for the contract address:

     ```bash
       const CONTRACT_ADDRESS = "your_contract_address_here";
     ```

7. **Run the Frontend**

   ```bash
       npm start
   ```
