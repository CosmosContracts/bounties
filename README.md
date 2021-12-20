# Junø Bounties

![Juno Bounties 1](https://user-images.githubusercontent.com/79812965/142215575-14f73bb6-cb9c-492c-92e5-47dde2d31133.png)

Want to earn some $JUNO and build reputation?

Welcome to Juno bounties.

To claim a bounty, first you should message the core team to express your interest in one of the bounties. If approved you can start working on it and when it's complete you can submit a PR to this repo and add your Juno address to the corresponding row in the table. A member of the core team will evaluate your claim, and if successful you'll be paid out the reward.

_In addition, if you go above and beyond the call of duty, the reviewers may decide to offer a bonus._

## IBC

One of the most exciting things about Juno smart contracts, is that they support the [Inter-Blockchain Communication protocol (IBC)](https://ibcprotocol.org/) by default. So much is possible.

### Juno IBC Challenges

| Task                     | Description                                                                                   | Reward   | Claimed by |
| :----------------------- | :-------------------------------------------------------------------------------------------- | :------- | :--------- |
| First cw20 sent over IBC | Send a cw20 over IBC, please provide proof in your PR and describe how you accomplished this. | 100 JUNO |            |

### Osmosis IBC Challenges

For these challenges, you'll need to create example CosmWasm contracts and documentation for interacting with Osmosis over IBC. In addition to $JUNO rewards, these challenges also have $OSMO rewards (amount TBD)!

| Task                 | Description                                                                                                                              | Reward     | Claimed by |
| :------------------- | :--------------------------------------------------------------------------------------------------------------------------------------- | :--------- | :--------- |
| Query price over IBC | Query price information for a trading pair over IBC for use in a contract.                                                               | 1000 JUNO  |  @giansalex |
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
