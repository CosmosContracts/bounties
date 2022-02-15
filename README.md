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

| Contract      | Description                                                                                                                                                                                                                                                                                                        | Claimed by | Reward   | PR(s) |
| :------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------- | :------- | :---- |
| Random beacon | Upgrade Confio's [rand contract](https://github.com/confio/rand) to work with the latest version of CosmWasm, and upload to Juno Mainnet. For more information about this contract see Simon's original [medium article](https://medium.com/@simonwarta/when-your-blockchain-needs-to-roll-the-dice-ed9da121f590). |            | 100 Juno |       |

## IBC

One of the most exciting things about Juno smart contracts, is that they support the [Inter-Blockchain Communication protocol (IBC)](https://ibcprotocol.org/) by default. So much is possible.

To claim these bounties, you must provide working open source code and successfully make transactions on _mainnets_ of any of the networks specified.

### Juno IBC Challenges

| Task                                                                                                            | Description                                                                                                                                                                                  | Reward   | PR(s)                                                        | Claimed by                                  |
| :-------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------- | ------------------------------------------------------------ | :------------------------------------------ |
| [First cw20 sent over IBC](https://github.com/CosmosContracts/bounties/pull/8)                                  | Send a cw20 over IBC, document and provide proof of accomplishment.                                                                                                                          | 100 JUNO | [#8](https://github.com/CosmosContracts/bounties/pull/8)     | juno1jax0gp2kczt3mmp68xt967z92yjnmrdm6ujrew |
| Make [cw20-ics20 contract](https://github.com/CosmWasm/cw-plus/tree/main/contracts/cw20-ics20) production ready | Help in the effort to make cw20-ics20 production ready. This award will be distributed to multiple individuals. Ways to contribute include coding, finding bugs, testing, and documentation. | 500 JUNO | [cw-plus #631](https://github.com/CosmWasm/cw-plus/pull/631) |                                             |

### Osmosis IBC Challenges

For these challenges, you'll need to create example CosmWasm contracts and documentation for interacting with Osmosis over IBC. In addition to $JUNO rewards, these challenges also have $OSMO rewards (amount TBD)!

NOTE: These challenges are currently BLOCKED until Osmosis adds support for IBC queries or CosmWasm.

| Task                 | Description                                                                                                                              | Reward         | PR                                                       | Claimed by |
| :------------------- | :--------------------------------------------------------------------------------------------------------------------------------------- | :------------- | -------------------------------------------------------- | :--------- |
| Query price over IBC | Query price information for a trading pair over IBC for use in a contract.                                                               | Partial Payout | [#5](https://github.com/CosmosContracts/bounties/pull/5) | @giansalex |
| Trade over IBC       | Swap two tokens over IBC on Osmosis.                                                                                                     | BLOCKED        |                                                          |            |
| LP tokens over IBC   | Add tokens to a Liquidity pool, bond them to receive LP rewards. Should also be able to unbound and remove tokens from a liquidity pool. | BLOCKED        |                                                          |            |

Useful resources include:

- [Create Custom IBC Application](https://docs.cosmos.network/master/ibc/custom.html)
- [Example Smart Contract for ICS20](https://github.com/CosmWasm/cw-plus/tree/main/contracts/cw20-ics20)

### Band protocol IBC Challenge

Band protocol supports [requesting oracle data over IBC](https://docs.bandchain.org/whitepaper/cosmos-ibc.html). For this challenge, please implement a smart contract that demonstrates requesting oracle data over IBC. Be sure to demonstrate this working on Juno mainnet and provide adequate documentation for replication in the contract's `README.md` file.

| Task                         | Description                                           | Reward   | Claimed by |
| :--------------------------- | :---------------------------------------------------- | :------- | :--------- |
| Request oracle data over IBC | Implement a contract to request oracle data over IBC. | 500 JUNO |            |

#### Rules

1. Submissions are open source. By submitting a PR, you're agreeing to License your contribution under an Open Source license.
2. Credit other people for their work.
3. Some solutions may require iteration to be accepted.
