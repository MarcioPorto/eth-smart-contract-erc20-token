# OpenZeppelin ERC-20 Token (Truffle Tutorial)


[This code follows the tutorial found [here](http://truffleframework.com/tutorials/robust-smart-contracts-with-openzeppelin).

First things first, ensure that you have OpenZeppelin installed. If not, run:

```
npm install zeppelin-solidity
```

Start a local development instance of the Ethereum network using something Ganache and run:

```
truffle compile
truffle migrate
```

To access the frontend app from your web browser, make sure you have Metamask set up to use your local environment accounts and running on a private network. Then run:

```
npm run dev
```