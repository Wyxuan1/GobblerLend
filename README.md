# GobblerBid
GobblerLend is a simple fixed term, fixed borrow p2pool lending platform based on LAN – with a few twists.

## Features
 - ERC 4626 vault tokens for composability
 - A VRGDA forked from [T11s' implementation](https://github.com/transmissions11/VRGDAs) to sell the ability to deposit in.
    - forked to support individual ERC20 tokens, rather than 721s.
 - Automatic loans denominated in Base_asset for GOO or Gobblers that meet the parameters of the pool
 - Deposits of unutilized funds into Aave for maximal capital efficiency

There's a bunch of other contracts which aren't part of GobblerBid itself, and the key contracts for GobblerBid are in /contracts/GobblerBid

## Use Case

A saavy group looking to acquire Goo or Gobblers at a discount can run their own GobblerBid instance, with their own oracle. 
On the other side, borrowers can acquire leverage on Goo or Gobblers. (goo, goo)?


## Todos:
- Create a Gobbler themed UI for the UI
- Iron out bugs and get testing done
- Initialize contracts when ArtGobblers hits mainnet

## Get Started
```
npm install --legacy-peer-deps
npx hardhat run scripts/deploy.js
```

Code has not been tested nor deployed. 


Goo Morning
