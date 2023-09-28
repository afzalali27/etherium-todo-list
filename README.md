
## Ethereum Todo List

This project is a smart contract-based task manager. It allows users to create tasks, mark them as completed, and view their tasks.

## Prerequisites
  - Ganache - Local blockchain emulator
  - Metamask - Chrome extension for dummy wallet manager
  - Truffle - A development framework for Ethereum that simplifies the process of creating, testing, and deploying smart contracts. It provides tools and configurations for smart contract development.


## Installation

To install the project dependencies, run the following command:

```
npm install
```

## Usage

Connect Metamask with Ganache by adding local network providing RPC url and ChainId (default 1337) then import Ganache account by providing public address

To run the project, use the following commands:

```
truffle compile
truffle migrate
npm run dev
```

This will start the lite-server and open the project in your default browser.

## Functionality

The main functionality of the project includes:

- Creating tasks
- Marking tasks as completed
- Rendering tasks

