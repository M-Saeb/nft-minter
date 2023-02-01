# 🗃 Simple NFT Minter
An NFT Minter interface that uses this [contract](https://ropsten.etherscan.io/address/0x4C4a07F737Bf57F6632B6CAB089B78f62385aCaE) to mint

## Used Technologies
- MetaMask
- Alchemy
- Pinata / IPFS

## Setup
start by creating the following account
- Meta Mask Account with a wallet on the Goerli network
- Alechmy account with an app on the Goerli network
- Pinata account with a file and an API key

once you created all the required accounts, create a .env file with the following variables

```bash
REACT_APP_PINATA_KEY= // fetched from the Pinata account
REACT_APP_PINATA_SECRET= // fetched from the Pinata account
REACT_APP_ALCHEMY_KEY= // fetched from the alchemy account
```


## Usage
you'll need a meta mask wallt to use, once that done simple run

```
npm run start
```

if the server didn't run successfully than run


```
npm update
```

followed by

```
npm run start
```

you should see a webpage that looks like the following

![image](https://assets-global.website-files.com/6171e9fea621c67e12b9f9be/6171e9fea621c6c103b9fc04_PNrbdLnNM6OriGE32N25TGSl.png)

from this page you can mint any NFT you want by filling the three requires fields:
- Link to assets: an image URL to link to the NFT (ex: `https://gateway.pinata.cloud/ipfs/QmNcb1qJ4DMNqyXhV3oy5a5CyUCGGRJqBztWVKHoEYU3fe/`)
- Name: name of the NFT
- Description: Any other info you want to add

Once all fields are filled, simply click on the "Mint NFT" button below, you should be asked to confirm from your Meta Mask wallet.

Confirm and **Voialla !!** you just minted an NFT 🎉