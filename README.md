# web3_RandomElections_au_001
Random~Electionsz | PIRATEorNINJA - project for ETHDENVER ENCODE Camp using Alchemy as the node-provider.

## SETUP ENVIRONMENT

> npm install

then to connect:
> npm install @alch/alchemy-web3
> npm install dotenv --save

> npm start,   //connection to contract works!

//INSTALL HARDHAT LOCALLY:
> npm install --save-dev hardhat
//UPDATE CONFIG: hardhat.config
> npx hardhat compile
//DEPLOY
> npx hardhat run scripts/deploy.js --network goerli
// VERIFY with EtherScan:
> npm install --save-dev @nomiclabs/hardhat-etherscan
// ETHERSCAN integration
UPDATE hardhat.config - to ETHERSCAN, with eKey.
VERIFY:
> npx hardhat verify --network goerli DEPLOYED_CONTRACT_ADDRESS 'Hello World!'
Gotta Get Parameters exactly correct for ABI VERIFICATION.


