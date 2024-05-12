# DYield Farming Defi

The app aims to develop a DeFi app which can be used to implement concept of yield farming / liquidity mining

---
The following setups
- Configuring a blockchain.
- Developing smart contracts.
- Testing for the smart contracts developed
- Developing a client-side website so that users can actually use this application.
---

You can check the quick tutorial about "what is the blockchain?" in [here](https://ahmetozlu93.medium.com/blockchain-in-a-nutshell-8ad72743971e).

## Theory

### What is yield farming?

The main part of yield farming is a part which allows cryptocurrency holders to lock up their holdings, which in turn provides them with rewards.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/118402446-91963780-b672-11eb-9574-12e19fb789f9.png" | width=720>
</p>

## Application Software Architecture

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/104122166-729a3880-5354-11eb-9088-5123e47990d2.png" | width=720>
</p>

## Installation

### Setup

- **Node.js**

      sudo curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
      nvm install 12.18.3
      node -v

- **Truffle**

      sudo npm install -g truffle@5.1.39 --unsafe-perm=true

- **Ganache** installation guide can be found in [here](https://www.trufflesuite.com/ganache).

- **MetaMask** installation guide can be found in [here](https://metamask.io/).

### Commands

- Install necessarily Node.js packages

      npm install

- Deploy smart contracts to the Ethereum blockchain

      truffle migrate --reset
      
- Deploy and run the front-end application

      npm start run
      
- Run the scripts to issue tokens

      truffle exec scripts/issue-tokens.js