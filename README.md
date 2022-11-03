## Entry for EarnWeb3 bounty | Thirdweb

Contract address: https://goerli.etherscan.io/address/0xC361464340eE7e10F6876271f4CD626973210E2d

Build with thirdweb's ContractKit. Create a custom smart contract in Solidity using thirdweb's ContractKit. 

Create a new contract and deploy it with 
```bash
npx thirdweb deploy
```
Check out your own contract dashboard, where you can call any function on your contract, and view the results and view a live-updating feed of all events emitted by your contract. 
It will look something like this

![My Remote Image](https://i.imgur.com/Wa3bbk3.png)

## Getting Started

Create a project using this example:

```bash
npx thirdweb create --contract --template hardhat-javascript-starter
```

You can start editing the page by modifying `contracts/Contract.sol`.

To add functionality to your contracts, you can use the `@thirdweb-dev/contracts` package which provides base contracts and extensions to inherit. The package is already installed with this project. Head to our [Contracts Extensions Docs](https://portal.thirdweb.com/thirdweb-deploy/contract-extensions) to learn more.

## Building the project

After any changes to the contract, run:

```bash
npm run build
# or
yarn build
```

to compile your contracts. This will also detect the [Contracts Extensions Docs](https://portal.thirdweb.com/thirdweb-deploy/contract-extensions) detected on your contract.

## Deploying Contracts

When you're ready to deploy your contracts, just run one of the following command to deploy you're contracts:

```bash
npm run deploy
# or
yarn deploy
```

## Releasing Contracts

If you want to release a version of your contracts publicly, you can use one of the followings command:

```bash
npm run release
# or
yarn release
```

## Join our Discord!

For any questions, suggestions, join our discord at [https://discord.gg/thirdweb](https://discord.gg/thirdweb).
