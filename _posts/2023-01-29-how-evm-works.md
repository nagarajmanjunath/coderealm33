---
layout: post
title: "How EVM works"
categories: [blockchain]
image: assets/images/evm.png
---

The Ethereum Virtual Machine (EVM) is the runtime environment for smart contracts on the Ethereum blockchain. It executes the code of smart contracts on the Ethereum network and is responsible for enforcing the rules set by the contract.

Here's how the EVM works:

Code Deployment: Smart contracts are written in Solidity or another programming language supported by the EVM and are deployed to the Ethereum network. Once deployed, the contract code is stored on the blockchain and is accessible by anyone.

Contract Invocation: When a contract is invoked, the EVM executes its code. The contract can receive input data, access and modify its own storage, and interact with other contracts on the Ethereum network.

Gas: Every action performed by the EVM, such as executing a function or accessing storage, requires a certain amount of gas, which is a measure of the computational effort required to perform the action. The cost of gas is paid in Ether, the native cryptocurrency of the Ethereum network.

State Changes: As the EVM executes the code of a smart contract, it changes the state of the contract. The state includes the contract's storage, the balance of its associated Ethereum account, and any other data associated with the contract.

Consensus: The EVM is executed by every node in the Ethereum network, and the state changes made by the EVM are reflected in the global state of the Ethereum blockchain. The EVM is responsible for enforcing the consensus rules of the Ethereum network, ensuring that the state changes made by the EVM are valid and irreversible.

In conclusion, the EVM is a crucial component of the Ethereum network, providing a secure and efficient runtime environment for smart contracts. The EVM enables developers to build and deploy decentralized applications on the Ethereum network, and provides a platform for executing and enforcing the rules of these applications.
