# WSKY

**Status: Historical** — reference only, no support, no further development.

A 2019 to 2021 collection of token and NFT contract source kept for reference.
Nothing here is deployed by Daly Ventures today, and none of it should be
treated as audited or production-ready.

## Contents

| File | What it is | Origin |
|---|---|---|
| `WSKY_Token.sol` | ERC-20 style `WSKY` token contract (Solidity 0.4.x era) | Etherscan-verified source, February 2019 |
| `1000_NFT_Mint.js` | Node script for batch-minting an NFT collection | Community mint tooling |
| `Megapont-nft-contract.clar` | Clarity NFT contract implementing the SIP-009 trait | Public Stacks contract (Megapont Ape Club) |
| `Megapont_Reveal.clar` | Identical copy of the file above, kept as originally saved | Same |
| `MiamiCoin.clar` | CityCoins MiamiCoin core contract v1 | Public Stacks contract |
| `MiamiCoin_TokenContract.clar` | CityCoins MiamiCoin token contract | Public Stacks contract |
| `free-punks.clar` | Clarity NFT contract (free-punks) | Public Stacks contract, mainnet |
| `Stacks_Code.clar` | Clarity hello-world example | Stacks tutorial |

Most files are copies of publicly published third-party contracts that were
studied while learning Stacks and Solidity. They remain subject to their
original authors' licenses. Only `WSKY_Token.sol` originated with this account.

## Why it is still here

It documents an early phase of Daly Ventures' work on tokenized assets and
predates the governed-AI portfolio (RealInsight, Hot-Wheels-Agent,
racing-intelligence, ai-wages). For current work, see
[github.com/brdaly](https://github.com/brdaly).
