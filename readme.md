# Decentralized Escrow Application

This is very basic dApp aims to provide decentralized Escrow services built with [Hardhat](https://hardhat.org/).

##### What is an escrow ?

An escrow is a contractual arrangement in which a third party (the stakeholder or escrow agent) receives and disburses money or property for the primary transacting parties, with the disbursement dependent on conditions agreed to by the transacting parties.


##### Why decentralization ?

Aim to take advantage of cool Ethereum features such as immutability and censorship resistance to provide flawless escrow service.

##### How to use this ?

Well if you need some escrow services and have little faith in human moral just follow the Getting Setup with dApp section below.

I advise to take a look at the Escrow contract to understand the logic before
setting up the dApp:

<img width="690" alt="Screen Shot 2023-01-03 at 9 57 42" src="https://user-images.githubusercontent.com/68856635/210323362-87af7c17-f90f-4fc0-a318-85244a023f23.png">




## Key Learnings

1. Escrow contract implementation

2. Running a Local Test Blockchain

3. Adding a Custom RPC Network to Metamask

4. React

## Getting setup

- Step 1: Cloning the repository

- Step 2: Installing the dependencies

- Step 3: Running a Local Test Blockchain via `npx hardhat node`

- Step 4: Add a Custom RPC Network to Metamask wallet i.e configure the browser wallet to about your locally running blockchain.

- Step 5: Compile the Contract via `npx hardhat compile`\*

- Step 6: Run the Front-End with React\*\*

- Interact With the dApp

\*_The artifacts will be placed in the `/app` folder, which will make it available to the front-end. This path configuration can be found in the `hardhat.config.js` file._

_\*\*To run the front-end application run `npm start` from the `/app` directory. Open [http://localhost:3000](http://localhost:3000) to view it in your browser._
