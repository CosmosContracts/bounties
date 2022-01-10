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

## IBC

One of the most exciting things about Juno smart contracts, is that they support the [Inter-Blockchain Communication protocol (IBC)](https://ibcprotocol.org/) by default. So much is possible.

To claim these bounties, you must provide working open source code and successfully make transactions on _mainnets_ of any of the networks specified.

### Juno IBC Challenges

| Task                     | Description                                                                                   | Reward   | Claimed by |
| :----------------------- | :-------------------------------------------------------------------------------------------- | :------- | :--------- |
| First cw20 sent over IBC | Send a cw20 over IBC, please provide proof in your PR and describe how you accomplished this. | 100 JUNO |            |

### Osmosis IBC Challenges

For these challenges, you'll need to create example CosmWasm contracts and documentation for interacting with Osmosis over IBC. In addition to $JUNO rewards, these challenges also have $OSMO rewards (amount TBD)!

| Task                 | Description                                                                                                                              | Reward     | Claimed by |
| :------------------- | :--------------------------------------------------------------------------------------------------------------------------------------- | :--------- | :--------- |
| Query price over IBC | Query price information for a trading pair over IBC for use in a contract.                                                               | 1000 JUNO  |            |
| Trade over IBC       | Swap two tokens over IBC on Osmosis.                                                                                                     | 5000 JUNO  |            |
| LP tokens over IBC   | Add tokens to a Liquidity pool, bond them to receive LP rewards. Should also be able to unbound and remove tokens from a liquidity pool. | 10000 JUNO |            |

- Note, claiming these will require sign off from both a Juno and Osmosis core team member.

These challenges will involve working with the Cosmos SDK as well as writing an example CosmWasm contract.

Useful resources include:

- [Create Custom IBC Application](https://docs.cosmos.network/master/ibc/custom.html)
- [Example Smart Contract for ICS20](https://github.com/CosmWasm/cw-plus/tree/main/contracts/cw20-ics20)

#### Rules

1. Submissions are open source. By submitting a PR, you're agreeing to License your contribution under an Open Source license.
2. Credit other people for their work.
3. Some solutions may require iteration to be accepted.
