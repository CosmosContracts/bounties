# Junø Bounties

![Juno Bounties 1](https://user-images.githubusercontent.com/79812965/142215575-14f73bb6-cb9c-492c-92e5-47dde2d31133.png)

Want to earn some $JUNO and build reputation?

Welcome to Juno bounties.

To claim a bounty, first you should message the core team to express your interest in one of the bounties. If approved you can start working on it and when it's complete you can submit a PR to this repo and add your Juno address to the corresponding row in the table. A member of the core team will evaluate your claim, and if successful you'll be paid out the reward.

_In addition, if you go above and beyond the call of duty, the reviewers may decide to offer a bonus._

## Bug Bounties

Eligible GitHub repositories for Bug Bounties include:

- [juno](https://github.com/CosmosContracts/juno): the Juno blockchain source code.
- [wasmd](https://github.com/cosmwasm/wasmd): the core smart contract module used by the Juno Blockchain.
- [cw-plus](https://github.com/cosmwasm/cw-plus): a library of contracts used by many Juno Projects.

Please confidentially report vulnerabilities to `Meow Stargaze ✨🔭#1736` or `dimi 🦙#2998` on the [Juno Discord](https://discord.gg/QcWPfK4gJ2). Rewards will be determined based on the severity and whether or not a fix is provide.

**Critical Vulnerability:**

A critical vulnerability is something that would take down the chain, or cause the token to devalue in a serious manner.

**Medium Vulnerability:**

A medium vulnerability is something that could potentially disrupt the chain.

**Low Vulnerability:**

A low vulnerability is something that might slow down the chain or make it less efficient.

## Contracts

These challenges involve writing contracts. To claim, PRs must link to an open source repo.

## IBC

One of the most exciting things about Juno smart contracts, is that they support the [Inter-Blockchain Communication protocol (IBC)](https://ibcprotocol.org/) by default. So much is possible.

To claim these bounties, you must provide working open source code and successfully make transactions on _mainnets_ of any of the networks specified.

### Band protocol IBC Challenge

Band protocol supports [requesting oracle data over IBC](https://docs.bandchain.org/whitepaper/cosmos-ibc.html). For this challenge, please implement a smart contract that demonstrates requesting oracle data over IBC. Be sure to demonstrate this working on Juno mainnet and provide adequate documentation for replication in the contract's `README.md` file.

| Task                         | Description                                           | Reward   | Claimed by |
| :--------------------------- | :---------------------------------------------------- | :------- | :--------- |
| Request oracle data over IBC | Implement a contract to request oracle data over IBC. | 500 JUNO |            |

#### Rules

1. Submissions are open source. By submitting a PR, you're agreeing to License your contribution under an Open Source license.
2. Credit other people for their work.
3. Some solutions may require iteration to be accepted.
