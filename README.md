# myVault 60/40 Crypto Strategy Vault


The idea for the vault is to accept funds and then rebalance back to a 60% ETH 40% DAI stablecoins

Build using the following commands:

```
mv credentials-example.js credentials.js
code credentials.js (Enter rinkeby wallet address with funds and Alchemy/Etherscan API Keys)
npm install
npx hardhat compile
npx hardhat node --fork https://eth-rinkeby.alchemyapi.io/v2/YourAlchemyAPIKeyHere
npx hardhat test --network local
npx hardhat run scripts/deploy.js --network rinkeby
```
