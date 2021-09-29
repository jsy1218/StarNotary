# ND1309 C2 Ethereum Smart Contracts, Tokens and Dapps - Siyu Jiang Complete
**PROJECT: Decentralized Star Notary Service Project** - I created a StarNotary DApp, and deployed to Rinkeby test network.


### Dependencies
1. **Truffle** 
```bash
# I'm using version v5.4.12
truffle version
JanettekiMacBook-Pro:nd1309-p2-Decentralized-Star-Notary-Service-Starter-Code janet$ truffle version
Truffle v5.4.12 (core: 5.4.12)
Solidity v0.5.16 (solc-js)
Node v14.17.5
Web3.js v1.5.3
```


2. **OpenZeppelin**
```bash
# I'm using version v2.3.0
JanettekiMacBook-Pro:nd1309-p2-Decentralized-Star-Notary-Service-Starter-Code janet$ npm list --depth=0 | grep openzeppelin-solidity
├── openzeppelin-solidity@2.3.0
```


### Your ERC-721 Token Name
SiyuStarToken


### Your ERC-721 Token Symbol
SST


### Your “Token Address” on the Rinkeby Network
https://rinkeby.etherscan.io/token/0xa571d7f2e6ad29618e16d03d274fee46872addf2



### Secrets Setup
The user of this project is expected to create .env in the project root, with API_KEY and MNEMONIC. Also .env should be put into .gitignore in each contributor's local repository.