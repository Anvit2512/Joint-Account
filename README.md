BlockchainExpert - Bank Account With Multiple Approvals
This project provides a smart contract that allows for creating joint bank accounts. Each bank account can have up to 4 owners, each of which must approve any withdrawl of funds. As well as completed contract there is are automated test cases and a slim front-end applications that allows you to interact with some functionality of the contract. Please free to extend this project and add your own features and functionality.

Getting Started
To test and deploy the smart contract follow the steps below.

Install Node.js
Clone the repository: git clone https://github.com/Anvit2512/Joint-Account.git
cd Joint-Bank-Account
npm install
To test the contract run npx hardhat test
To deploy the contract to your localhost network do the following:
npx hardhat node
npx hardhat run --network localhost ./script/deploy.js
Using the Frontend
Install the Liveserver Extension in VSCode.
Open base.html
Click the button that says "Go Live" in the bottom right hand corner of your VSCode.
Import any accounts you need into MetaMask and change your MetaMask network to "Hardhat".
Interact with the contract!
