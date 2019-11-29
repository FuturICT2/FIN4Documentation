Getting started
===============

Digital Wallet
^^^^^^^^^^^^^^

**FIN4Xplorer** consists of two parts:

- Smart contracts that are deployed to the `Ethereum network <https://ethereum.org/>`_ - the `Rinkeby test network <https://www.rinkeby.io/>`_ for now. The entire functionality is in these smart contracts. Everything could also be done by interacting with them via a command line.
- A "frontend" in the form of a *Web DApp* that acts as an user interface for convenient interaction with said smart contracts. Web apps run directly in the browser, both on desktop computers and on smartphones. DApp stands for distributed app, meaning it runs on a blockchain.

The only, yet significant, difference a visitor of a Web DApp experiences compared to a Web App, is the need for a "bridge to the blockchain". Also called a digital wallet. Its first task is to establish the connection to the blockchain network - either via a `full node <https://docs.ethhub.io/using-ethereum/running-an-ethereum-node/#full-nodes>`_ that users run themselves or via a gateway service like Infura. Its second task is to pop up whenever the user seeks to write data to the blockchain and enable the convenient signing of such transactions with the users private key.

There are many organizations and projects out there offering digital wallets in different stages of maturity and compatibility. While the trend goes towards deeper and native integration into browser (or even operation systems), for now the market appears scattered.

The digital wallet we are using ourselves, and that seems to be the currently best supported one out there, is MetaMask: `metamask.io <https://metamask.io/>`_. MetaMask is available both as extension for desktop browsers (Chrome, Firefox, Opera and Brave) and as early-stage mobile app (iOS and Android).

Once you have a digital wallet, either restore an existing account or follow the process to create a new account. In most digital wallets, creating a new account involves the randomized mathematical creation of a new and unique mnemonic (also called "seed phrase"). From this, one or more accounts, each with a public address and a matching private key, can be derived deterministically. Meaning you only have to remember/store (the digital wallet will probably remind you thoroughly to do so) the mnemonic to restore your account(s) anytime on any machine. Usually only the first account per mnemonic will be used.

After having created your new account, don't forget to switch to the *Rinkeby Test Network*. By default you will be on the *Main Ethereum Network*.

Ether
^^^^^
TODO
How to get Ether
