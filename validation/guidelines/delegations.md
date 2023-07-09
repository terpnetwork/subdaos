# Delegation Guidelines

NOTE: These guidelines are not in action until consensus & creation of the Validation Delegation SubDAO.


## Delegations SubDAO Inception

The Validation Delegations SubDAO (VDS) is a part of the Validation SubDAO, to be proposed through both Terp Network & the validation subDAO governance processes.

## Why do we have a Delegation SubDAO?

The three core components of any distributed proof of stake blockchain are delegators, validators and the founding team. As the blockchain matures, additional roles are required to assist with community engagement and support to build on foundations set from genesis. Typical members/roles added include developers, marketing managers, and community managers. As Terp Network is a DAO-based blockchain, managing delegations to validators from the Foundation DAO can been (primarily) moved from the founding team (aka "Foundation DAO") to the Validation Delegation SubDAO.

## The objectives of the VDS are:

- To provide the Validation Subdao within an ongoing income stream from staking rewards which will be used for future development of the Terp Network. 
- To reward validators that contribute to Terp Network, via staking TERP with them, which provides a continual revenue stream via comission. 

## Who can apply for the delegations program?
Any entity running a validator node on the Terp Network that satisfies the minimum requirements outlined in section 2.1

## How can a delegator apply for a delegation?
By submitting a delegation request here. The form will only be open for submissions during delegation application collection periods. These periods will be announced on the @TerpCulture Twitter account.

## Delegation Epoch
Delegations will be made for a set period. This period is known as an epoch. The epoch will be marked by a Terp Network block number which will be provided after applications are scored and delegations are made. The epoch length is determined by the subdao. 

## Determination of individual delegation amounts
The total amount that will be delegated to each validator will be a function of the total amount allocated to be delegated by the Validation Delegation SubDAO, the total score earned by the validator (resultant from assessment of application), and the points multiplier to be applied as per section 1.8.

# Delegation Criteria

The delegation criteria have been developed with the best interest of Terp Network and the Terp Network community in mind. The criteria aim to incentivize desireable outcomes for the Terp Network including:
- Decentralized, reliable and trusted network of validators.
- Retaining full network history.
- Robust IBC relayer network.
- Robust and accessible network of RPC and API nodes.
- Development of the core network binary.
- Development of ecosystem dApps and tooling.
- Participation in network governance and governance discussions.
- Social participation in the network ecosystem.

## Minimum Requirements

A Validator must satisfy the minimum requirements of the program. These requirements are scored as pass/fail. If any of the minimum requirements are not met, the validator will not be considered for a delegation and the application will be rejected.

If a Validator has received a delegation and is found to no longer meet the minimum requirements at any point during the epoch, the delegation will be removed.

- **Submission of application:** An application must be submitted to the SubDAO
- **Validator information:** The validator must have accurate on-chain information including:
   - a minimum of one form of contact information
   - a security contact
   - a logo/avatar submitted on-chain to their validator
- **Maximum commission:** The validator must have a commission rate lower than or equal to 10%.
- **Maximum rank:** The validator must be ranked outside the top 10 validators, ranked by bonded voting power.
- **Exchange validators:** The validator must not be owned and/or operated by a centralized exchange.
- **Governance participation** The validator must have voted on **80%** or more of governance proposals that enter the voting phase during the epoch.
- **Uptime**  The validator uptime during the previous epoch must be 95% or greater. Uptime is determined by counting the number of blocks recorded on-chain that are signed by the validator.
- **Downtime slashing** The validator must not be slashed for downtime more than once during the previous epoch.
- **Doublesign slashing** A validator that has double-signed will not be considered for the program. If part of special circumstances (e.g. the Project Team had given wrong instructions) exceptions for a hard slash can be made.
- **Multiple validators** One delegation per entity is allowed. Therefore, the term validator in this document also refers to the respective organization/brand/individual or otherwise, and not only to the specific on-chain validator.
-  **White-label validators** A validator that is “white-labeled”, operates a revenue split, or is not run wholly by the team applying for the delegation is ineligible for a delegation.

## Technical Criteria
Technical criteria are assessed by the SubDAO. These items are not considered mandatory, however, they will contribute to the overall score of the applicant.

### Core Development  (Max. 3000 points)

Awarded for applicant's contribution to the Terp Network code base. Organizations that are otherwise employed by the Terp Network for their contributions will not be awarded points in this category.

Contributions must be merged into the Terp Network code base to be considered for assessment.

The score awarded is determined by the SubDAO.

### Non-Core Development  (Max. 2500 points)

Awarded for applicant's ongoing development of open-source dApps, smart contracts, community tooling, etc.

The score awarded is determined by the SubDAO.

### Relayer Operations (Max. 2000 points)
Awarded for relayer operations during the previous epoch.

The score awarded is calculated as a percentage of successful relay transactions vs the total successful transactions over the previous epoch period.

### Mainnet Public Archive Node (Max. 1500 points)

Points are awarded for the node uptime during the previous epoch. The maximum points are awarded for 100% uptime and the score is scaled linearly down to 85%. If the node uptime is less than 85%, no points are awarded.

Operators must submit the archive node address to the SubDAO when the node is brought online such that it can be monitored for consideration in the next round.

### Mainnet Public RPC/API/Websocket Node (Max. 1000 points)

Points are awarded for the node uptime during the previous epoch. The maximum points are awarded for 100% uptime and the score is scaled linearly down to 85%. If the node uptime is less than 85%, no points are awarded.

The RPC/API node will be added to the Terp Network public proxy.

Required services - RPC, gRPC, API.

### Testnet Validator Node (Max. 2000 points)

Points are awarded for the operation of a validator on the most current testnet. The testnet validator uptime during the previous epoch must be 95% or greater.

Uptime is determined by counting the number of blocks recorded on-chain that are signed by the validator.

### Testnet Public RPC/API/Websocket Node (Max. 1000 points)

Points are awarded for the node uptime during the previous epoch. The maximum points are awarded for 100% uptime and the score is scaled linearly down to 85%. If the node uptime is less than 85%, no points are awarded.

## Non-technical Criteria

Non-technical criteria are assessed by the SubDAO. These items are not considered mandatory, however, they will contribute to the overall score of the applicant.

### Ecosystem Participation  (Max. 2000 points)
Participation in the Terp ecosystem score (Social media, Telegram, Discord, writing documentation, guides, posts etc.).

Points are decided by the SubDAO.

Some examples of these activities are provided below:

- Moderate non-English local language community - so long as there are no other funding sources for this work. The moderation of these channels must be provided for at least 5 days per week.

- Promote Terp through social activities like Podcasts, Youtube, Twitter Spaces, etc.
- Provide and maintain training and onboarding content to help lower the barrier of entry to end-users, while promoting the secure use of wallets and applications.
- Publish valuable content online (Medium, Twitter threads, etc) that highlights Terp and Applications on the Terp Network.

### Active Participation In Governance  (Max. 1500 points)

Points are awarded for active participation in governance including taking part in discussions on commonwealth.im both before a proposal goes on-chain and during the voting period.

Points are decided by the SubDAO.

This criterion is separate from the minimum governance voting participation outlined in section 2.1.7

### Self Bonded Tokens  (Max. 500 points)

Points are awarded for a validator's self-stake compared to the total amount staked to the validator. The minimum required self-stake is 0.1% of the total staked and 500 TERP to be eligible for this criteria.




