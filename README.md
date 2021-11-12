# HealthLink-DataDAO

Hackathon Project Documentation:

Project: 

A Health-Chainlink DataDAO, that helps to monetize your own Health and wellness data to pay for your own insurance.
Note: An ELI5 version is available at the end.


Fundamentals: 


A Healthcare data reservoir that is sourced from multiple users
Privata data storage and computation
A mechanism for Data-aggregators to engage, for the simple reason being scattered datasets from multiple scattered user is less useful than an aggregator who connects multiple users to sub-license their 
A decentralized marketplace for consumers to choose data-aggregators/brokers to choose where their data goes to
Involvement of Data-NFTs to ensure there is sufficient data ownership visibility
A Chain Link stack to ensure that the off-chain data is reliable, the use-case of reliable data would be sufficient to pave the way for effective insurance-claim mechanism




Problem statement refinement:

The most common deficit that is found in the current Insurance model works against a common set of consumers who are not able to provide a list of verifiable data to insurance providers.
Truly verifiable data provides more value proposition to insurance providers


In our current model and use-case, we opt for a completely digital set of verifiable data sources.
mHealth data that is sourced from Digital biomarkers that are non-invasive or semi-invasive in nature.
The test mHealth data for the Hackathon will be sourced from a set of test users whose identifiers will be pseudo anonymised and only the meta-data of interest will be floated to data-reservoir 

Layer 1 Blockchain:

While, there are multiple methods to guarantee private computation such as differential privacy, E2E, split-learning, federated learning, we choose to go with Compute2data that is elegantly designed on the Ocean Protocol.
Compute2Data makes the job relatively easier with a working proof of concept Blockchain.
The working principle of Ocean protocol is shown below for ease of understanding and why we choose for our use-case




Secondary data-market place:

Even though the Ocean marketplace at Ocean Marketplace solves the decentralized connector component, it lacks the potential visibility that is needed for Digitized Healthcare data. A secondary market-place is necessary in our use-case since a dedicated focus is required to bridge data-aggregators related to the healthcare marketplace and insurance providers.

How do Data-aggregators operate?


For the purpose of working POC, we assume that the data aggregators are provided with specific access keys for aggregating the data-clusters. In the future, we plan to implement fine-grained access to ensure there is fair usage and a permissioned system to handle sensitive private data.

Fine-Grained Permissions now supported in Ocean Protocol


Dataset identifiers:

The ownership to individual users will be implemented using Data-NFTs or simply, giving a DID for the data-cluster provided by the user.



Monetization to both parties:

Providing data-liquidity and staking for source of funds to data providers
Data-aggregators will ensure there is sufficient private computation possible on the available data

Problem statement related to the end-use case:

Providing reliable set of informations that is required by the insurance providers
Deficit that is not covered by the insurance providers, can be offset by the monetized data + funds sourced from liquidity pool


Crucial developer aspects involved in the project:

Health data domain: mHealth and related IOT data linked to mobility and activities of the user. Test data-sets will be aggregated from volunteers to show the working principle


Private computation: A suitable privacy stack to ensure there is enough security over data production, storage, consumption and sufficient room for analytics without deviating from privacy concerns.


Layer 1 Blockchain: The ocean protocol that would serve us to safeguard the immediate fundamentals involved in the project operation


Secondary Blockchain: Involving secondary chains such as Polygon/Solana to carry forward the remaining operations that are not covered by the Core layer1 chain. This is the most important component in terms of developer activity since it requires bridging the best core components of Ocean protocol to the data-curators who will specifically find the data-consumers for monetization incentives.


Data NFT-Marketplace: Once the data-produce, privacy is ensured an NFT marketplace is needed . NFT standards depending on the blockchain would be leveraged to make the marketplace happen.



Liquidity pools:

The data based liquidity pool would need to be created, which benefits the users and data-curators. Incentives can be provided to both providers and consumers so there is financial incentive for both parties.

Assistance: Any expertise in designing the data-based liquidity pool will be welcome.


DAO Architecture: 

At the heart of the organizational architecture, a DAO approach necessitates the fair usage of data to cover for legalities


To ensure a community approach, there would be a mechanism where governance tokens will be issued toward the Data-NFT holders and ensure there is healthy transaction structure from data-reservoirs -> aggregators -> Data-consumers

