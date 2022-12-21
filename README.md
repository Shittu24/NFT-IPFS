# NON FUNGIBLE TOKENS (NFTs) METADATA ON IPFS WITH LEARNWEB3DAO JUNIOR TRACK

This project demonstrates a NFTs collection contract where users can buy different NFTs collection whose metadata is stored on Inter Planetary File System (IPFS). There are only 10 NFTs available for this collection so once the 10 NFTs have been minted, nobody can buy NFTs again. Also, only the owner of this contract can withdraw the ETH used to mint each of the NFTs and the owner can also transfer or renounce his ownership.

The frontend of this contract was built with NextJS that provides a simple user interface to allow users to interact with the contract.

Firstly, you need to connect your wallet on the mumbai testnet(polygon) then click on thye public mint. You will also see the NFTs available to be minted. If there is NFTs available, you will be able to mint  a NFT with your address and you can view them on opensea.


Try running some of the following tasks on the contract (hardhat) directory:

```shell
npm install
yarn hardhat help
yarn hardhat test
yarn hardhat node
yarn hardhat run scripts/deploy.js
yarn hardhat run scripts/deploy.js --network mumbai
```

## Getting Started With The Frontend in the my-app directory

First, run the development server:

```bash
npm install
npm run dev
# or
yarn 
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.