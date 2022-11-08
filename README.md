# Aave Liquidation Bot
* Find liquidatable loans from the Aave
* Calculate profits with own collateral
* Output details of unhealthy loan (checking health factor) if its profitable to liquidate
* Execute liquidation of the loans

## Solidity Contract
* All contracts can be found in `/contracts`
* Can be deployed to Goerli for testing

# To Do
* Currently this script is not setup to call the contract, it must be done manually.
* Remaining task is to automate the liquidation. This shouldn't be hard to do since the contract is already in place.


# To get started
1. Install dependencies
`npm install`

2. Deploy contract
All contracts can be found in `/contracts`

# Starting the bot
1. Specify the chain to use via APP_CHAIN_ID

2. Execute liquidation script
`npm run build`
`npm start`


Thanks to this repo for providing a base to start with.
https://github.com/Songark/aave-liquidation-bot
