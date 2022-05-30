# Dcloud
Dcloud is decentralized application to store our data on cloud

For storing files and data online, most of us use cloud services provided by an central authority. We have to buy storage space in bulk and want to make payment regularly to access and store our data. As datas are stored in central system. there is a chance o loosing our data in case of a failure in the system and our data could be manipulate.
Dcloud provide sollutions to this problems. Our data can be stored securely in blockchain and it is immutable and no one can manipulate our datas. And payment need to be done only once. We use Filecoin to store the data, and the hash is stored in mumbai(polygon testnet)which runs on ethereum evm. Now everyone is able to upload their files in blockchain with ease.



## Tech Stack Used

- Solidity
- Truffle Suite
- ethereum
- web3.storage - IPFS and Filecoin
- Openzeppelin contracts
- ReactJS
- polygon
- mumbai testnet

## Dcloud Smart Contract Deployment


## Run Locally

### Pre-Requisites

- Truffle Suite
- Ganache CLI

```
$ npm install -g truffle
$ npm install -g ganache-cli
```  
Clone the project

```
$ git clone https://github.com/gp11gp11/Dcloud
$ cd Dcloud
```
### Setting up a local Blockchain
Install dependencies

```
$ npm install
```

Compile Smart Contracts

```
$ truffle compile
```

Run ganache

```
$ ganache-cli
```  

Run migrations to deploy the smart contracts

```
$ truffle migrate
```  

### Setting up the client

Start the App

```
$ npm start
```

Visit https://localhost:3000/ to view the app


## Running Tests

To run tests, run

```
  truffle test
```
