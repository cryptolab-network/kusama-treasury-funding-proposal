# Proposal

# Summary

CryptoLab (https://www.cryptolab.network) aims to provide organized data for both Kusama validators and nominators. 

For nominators, we help them to choose among the really large sets of Kusama validators. We would like to provide simple and sufficient data, and also notify them about validator status change such as validator's commission goes up to help them to avoid being deceived by malicious validators.

For validators, we help them to monitor the on-chain status such as being nominated or lost a nomination. We also help them to monitor their nodes, including notify them when their nodes go online/offline.

## Team Background

## Previous works

We have developed the CryptoLab website and Telegram bots, which already accumulated some users.

# Problem Statement

## Nominator

Staking on NPoS based chains is hard for non-technical newcomers. As staking on most PoS chains only requires a nominator to choose one validator, staking on Substrate-based chains has a multi-step procedure. Besides, as they are NPoS, a nominator can (and needs) to choose multiple validators. How can a nominator new to Kusama choose good validators can be a problem.

The Polkadot App, although it provided all the needed functions and realtime data for a nominator, it lacks of historical data and change notifications. A nominator must monitor the validators it chose frequently to avoid being deceived by malicious validators. It also is hard for a nominator to get how much staking rewards it earned solely on the Polkadot App.

To summarize, we aims to resolve the following problems for nominators

* Complicated nomination procedure
* Don't know which validators are good
* Hard to calculate rewards from staking
* No validator historical data 

## Validator

# Related Works

## Liquidity Provider

## Staking on Centralized Exchange

Many Kusama holders choose to stake their funds through centralized exchanges because the staking procedure is much simpler than staking on the App. While it is simple, the cons of it are evident. Nominators earns less and it also makes the chain pron to attack because stakes are more concentrated on validators hold by these exchanges.

# Our Solution

## Tasks

### Maintenance

CryptoLab currently runs in a virtual machine on a VPS. As the historical data grows, the performance of one virtual machine soon will not be sufficient. We plan to migrate our  service to AWS to utilize various functionalities on the platform.

