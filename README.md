# Cardano-based Lending and Staking Platform

This repository outlines the initial concept for a decentralized finance (DeFi) platform built on the Cardano blockchain. The platform is designed to leverage the power of Cardano Non-Fungible Tokens (CNFTs) to create a lending system with unique features.

## Concept

The platform enables users to obtain loans in ADA by collateralizing their CNFTs. A key feature of the platform is a dual-token system that integrates:

- A main utility and governance token.
- A treasury-backed token issued in the event of loan defaults, which is also stakable.

Initial CNFTs used to kickstart the platform can be staked to earn the main token, while the CNFTs minted from defaulted collateral can earn a separate treasury-backed token.

## Specifications

- The loan amount is determined as 1/3 of the CNFT's best offer on established marketplaces.
- An interest rate of 1% per week is charged.
- If a loan defaults, a new CNFT is minted and can be staked to earn a treasury-backed token.

The platform's mechanics aim to create a sustainable lending model while also contributing to the Cardano NFT ecosystem.

## Note

This repository is currently only for documenting the proposed idea. Detailed specifications and implementations will follow in subsequent updates.