Assistance: A supportive code-base that will ensure fair connection with the fair-voting policy of 1 Data NFT- 1 Vote, enabling the use-cases of ERC721 standards.


Data-storage: Storage aspects for

- Private computation
- Storage of the Data NFTs
Chain Link Stack: A suitable chainlink stack that enables the verifiability of digital data-providers. [More details to be added]


Useful Third party tools:
Moralis [ https://moralis.io/ ]
Alchemy [ https://www.alchemy.com/ ]


Unclear components:

How Might we use the Chain Link stack to back our idea?
Do we use any existing use-cases of decentralized insurance to retrofit into our idea?

Context of the Project:

Participation in the Chain Link hackathon. 

https://chainlink-fall-hackathon-2021.devpost.com/

Deadline for submitting approximate idea and Team members:
November 14th


Deadline for final submission: November 28th

Criteria: While using the existing use-cases provided by various chains is encouraged, we intend to make this an open-source project even though there is a massive opportunity to make this idea into a Web2 project.

Other criteria are mentioned in the hackathon post link above ^

Our Hackathon mission:

While we have been working on a completely original idea since the commencement of Hackathon, we encourage the community of DeFi & blockchain experts, developers to join our journey in giving us strong feedback and help us build our project that could make a large-scale social impact in the lives of people who could potentially pay for their own insurance with their own monetized data as Self-sovereign individuals with their right to own their own data.


Other helpful References:

Data-NFTs
https://medium.com/@trentmc0?p=dbb3a803096b


Building a smart contract for Insurance
https://blog.chain.link/parametric-insurance-smart-contract/


Team Members:

Dr. Prk
Discord: drprk.eth #1527

Along with Members of the DeFi Talent Builder DAO
( https://discord.gg/cK2yGpge )


DAO Team Meetup:

November 5th, Friday 3 pm IST 
November 8th, Monday 7pm IST
November 14th, 1pm IST


ELI5 version:

Nothing comes free of cost. if you’re a product user at no cost, You’re the product 


Why would you like to keep giving your data to Google & Facebook when you have the chance to monetize your own data?


The existing proof of concept for a Data economy happens at Ocean protocol, where they allow you to store your data-set in great privacy standards, with access to data-consumers where they would license/buy your data at a desirable market price

Example: https://market.oceanprotocol.com/


Okay, I’ve uploaded my data. What next? Can I license my own mobile based fitness data (in this use-case) to market buyers?

Yes, the intention is to connect your data-sets to multiple stakeholders of interest. Thereby rendering your data as it’s own asset-class


Why do I need data-aggregators? Why I can’t I sell it on my own

In principle, yes. You can sell your own data by yourself if you’re willing to provide valuable data with good visualization



Fine, As a Developer, what’s my job here?

Understanding Ocean protocol will make things easier since they have solved the monetization aspect. We will use it to suit our use-case by forking their existing marketplace

https://github.com/oceanprotocol/market

What next?

A reliable marketplace is essential to simplify the Platform for the providers & data-consumers. Enabling NFTs will be more impactful than using a tradeable data-token. 

The final marketplace would have to make it a lot easier by providing a catalogue of Data-NFTs (health-based data, for ease of convenience, we will source some dummy datasets)

The Data-NFTs will be catalogued according to existing market trends, demands and use-cases.










Bounties offered:

200 USDT

A deep dive of making the entire proposal understandable for any developer, right from understanding of the Ocean Protocol towards building the secondary marketplace for the data-consumers. Brainstorming of newer ideas is welcome.

50% of the Amount payable for the best draft version at a suitable deadline, followed by completion of the quest.

300 USDT

Building the secondary marketplace where data-based NFTs are minted by the users, with provision for using the marketplace as a data-consumer.

An Additional 300 USDT

For building a hybrid smart contract involving Oracles that verify the accuracy of the Mobile based data that is provided.

( Option to be part of the team): The above bounties are independent of the bounty options, although the deadline to be part of the team is on 14th of November.


Other requirements:

Team-support is available for additional guidance. Making this happen by one-self might sound like a herculean task, feel free to reach out to drprk.eth #1527 on Discord to brainstorm further.

