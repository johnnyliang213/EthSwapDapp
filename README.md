# EthSwapDapp
decentralized app for swapping eth token to a fake token

### Follow the following steps to run this application on local
1. `git clone` the project and cd into the project directory to run `npm install` and `npm run start`
2. Run `truffle migrate` and `truffle deploy` to locally deploy smart contract 
3. Make sure `Ganache` is up and running on port `7545`
4. Connects Metamask to localhost:7545 and connects an account from `Ganache` by key in a fake private key
5. Happy Swapping!!

### Smart Contract Developement
There are two smart contracts for this project, a fake ERC-20 Token contract and a eth swap exchange contract. Both contracts were tested and the test file can be found in  the `test` folder. 

### Demo video
[![Click to view demo](https://youtu.be/ntupkcvcg-I)](https://youtu.be/ntupkcvcg-I)
