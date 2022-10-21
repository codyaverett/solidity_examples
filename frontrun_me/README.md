# Frontrun me

A simple example showing how to write a smart contract that is easily frontrunnable by bots.
- Bots will even frontrun other bots sometimes

[Remix dev environment](https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.6.10+commit.00c0fcaf.js)

I used this [online keccak-256 encryption tool](https://keccak-256.4tools.net/) to generate an encrypted secret phrase for the intial contract creation.
I pass in the unencrypted string when I call the smart contract's take method to retrieve the assets placed in the contract.

## Reference
- [(video) How to get front-run on ethereum mainnet](https://www.youtube.com/watch?v=UZ-NNd6yjFM)
