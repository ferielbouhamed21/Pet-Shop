# Pet-Shop

This project is a decentralized application (DApp) called Pete's Pet Shop, which is built using Solidity and JavaScript. It is designed to help manage pet adoptions efficiently on the Ethereum blockchain.

![image](https://github.com/ferielbouhamed21/Pet-Shop/assets/78966152/567e826c-9375-41e2-823b-828f19deb188)


## Features

- Efficient management of pet adoptions on the Ethereum blockchain.
- The store can accommodate 16 pets at a given time.
- Transactions are conducted in Ether (Gas).
- Associates Ethereum addresses with pets to be adopted.

Before getting started, make sure you have the following tools and dependencies installed:

## Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [NPM](https://www.npmjs.com/)
- [Truffle](https://www.trufflesuite.com)
- [Ganache](https://www.trufflesuite.com/ganache)
- [py-solc-x](https://pypi.org/project/py-solc-x/)
- [Metamask](https://metamask.io)
- [Google Chrome](https://www.google.com/chrome/) or [Firefox](https://www.mozilla.org/firefox)

## Getting Started

Follow these steps to get started with this project:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/ferielbouhamed21/Pet-Shop.git
2. Open [Ganache](https://trufflesuite.com/ganache/)
> Create new Workspace using `truffle-config.js`
3. Install project dependencies:

   ```bash
   npm install
4. 

 - Compiles contracts
 - Performs migrations 
    ```bash
    truffle migrate

 - Runs tests
    ```bash
    truffle test
5. Installing MetaMask
   Click on the link, and it will take you to the download page : 
<a href="https://metamask.io/" target="_blank"> Metamask </a>
6. Start the development server:
   ```bash
   npm run dev
7. Open your browser and navigate to http://localhost:3000 to interact with the DApp.


## Development

The project covers the following topics:

- Setting up the development environment
- Creating a Truffle project using a Truffle Box
- Writing the smart contract
- Compiling and migrating the smart contract
- Testing the smart contract
- Creating a user interface to interact with the smart contract
- Interacting with the DApp in a browser

## Testing

- To interact with the DApp, click the "Adopt" button corresponding to your selected pet.


![Screenshot 2023-10-20 202525](https://github.com/ferielbouhamed21/Pet-Shop/assets/78966152/a949694b-af1a-4177-8033-68bbda1c4baa)


- MetaMask will automatically prompt you to confirm the transaction. Click "Submit" to approve the transaction.


![picture_3](https://github.com/ferielbouhamed21/Pet-Shop/assets/78966152/248f8f69-7bd4-470b-995f-d432a0efb526)


- The "Adopt" button for the chosen pet will change to "Success" and become disabled, as specified, indicating that the pet has been successfully adopted. In MetaMask, you will find the transaction listed.


![Screenshot 2023-10-20 202410](https://github.com/ferielbouhamed21/Pet-Shop/assets/78966152/a368714f-17e6-47a5-a284-5eeaa8b5c1e6)


![picture_7](https://github.com/ferielbouhamed21/Pet-Shop/assets/78966152/e5fbd722-2190-4098-8c5e-246e43d4b9b4)


- You can also view the same transaction in the "Transactions" section within Ganache.


![image](https://github.com/ferielbouhamed21/Pet-Shop/assets/78966152/5889011d-d4fe-40e2-bd4e-2b23a32f9e92)


## Contributing

If you want to contribute to this project, feel free to open an issue or submit a pull request. We welcome contributions from the community.
