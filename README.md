DegenToken
Simple overview of use/purpose
DegenToken is an ERC20-compliant token with additional functionalities for minting, burning, transferring, and redeeming items. It is designed to be used in a decentralized application where users can interact with the token and redeem it for NFTs.

Description
DegenToken is a smart contract implemented in Solidity that leverages the OpenZeppelin library for secure and modular development. The token supports standard ERC20 operations, along with custom features that allow users to mint, burn, transfer, and redeem tokens for items. This project includes deployment and configuration scripts using Hardhat, a development environment for Ethereum.

Getting Started
Installing
Clone the repository
git clone <repository-url>
cd <repository-folder>
Install dependencies

npm install

Executing program
Compile the contract

npx hardhat compile
Deploy the contract


npx hardhat run scripts/deploy.js --network volta
Replace volta with localhost, fuji, or mainnet depending on your deployment target.

Interact with the contract

Use Hardhat's console to interact with the deployed contract

npx hardhat console --network volta
Help
For common issues, consider the following steps:

Compilation errors: Ensure that all dependencies are installed and the Solidity version in your contract matches the version specified in hardhat.config.js.
Deployment issues: Verify that your environment variables are correctly set and that you have sufficient funds for gas fees.
Interaction problems: Check that the contract address is correctly specified and the network configurations are accurate.
To get detailed help information, run:


npx hardhat help
Authors
Annu
Dominique Pizzie - @Annu1603
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
