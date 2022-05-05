## Dependencies

First install required dependencies:

You'll need local ethereum node, I recommend `ganache-cli`. You can install it from npm.

```
npm install -g ganache-cli
```

Install truffle:

```
npm install -g truffle
```

Then install contract dependencies:  

```
npm install
```

Please install or have installed the following:

- [nodejs and npm](https://nodejs.org/en/download/)

**Functional specifications**

* Stake ERC20 tokens
* Unstake tokens
* Create own reward token (or use ETH or other ERC20 like DAI)
* Reward quantity should be proportional to the locked value in the smartcontract

**Requirements**

* Use Chainlink oracle

![screenshot](https://github.com/bhargava-krishna/yield-farming-dapp/blob/main/screen.jpg?raw=true)
