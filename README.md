
<p align="center">
  <img src="https://user-images.githubusercontent.com/16810128/36881745-df9c599a-1e23-11e8-9ea3-58d4730bd537.jpeg">
</p>

Tutorial: [How to issue your own token on Ethereum in less than 20 minutes](https://medium.com/bitfwd/how-to-issue-your-own-token-on-ethereum-in-less-than-20-minutes-ac1f8f022793)

This tutorial will take you through the steps of issuing your first ERC20 token on the Ethereum network using a single smart contract and MyEtherWallet.

This repo contains the sample solidity file: 
```
contracts/erc20_tutorial.sol
```

THIS IS A MODIFIED FORKED REPO
This file was modified so the contract is based on limit of supply, and added bonus tokens for the first people who acquire them. The first round of tokens have a conversion of 1ETH for 10,000BC, until 100 million tokens are supplied. The second round has a conversion of 1ETH for 5,000BC, until 500 milion tokens are supplied. Finally, the third round has a conversion of 1 ETH for 2,000BC, until the supply limit is reached, where there would be no more tokens available. The only thing yet to fix is that if the final person who trades ethereum just before the supply limit is reached, and will be surpassed by its value, the person will recieve tokens above the supply limit according to how much was sent.
