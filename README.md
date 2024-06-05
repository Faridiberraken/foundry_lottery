# Proveably Random Raffle Contracts

## About

This code is to create a proveably random smart contract lottery.

## What we want it to do?

1. Users have to pay a fee to buy a lottery ticket
   1. At the end of the lottery the winner will get all the fees collected.
2. After a period of time, the lottery will automatically draw a winner.
   1. And this will be done programatically.
3. Using Chainlink VRF and Chainlink Automation
   1. Chainlink VRF --> Randomness
   2. Chainlink Automation --> Timed based trigger
