# Certificate-Dapp
 The application only uses a combination of client side scripting and Metamask wallet

Most of the steps are only reuired when runninig for the first time, please keep that in mind.

## Setting up the development environment 

Before we start we need some tools and dependencies. Please install the following:

1. Node.js and npm (comes with Node)
2. MetaMask Wallet

## Setting up MetaMask Wallet
1. Install MetaMask wallet to your browser.  
2. Connect to any test network (Rinkeby, Ropesten, Kovan etc..) and use the faucet to get test ether. 

## Compiling and deploying the smart contract.
Go to: http://remix.ethereum.org
1. Compile the contract
2. Connect to the MetaMask wallet using the Injected Web3 environment in remix and
deploy the contract


## Edit app.js
1. Provide deployed contract address in `javascripts\app.js (Line No.: 12, Veriable Name: contractAddress)`
2. Provide deployed contract abi in `javascripts\app.js (Line No.: 13, Veriable Name: contractAbi)`


## Installation
Install all other dependencies using following command: `npm install`

## Run Dapp
Execute the command: `npm start`



