# Khairul Ezw — Web3 Builder in Training

Building on-chain products, one contract at a time.

## About me
Beginner web3 builder working through the Web3 Builder Course. Currently learning Solidity, Foundry, and full-stack dApp development.

## Skills I'm learning in this course
- Solidity smart contracts
- Foundry (forge, cast, anvil, chisel)
- Next.js + TypeScript + wagmi/viem
- Supabase and SQL
- The Graph / Ponder indexing

## Currently working on
- Module 1.2: Git & GitHub from Scratch

## Module completion log
| Date | Module | Hours | What I built |
|------|--------|-------|--------------|
| 2026-08-14 | 1.1 The Terminal | ~3 | terminal-lab exercises |
| 2026-08-15 | 1.2 Git & GitHub | ~3 | git-practice repo + merge conflict |

## Projects

### Counter (Module 2.2 — redo)
First Foundry/Solidity contract deployed with my own wallet. Simple counter with `setNumber` and `increment` functions.

- Repo: github.com/khairulezwan2015-code/counter
- Deployed: https://sepolia.etherscan.io/address/0x2c3B9C9d491349b990341C2EE02fB942acD53f00
- Deployer wallet: 0xD465aAa9010B0c9BAE42Ea98880546553104Af4f (keystore "deployer")
- Tests: template suite — `test_Increment` + `testFuzz_SetNumber` (fuzz = many random runs)
- Stack: Solidity 0.8.13, Foundry 1.7.1
