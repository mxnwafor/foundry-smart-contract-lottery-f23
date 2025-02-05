# Provably Random Raffle Contract

## About

This code is to build a provably random smart contract lottery.

## Note
Test coverage is at 54.92%. More functionality testing to be done with time.

## Quickstart
Install foundry with:
```
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

Check forge version:
```
forge --version
```

Check cast version:
```
cast --version
```

Check anvil version:
```
anvil --version
```

Clone into the repo:
```
git clone https://github.com/mxnwafor/foundry-smart-contract-lottery-f23
cd foundry-smart-contract-lottery-f23
forge build
```

## What we want it to do:

1. Users can enter by paying for a ticket
    1. The ticket fees are going to go to the winner after the draw
2. After X period of time, the lottery automatically draws a winner
    1. And this will be done programmatically
3. Using Chainlink VRF and Chainlink Automation
    1. Chainlink VRF -> Randomness
    2. Chainlink Automation -> Time based trigger

## Tests!

1. Write some deploy scripts
2. Write our tests
    1. Work on a local chain
    2. Forked Testnet
    3. Forked Mainnet