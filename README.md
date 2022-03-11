# 💰 Build subgraph for your favorite yield aggregators! ($20k) 💰

## Goals

Messari is looking for experienced subgraph developers to help build out a set of subgraphs. The subgraphs will be built out for the following protocols:

- BadgerDAO
- Tokemak
- StakeDAO
- Yield Yak

You are free to pick any (or all) of the four above protocols to work on. We will award 5000 USDC to a subgraph implemented for each of the above protocol.

The subgraphs need to be built according to the following schema:
https://github.com/messari/gitcoin-grant/blob/master/schema.graphql

*Feel free to contact @v_for_vincent on Telegram or Twitter for any questions about the schema.*

## Details

The [schema](https://github.com/messari/gitcoin-grant/blob/master/schema.graphql) is well documented and has comments explaining each entity/field. Below are some examples of the data you will need to map/compute for the subgraphs:

- Pool/vault information
- Usage information
- Revenue/Fees
- Transactions

You will need to refer to each protocol for details on how to calculate fees/revenue/tvl etc:

- BadgerDAO
  - Protocol documentation: https://badger-finance.gitbook.io/badger-finance/
  - Smart contracts: https://github.com/Badger-Finance/badger-system
  - Deployed addresses: https://docs.badger.com/badger-finance/contract-addresses
  - Existing subgraphs: https://github.com/Badger-Finance/badger-subgraph
- Tokemak
  - Protocol documentation: https://docs.tokemak.xyz/
  - Smart contracts: https://github.com/Tokemak/tokemak-smart-contracts-public
  - Deployed addresses: https://docs.tokemak.xyz/protocol-information/contract-interactions
- StakeDAO
  - Protocol documentation: https://stakedao.gitbook.io/stakedaohq/
  - Smart contracts: https://github.com/StakeDAO/smart-contracts
  - Deployed addresses: https://stakedao.gitbook.io/stakedaohq/platform/deployed-contracts
  - Existing subgraphs: https://github.com/SimpleFi-finance/subgraphs/tree/master/stake-dao
- Yield Yak
  - Protocol documentation: https://docs.yieldyak.com/
  - Smart contracts: https://github.com/yieldyak/smart-contracts

Some of the protocols have existing subgraphs you can use as a reference.

## Submission Requirements

- Submission needs to strictly follow above schema
- Code needs to be easy to understand and well-documented
- All calculations (e.g. Revenue, TVL) need to be accurate (verified against other sources)
- Completed subgraph needs to index fully and sync to head

After you start, please give us a weekly update on your progress so we can keep track.

## Work Plan

- Please tell us which subgraphs you are planning to build. If you decide to work on multiple, let us know the order in which you plan to do.
- If you've built subgraphs previously, please include a link to either the deployed subgraph or the Github repo.
- Please let us know your estimated timeline.

## Bounty

- 5000 USDC will be awarded to the winner of each subgraph upon completion
- You can work on multiple subgraphs and win multiple rewards

*Feel free to contact @v_for_vincent on Telegram or Twitter for more information.*
