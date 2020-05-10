# Voting system Decnetralized App on Blockchain

Organizational voting system Dapp using Ethereum smart contracts and web3.js for front end using metamask as an wallet provider for tetsing purposes across test RPC network.
The project was built using Truffle IDE for all development testing purposes using a locally hosted blockchain with the help of Ganache cli as provider of test chain.This 
project also uses node package manager for handling different node packages and for importing lite server for testing purpose.
## To run project:

1.Clone or download this repository to your machine.

2.Install dependencies i.e node package manager and truffle IDE along with ganche as GUI.

3.Launch terminal in your project directory and run commands in the following order:

 >  a. $ truffle compile  -this will compile the contracts in our project with the solidity compiler embedded inside truflle IDE.
  
 >  b. $ truflle test     -this will run our contracts against all the test cases written in test scripts inside test folder.
  
 after b,launch another terminal in same directory and run command $truffle develop,this will start the local blockchain on your machine using ganache and will generate some
 accounts for testing purposes along with their private keys and a sercret phrase.
 
 > c. $ truffle migrate  -this will deploy our contracts over test network.
 
 > d. $ npm run dev - this will run dev script in truffle-config.js file and start lite server and load the front end on your default web browser.
 
 now import accounts on meta mask using keys and try running different functions,refresh the page for changes to reflect.
