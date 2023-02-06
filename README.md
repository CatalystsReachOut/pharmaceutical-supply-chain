# Pharma-Chain :pill:

A supply chain for the safe distribution of medicines using Blockchain and AI.


## ✨ Motivation
<p align="justify">
At present, counterfeit drugs pose a serious threat as it is difficult for people to know the true value of purchased medicines due to a significant lack of transparency in the current system. Also, tampering within the supply chain is difficult to investigate when suspicion of illegal or unethical practices. 
</p>

## ⚡ Our Solution
<p align="justify">
Our solution is an amalgamation of two powerful technologies - Blockchain and AI. Blockchain is an open, distributed ledger that can efficiently record transactions between two parties in a verifiable and permanent way. Since blockchains are decentralized, distributed, transparent, and immutable, they can easily solve counterfeit medicines. AI in pharmacology helps improve customer service, loyalty and enables easy access to blockchain-based medical intelligence. 
</p>
<p align="justify">
This project proposes a system that uses blockchain and AI for the safe supply of medical drugs throughout the supply chain. Each product within the chain can be transferred between authenticated entities of the chain using an event request-response mechanism. All transactions between entities are recorded into the blockchain using smart contracts with the help of which a product can be traced to its source. We built a Rasa chatbot integrated into a Flutter app enabling ordering, tracing back medicines, and enhancing blockchain-based credit evaluation. A DApp was then developed using React Framework. The smart contracts were deployed on a local blockchain provided by Ganache. Using Web3.js and Truffle framework, DApp is connected to the blockchain. The experimental results show that our solution is feasible and comparatively more secure than existing systems.
</p>

## 💻 System Overview
<img src="assets/Blockchain Supply Chain.jpeg"/>

## 👀 Getting Started

### To deploy the Smart Contract

1. Install Ganache and create a workspace.
2. Install Truffle npm package globally by running ```npm install -g truffle```.
3. In the `truffle-config.js` file update the `from:` address to an address from your Ganache workspace.
4. Run ```truffle migrate --reset``` from the command line to deploy the smart contract to the blockchain.
5. Download Metamask Chrome extension for the browser to help interaction between the application and the blockchain.

### To run React development server

```bash
cd blockchain
npm install
npm start
```

### To run Node.js server
```bash
cd server
npm install
npm start
```



## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

[MIT License Link](https://github.com/sherwyn11/Pharma-Chain/blob/master/LICENSE)
