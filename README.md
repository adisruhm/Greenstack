 GreenStake

A sustainability-focused staking smart contract built in **Clarity** for the **Stacks blockchain**.

---

 Overview

**GreenStake** is a decentralized staking contract designed to support environmentally focused funding initiatives while rewarding participants for contributing capital.

The contract enables users to stake STX or SIP-010 tokens into a pool that can be linked to verified sustainability projects such as renewable energy, carbon offset initiatives, environmental restoration programs, and green infrastructure development.

By combining decentralized finance mechanisms with impact-focused funding, GreenStake introduces a transparent and programmable framework for sustainable finance within the Stacks ecosystem.

---

 Problem Statement

Environmental initiatives often face challenges such as:

- Limited access to decentralized funding
- Lack of transparency in fund allocation
- Dependence on centralized financial intermediaries
- Limited incentives for contributors

GreenStake addresses these challenges by:

- Providing a decentralized staking pool for sustainability funding
- Enabling transparent tracking of contributions
- Offering deterministic staking rewards
- Allowing programmable funding structures for green initiatives
- Creating incentive-aligned environmental finance systems

---

 Architecture

 Built With

- **Language:** Clarity
- **Blockchain:** Stacks
- **Framework:** Clarinet

 Supported Assets

- Native STX staking
- SIP-010 fungible tokens (optional extension)

---

 Roles

1. Contract Owner

Responsible for configuring the staking pool.

Capabilities:
- Set staking parameters
- Configure reward rates
- Define staking duration requirements
- Manage sustainability project metadata

2. Stakers

Participants who stake tokens in the pool.

Capabilities:
- Stake tokens
- Earn rewards over time
- Withdraw stake after conditions are met
- Claim accumulated rewards

3. Observers / Auditors

Any network participant can verify:

- Pool size
- Staked balances
- Reward distributions
- Staking activity

---

 Staking Lifecycle

1. Contract owner initializes staking parameters.
2. Users stake STX or supported tokens.
3. Staked funds accumulate within the pool.
4. Rewards are calculated based on staking duration and configured rates.
5. Users claim rewards periodically or upon withdrawal.
6. Stake can be withdrawn after lock conditions are satisfied.

---

 Core Features

-  STX and SIP-010 token staking
-  Deterministic reward distribution
-  Configurable staking durations
-  Transparent pool contribution tracking
-  Secure withdrawal and reward claiming
-  On-chain staking state verification
-  Minimal and auditable contract logic
-  Clarinet-compatible architecture

---

 Security Design Principles

- Deterministic reward calculations
- Explicit staking balance tracking
- Controlled withdrawal logic
- Transparent reward accounting
- Minimal attack surface
- Immutable contract rules once deployed

---

License

MIT License

---

Development & Testing

1. Install Clarinet

Follow official Stacks documentation to install Clarinet.

2. Initialize Project

```bash
clarinet new greenstake

3. Validate Contract

clarinet check
   
4. Run Tests

clarinet test


