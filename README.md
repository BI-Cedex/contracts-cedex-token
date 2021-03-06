# CEDEX Coin Smart Contract
## Overview
CEDEX is the First Ever Certified Blockchain Based Diamond Exchange

CEDEX.com is a global exchange that focuses on bridging the gap between the traditional diamond industry and the innovative financial markets. With its extensive industry knowledge, CEDEX wants to engineer a ground-breaking change – enabling people to liquidate and invest in diamonds like any other financial asset, in a transparent and secure way.

The CEDEX exchange enables anyone to invest in individual diamonds, shares of a high- value stone or shares in a basket of diamonds (ETF).

Investors, buyers and sellers are confident because the diamond value is transparent, using the DEX, our machine learning algorithm and blockchain technology that rates a diamond’s asking price, liquid because it creates a two- sided market by enhancing both the supply and demand, and fungible because CEDEX creates a unique benchmark value, rate and contract for every stone.

CEDEX was founded by a group of experienced veterans from the FinTech, diamond, financial and online industries, all of whom have extensive industry knowledge.

Become part of one of the most revolutionary changes in the financial industry in centuries – enabling people to finally invest in diamonds like any other commodity.

For more information, visit the [website](https://www.cedex.com) and read the CEDEX [Whitepaper](https://cedex.com/img/Whitepaper.pdf).

## About the coin
The CEDEX exchange will be powered by the CEDEX coin. This ERC-20 compitable token (source code of the contract you can find here) will be traded over the public Ethereum blockchain and will allow users to purchase diamonds on CEDEX, transforming their assets into diamonds. 
Use of the CEDEX coin will be the driven by trading volumes generated on the CEDEX Exchange and the demand of the diamond of the diamond ecosystem.
The CEDEX coin will be the only means of payment used on the CEDEX exchange. The amount of CEDEX coin is limited to 100,000,000. Any coins offered for sale that are not sold will be burned

### CEDEX Coin Requiremets
1. Standard ERC20 "CEDEX Token" with symbol "CEDEX", 18 decimals and total supply of 100,000,000 units created at contract deployment and assigned to a specific wallet.
2. 50,000,000 tokens are assigned for the public token sale
3. Up to 25,000,000 of the tokesns will be sold in the pre-sale and the reminder in the sale.
4. Up to 15,000,000 of the tokens will be given as bonuses for pre-sale and early sale participants.  
5. 15,000,000 tokens are assigned for the Founders, team and advisory board. 18 month vesting period for them (10% vested after end of sale, 30% after 6 months, 30% after 12 months and 30% after 18 months)
6. 15,000,000 tokens are assigned for the company and be used in the future for: development and marketing expansion or for diamond purchases to facilitate future financial instruments offered on CEDEX and for operational costs
7. At the end of the token sale, any unsold tokens will be burned 
8. Tokens are distributed to users up to three weeks after the sale ends. Once they are distributed, they are transferable. 
9. Value of 1 CEDEX coin will not exceed $0.8. The hard cap of Token-Sale will be published in ETH, prior to the Token-Sale on March 10,2018 08:00 GMT, CEDEX will be locking and publishing the final ETH amount to be sold in the Token-sale
10. It should be possible to set a vesting period to tokens while sending them to an ICO contributor 
11. 18 month vesting period for the Founders, team and advisory board (10% vested after end of sale, 30% after 6 months, 30% after 12 months and 30% after 18 months)

### Installing
This was developed using Node 8.4.0, Truffle 3.4.11.

```
npm install -g truffle
npm install
git clone https://github.com/Cedex-Diamond-Exchange/contracts-cedex-token.git
cd ICO
npm install zeppelin-solidity
truffle compile
```

### Testing
To run the tests, simply run

```
truffle test
```

### Composition of the repo
The repo is composed as a Truffle project. The test suite can be found in `test` folder. The contract is in `contracts/Cedex.sol`. The deployment scripts are in the `migrations` folder.

### Built With

* [Truffle](http://truffleframework.com/) - The most popular development framework for Ethereum
* [OpenZeppelin](https://openzeppelin.org/) -  Open framework of reusable and secure smart contracts in the Solidity language.
* [Style Guide](http://solidity.readthedocs.io/en/develop/style-guide.html) - Coding conventions for writing solidity code.

## Audit
Contract verified by [Oceanico](http://www.oceanico.io/)
It implements all methods from ERC-20 standard and is ready for usage on blockchain platforms
For more information, and review of the smart contract audit [report](https://github.com/Cedex-Diamond-Exchange/contracts-cedex-token/blob/master/Cedex_Auditing.pdf)

