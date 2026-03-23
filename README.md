Crypto Wallet Decentralized Application


Project Overview
A decentralized application that allows users to deposit Ether into a smart contract and enables the contract owner to send funds to other addresses. The application includes a Solidity smart contract deployed on Sepolia testnet and a web interface that connects via MetaMask.

Live Demo
https://YOUR-USERNAME.github.io/CryptoWallet/

Requires MetaMask extension and connection to Sepolia test network.

Completed Features
MetaMask Integration
Users can connect their wallet to the application.

Deposit Ether
Any user can send Ether to the smart contract.

Send Ether
Only the contract owner can transfer Ether to another address.

Balance Display
The contract balance is shown and auto-refreshes every ten seconds.

Transaction Status
Visual feedback is provided during deposit and send operations.

Responsive Interface
The layout works on desktop and mobile devices.

Technology Stack
Solidity 0.8.31
HTML5, CSS3, JavaScript
Web3.js
MetaMask
GitHub Pages
Remix IDE

Smart Contract
Contract Address: 0xYOUR_CONTRACT_ADDRESS_HERE
Network: Sepolia Testnet

Functions:
receive – Accepts incoming Ether
sendMoney – Owner sends Ether to any address
getBalance – Returns contract balance
owner – Returns contract owner address

Usage
Connect Wallet
Click Connect MetaMask and approve the connection.

Deposit
Enter amount and click Deposit. Confirm in MetaMask.

Send (Owner Only)
Enter recipient address and amount. Click Send and confirm.

Check Balance
View balance on screen. Click Refresh Balance or wait for auto-refresh.

Deployment
Frontend
Hosted on GitHub Pages. The index.html file is served directly from the repository.

Smart Contract
Deployed using Remix IDE to Sepolia testnet via MetaMask.

