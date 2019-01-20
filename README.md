# Barter DAPP
Barter Economy World on Ethereum DApp

## Introduction
This is a second-hand exchange platform using blockchain technology.  
Users can exchange their second-hand commodities for another, without the use of money or any type of tokens.  Thus, the owner can define the unique value of each used product.  
The platform also inherits the advantages of decentralized application: secure, open, and trust-worthy.

## Getting Started (localhost)
1. Install all dependencies
```
    cd react-box/client
    npm run install
```
2. Start Ganache on your computer and login to your Ethereum account using Metamask
3. Deployment:
```
    cd react-box
    truffle compile
    truffle migrate --reset
```
4. Run client on localhost and run server (MongoDB) at the same time 
```
    cd react-box/client
    npm run start
```
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Functions
1. Homepage
2. Upload an item and store its information on the blockchain.
3. Click on the item to start the exchange process.
4. Click "Like" or "Nope" button to show your preferences.
5. If 2 items from different users (Ethereum accounts) "likes" each other, there is a match! 
6. The matched items will be recorded in the blockchain.