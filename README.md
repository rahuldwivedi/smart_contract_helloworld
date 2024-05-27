# Smart Contract Hello World

This repository presents practices about:

- Setup a blockchain.
- Develop Ethereum smart contract.
- Deploy the contract and test it.

## Quick Demo

First, clone the repository and build the project using truffle by this command:

    truffle build

After building the project and starting ganache which provides ethereum blockchain network on your local, our smart contract can be deployed using truffle by this command:

    truffle migrate

Now, our smart contract has been built and deployed so we can perform test on it by these commands respectively:

    var hw;
    Main.deployed().then(function(d){hw = d;});
    hw.setUserName("Rahul")
    hw.printMessage.call() // prints Hello Rahul!


## Installation

### Setup

- **Truffle**

      sudo npm install -g truffle@5.1.39 --unsafe-perm=true

- **Ganache** installation guide can be found in [here](https://www.trufflesuite.com/ganache).


