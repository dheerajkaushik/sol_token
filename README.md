# module3sol

Creating a full UI for a Candy Machine 

# Functionality

-New SPL token is created
-splTokenAddress of new SPL token in added
-UI created for candy machine
-Mint tested using dummy account

## Project Overview

1.Create an SPL token.
2.You will need to tweak your config.json to use the splTokenAddress of the token you created in Step 1.
3.Create a UI for your candy machine 

## Getting Started

1. Set Environment:
   - Make sure you have Node.js and npm installed on your computer.

2. Create a React Application:
   - Initialize a new React application using Create React App or your preferred React setup.

3. Set Up a New Wallet
   - We first need to create a new wallet


4.Establish a Connection to Your QuickNode RP

Now to fund your wallet you can run the command:
```bash
solana airdrop 5
```
### Prepare NFT Assets
1.Configure Candy Machine

Create a new file, config.json in your root project folder.

Open the file and paste this config: 
```bash
{
    "price": 0.01,
    "number": 10,
    "symbol": "NB",
    "sellerFeeBasisPoints": 500,
    "gatekeeper": null,
    "solTreasuryAccount": null,
    "splTokenAccount": "address",
    "splToken": "spl token address",
    "goLiveDate": "2022-07-24T00:00:00Z",
    "endSettings": null,
    "whitelistMintSettings": null,
    "hiddenSettings": null,
    "uploadMethod": "bundlr",
    "awsS3Bucket": null,
    "retainAuthority": true,
    "isMutable": true,
    "creators": [
    {
      "address": "YOUR_WALLET_ADDRESS",
      "share": 100
    }
  ]
}
```
2.Sugar has a built in validation error that will let us check for any errors before we proceed. In terminal, run: 
```bash
sugar validate
```


**4. Configure Your Project:**
   - Modify your `config.json` to include the SPL token address you created earlier.


**5. Create UI Components:**
   - Design and implement your UI components for minting NFTs from the Candy Machine.



  # Author:
  
  Dheeraj

