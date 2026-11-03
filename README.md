# Solidity Smart Contracts

A set of Ethereum smart contracts written in Solidity 0.8.

| Contract | What it does |
|----------|--------------|
| `BZYtoken.sol` | ERC-20 token (100,000 supply, 2 decimals), approve-and-call |
| `Rewardtoken.sol`, `RewardTokenversion2.sol` | ERC-20 token with reward-per-token distribution |
| `staking (1).sol` | Staking: stake / unstake, claim rewards in several tokens, APR |
| `ThreeTokenSwaap.sol` | Swap between three tokens (OpenZeppelin ERC-20) |
| `SchoolManaging.sol` | Owner-only student registry with grades and certification status |

## Skills demonstrated
- Solidity: ERC-20 standard, allowances, modifiers (`onlyOwner`), events, reward maths
- Blockchain security basics: access control, integer overflow protection in Solidity 0.8

## Value for an employer
- Understanding of Web3 attack surface (access control flaws, approval abuse) useful for crypto-fraud and phishing investigations
- Code review mindset for financial logic

## Quick start
Open a contract in [Remix IDE](https://remix.ethereum.org), compile with Solidity 0.8.x and deploy to the Remix VM or a testnet.

> Learning project, not audited. Do not deploy to mainnet with real funds.
