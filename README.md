# Owner.sol Deployment 

This repository contains the deployment of the Owner.sol smart contract to:

* Sepolia Testnet

* Lisk-Sepolia Testnet

* Arc Testnet

The contract was deployed using both:

* Foundry

* Hardhat

## Contract Overview

Owner.sol is a simple smart contract that demonstrates ownership logic.

Main features:

* Stores the contract owner

* Restricts certain functions to only the owner

* Allows ownership verification

## Deployment Details
### Sepolia Testnet

Foundry Deployment Address:
0x52E1f9f6AE17af16a362037C44D66F66BE21f548

Hardhat Deployment Address:
0x9E87f1be826ccEC0e32217a27dC6C9ffBC39fE18

### Lisk-Sepolia Testnet

Foundry Deployment Address:
0x7096C8FD97a399ec59C8DF7055329223821b46F1

Hardhat Deployment Address:
0xc14d1eE6daCfe757cef570B339Ff8Ea7084bf354

### Arc Testnet

Foundry Deployment Address:
0x7096C8FD97a399ec59C8DF7055329223821b46F1

Hardhat Deployment Address:
0xc14d1eE6daCfe757cef570B339Ff8Ea7084bf354

## Tech Stack

* Solidity

* Foundry

* Hardhat

* Node.js

* Alchemy / RPC Providers

## Project Structure
```
├── foundry/
│   ├── script/
│   ├── src/
│   └── foundry.toml
│
├── hardhat/
│   ├── contracts/
│   ├── scripts/
│   └── hardhat.config.js
│
└── README.md
```

## How to Deploy
### Using Foundry
```
forge script script/Owner.s.sol \
--rpc-url <RPC_URL> \
--private-key <PRIVATE_KEY> \
--broadcast \
--verify
```

### Using Hardhat
```
npx hardhat ignition deploy ignition/modules/Owner.ts --network <network-name> --verify

```

## Submission Requirements

* Deployed on Sepolia
  
* Deployed on Lisk Sepolia

* Deployed on Arc Testnet

* Used Foundry

* Used Hardhat

* All contract addresses included in this README
