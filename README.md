## Getting Started

Create a project using this example:

```bash
npx thirdweb create --contract --template forge-starter
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

## Deployment Steps

To deploy the contract in this repository, follow these steps:

1. Ensure you have Node.js and npm installed on your machine.
2. Open a terminal and navigate to the root directory of the repository.
3. Run `npm install` to install the necessary dependencies.
4. Run `npm run build` to compile the contracts.
5. Run `npm run deploy` to deploy the contracts.

The deployment process uses the `thirdweb` tool, as specified in the `package.json` file. The deployment command is defined as `npx thirdweb@latest deploy`. Make sure you have the necessary permissions and configurations set up for deploying the contracts. For more details, refer to the `README.md` file.

## Join our Discord!

For any questions, suggestions, join our discord at [https://discord.gg/thirdweb](https://discord.gg/thirdweb).
