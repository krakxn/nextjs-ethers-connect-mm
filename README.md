# MetamaskConnect - Next.js, Ethers.js:

This is a minimalistic project to show us how we can connect to Metamask using Ethers.js in Next.js / React.

This could just as easily be done in TypeScript.

This project starts with Next.js boilerplate, by running `yarn create next-app nextjs-ethers-metamask-connect`

## Requirements

- [Metamask](https://metamask.io/)
  - This is a browser extension that lets you interact with the blockchain.

## Quickstart

1. Clone the repo and install dependencies

2. Now, in my repositories, you need to clone hardhat-simple-storage in a new window 

- Then, you'll need to open up a second terminal, cd into the repo and run:

```
yarn hardhat node
```

This will deploy a sample contract and start a local hardhat blockchain.

3. Connect your [Metamask](https://metamask.io/) to your local hardhat blockchain.

> **PLEASE USE A METAMASK ACCOUNT THAT IS NOT ASSOCIATED WITH ANY REAL MONEY.**
>
> I usually use a few different browser profiles to separate my metamasks easily.

In the output of the above command, take one of the private key accounts and [import it into your Metamask.](https://metamask.zendesk.com/hc/en-us/articles/360015489331-How-to-import-an-Account)

Additionally, add your localhost (with chainId 31337) to your Metamask.

4. Open the UI

Then, back in your first terminal, run:

```
yarn dev
```

5. Hit buttons

You'll be brought to the UI after running `yarn dev` which has exactly 2 buttons. Hit `connect` then hit `execute` and you'll send a transaction to your local hardhat.

### Important localhost note

If you use metamask with a local network, everytime you shut down your node, you'll need to reset your account. Settings -> Advanced -> Reset account. Don't do this with a Metamask you have real funds in.

# Thank you!
