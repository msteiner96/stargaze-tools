# Stargaze Mission Control

Mission control is a set of tools for launching a project and minting on Stargaze.

## Setup project

```sh
git clone https://github.com/public-awesome/stargaze-nft
cd stargaze-nft
yarn install
```

## Create an account on testnet

```sh
yarn run account
```

## Get funds from faucet

```sh
yarn run fund [your-address]
```

## Configure project

Edit `config.json` with your project configuration.

## Initialize an NFT minting contract

```sh
yarn run init
```

Edit `config.json` with the contract address.

## Mint an NFT

```sh
yarn run mint --to [address]
```

`[address]` can be any Cosmos address. It'll be converted automatically into a Stargaze address that starts with "stars".
