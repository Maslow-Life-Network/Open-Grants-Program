# **Open Grant Proposal**

- **Project** : Citadel.one integration of Polkadot
- Proposer (GitHub account): citadeldao
- Payment Address: 1A1vqwiis7HWsvXHutsTj956SgrjRSNj5Y

## **Project Overview**📄

### **Overview**

Please provide the following:

**A brief description of the project.**

Citadel.one is a non-custodial Proof-of-Stake platform for the management and storage of crypto assets. Users can create public addresses for all supported networks with one seed phrase, connect their Ledger or Trezor device, or import an address generated by another wallet. The analytical dashboard provides relevant information on wallets&#39; balances and networks&#39; main metrics. One of the main functions of the Citadel.one platform is participation in the PoS consensus — users can stake and delegate their assets, claim rewards, and follow the latest network proposals in the voting tab.

**An indication of how you will integrate this project into Substrate / Polkadot / Kusama.**

1. Citadel will provide users with a seamless Polkadot experience - send, stake, claim rewards, exchange DOT tokens via web/mobile as well as with hardware wallets. Among the major features Citadel gives access to extended analytics for the network, transactions, and users&#39; portfolio - we classify transactions, build relevant charts for rewards and balance.
2. On a basis of our product, other applications for Polkadot could be created as soon as we will publicly share the Polkadot blockchain transaction parser to the PostgreSQL database. At this point, any dev team will be able to build analytical dashboards using standardized SQL-requests.
3. We will also share our API interface for interactions with Polkadot node through which other apps will be able to integrate Polkadot transactions and staking.
4. With Citadel, users can claim rewards directly in the app. Additionally, notifications and mailing will be set highlighting rewards for claiming so that the user won&#39;t miss any of his rewards which is especially important as the rewards have [their expiration date](https://wiki.polkadot.network/docs/en/learn-simple-payouts). Apart from that, an API method for rewards claiming will be provided for public access.

**An indication of why your team is interested in creating this project.**

Citadel team believes Polkadot is unique by design. Very soon after the launch, the project entered the Top-5 by $ locked in staking, joining major PoS industry leaders like Tezos and EOS. Now, according to [Staking Rewards](https://www.stakingrewards.com/global-charts), Polkadot is an absolute leader with approximately $3 billion value participating in staking. Our mission is to bring the easiest user-experience to Polkadot holders which can consequently boost the growth of staking ratio, community and ecosystem.

**Project Details**

- **Mockups/designs of any UI components**

_Web-version mockup_

![](https://citadel.one/staticf/web.png)

_Mobile version mockups_

![](https://citadel.one/staticf/mob1.png) ![](https://citadel.one/staticf/mob2.png)

- **API specifications of the core functionality**

Below you can find the link to our API documentation. Not only we plan to integrate Polkadot into Citadel, but also upon the integration completion, we will share the open API for the development associated with DOT coins, including transfers, staking, transaction types, etc.

[https://work.paradigmfund.io/api/doc/](https://work.paradigmfund.io/api/doc/)

- **An overview of the technology stack to be used**

Web:
- Vue.js
- Node.js
- Express
- PM2
- Postgres
- Socket.IO

Mobile:
- Flutter Ios/Android
- Trustwallet/walletcore

**PoC/MVP or other relevant prior work or research on the topic**

The working product is accessible via the link - [citadel.one](https://citadel.one/)

### **Ecosystem Fit**

**Are there any other projects similar to yours? If so, how is your project different?**

The most similar to what we are building at Citadel is Lunie. However, some features and platforms&#39; details are different - it provides DOT holders with an opportunity to choose what&#39;s best for them.

To begin with, as multi-asset platforms, Citadel and Lunie support different networks. Thus, depending on the user&#39;s portfolio,one of the platforms will be more preferable, than the other. For example, if a user holds DOT and XTZ, Citadel will become a good all-in-one solution; in the same manner, if a user possesses DOT and AKT, it may be easier for him to use Lunie. In addition, Citadel supports Bitcoin, Ethereum, and Tether for the comfort of our users.

Furthermore, we integrated the fiat gateway and instant cryptocurrency exchange so that users can effortlessly buy tokens right in the app. Also, Citadel users have access to their transaction history details and a full analytical dashboard that allows them to track all the assets across multiple networks with a proper reward calculation. Lunie and Citadel have absolutely different interfaces, so users are free to choose the most suitable solution based on their specific needs. Below, you can find a quick comparison table.

|| **Citadel** | **Lunie** |
| --- | --- | --- |
| Networks available for staking | Cosmos, Polkadot (coming soon), Tezos, IOST, ICON, Orbs | Cosmos, Akash Network, e-Money, Polkadot, Kusama, KAVA, Terra |
| Other supported networks | Bitcoin, Ethereum, Tether | - |
| Staking | Yes | Yes |
| Proposals explorer | Yes | Yes |
| Fiat gateway | Yes | No |
| Built-in exchange | Yes | No |
| Transaction history | Yes | Coming soon |
| Overall analytical dashboard | Yes | No |
| Price feed information | Yes | No |
| Mobile app | Coming soon | Yes |

## **Team**👥

### **Team members**

**Dev team members**

- Gregory Shabalov - co-founder, CTO
- Pavel Khivintsev - Lead Backend Developer
- Petr Lapin - Lead Frontend Developer
- Alexander Nikishkin - Frontend Developer
- Alexandr Kozhemyakin - QA Engineer
- Nikita Pashkov - DevOps Engineer
- Yeskendir Sarinov - Backend Developer
- Aleksey Gavrilyuk - QA Engineer
- Andrey Dershevich - Mobile Developer

**Other team members**

- Alex Falko - co-founder, CFO
- Anton Pavlutsky - co-founder, CEO
- Dmitrii Shehovtsov - Head of Research
- Rina Spasenkova - CMO
- Vlad Gorlov - Community Lead
- Margo Omelchenko - Lead Designer

### **Team Website**

https://citadel.one/

### **Legal Structure**

Citadel.One PTE LTD

068914, SBF CENTER, SINGAPORE, 160 ROBINSON ROAD

### **Team&#39;s experience**

Citadel.One team is extensive not only by quantity but also by quality. Our team consists of specialists that are apt to cover all the tech needs – from DevOps and node administration to backend &amp; frontend handling. What&#39;s more, with the significant business, and finance knowledge of Alex Falko, vast project &amp; product experience of Anton Pavlutsky, and the all-encompassing hard skills of Gregory Shabalov, the Citadel team is competent in supporting sustainable growth and development.

As for the team&#39;s interesting cases, we shall begin with our co-founders&#39; experience. Feel free to check out interviews with [Anton](https://www.youtube.com/watch?v=f14BxVsF4Es&amp;t=94s) and with [Gregory](https://medium.com/citadel-one/interview-with-gregory-shabalov-cto-of-citadel-one-3eed1b4005db?source=---------0-----------------------), where they cover all of their relevant career experience. Furthermore, our dev team did hard yet interesting work with standardizing the tech stuff for all integrated networks: they coped to parse Tezos, ICON, IOST, Ethereum, Cosmos and bring them to the unified database storage standard so that the analytics can be provided in the quickest and the most convenient way.

Our Lead Backend Developer, Pavel, was apt to unload transactions in the shortest possible time by restructuring the parsing and data saving process using the streaming method. He also found a way to optimize the logic of wallet generation for different networks in order to reduce the number of libraries used and get a much faster website experience for users. Now Pavel is working on an extremely interesting instance associated with decoding the encoded Ontology byte data into a readable form.

**Team Code Repos**

From our side, we are ready to make the part associated specifically with Polkadot fully open-source. Accesses will be given to the Polkadot team directly upon request.

### **Team LinkedIn/GitHub Profiles**

- Alex Falko - [https://www.linkedin.com/in/alex-falko-a3b79289/](https://www.linkedin.com/in/alex-falko-a3b79289/)
- Gregory Shabalov - [https://www.linkedin.com/in/shabalov/](https://www.linkedin.com/in/shabalov/)
- Pavel Khivintsev - [https://www.linkedin.com/in/pavel-khivintsev-89667072/](https://www.linkedin.com/in/pavel-khivintsev-89667072/)
- Petr Lapin - https://github.com/lapinlapin
- Andrey Dershevich - https://github.com/Dersh
- Alexander Nikishkin - https://www.linkedin.com/in/aleksandr-nikishkin-1a0500197/
- Alexandr Kozhemyakin - [https://www.linkedin.com/in/alexandr-kozhemyakin-qa/](https://www.linkedin.com/in/alexandr-kozhemyakin-qa/)
- Nikita Pashkov - [https://github.com/Krewedk0](https://github.com/Krewedk0)
- Yeskendir Sarinov - [https://www.linkedin.com/in/yeskendir-sarinov-1b08771ab](https://www.linkedin.com/in/yeskendir-sarinov-1b08771ab)
- Aleksey Gavrilyuk - https://www.linkedin.com/in/aleksey-gavrilyuk-40595782/
- Dmitrii Shehovtsov - [https://www.linkedin.com/in/dmitrii-shekhovtsov-bba673189/](https://www.linkedin.com/in/dmitrii-shekhovtsov-bba673189/)
- Rina Spasenkova - [https://www.linkedin.com/in/neshtedle/](https://www.linkedin.com/in/neshtedle/)
- Vlad Gorlov - [https://www.linkedin.com/in/vladgorlov/](https://www.linkedin.com/in/vladgorlov/)

## **Development Roadmap**🔩

# **Roadmap Overview**

| **Number** | **Step** | **Specification** | **Detailed description** | **Team members involved** |
| --- | --- | --- | --- | --- |
| 1 | Node launch (not included in grant amount requirements) | Citadel will join the Polkadot ecosystem as a validator | The Polkadot node will be deployed with the setting of specific glitch recognition notifications (for instance, in case the validator node suspended block production, or server memory faced some issues) via Zabbix and Grafana. As a result of this stage, we expect the node to be up and running with the maintenance system and RPC interface for node access. After the successful node launch, the necessary support and updates will be provided for a longer period. | Nikita (system administrator)120h per year|
| 2 | Design (not included in grant amount requirements) | Interface preparation, design elements specifications, and tuning | As a result of this stage, the mockups for web and mobile UI will be ready on Figma. | Margarita Omelchenko (Lead Designer)40h |
| 3 | Preparation set 1 | Polkadot blockchain scrutiny, data transfer to PostgreSQL (for data aggregation and statistics building) | This stage mainly involves the examination of Polkadot blockchain, parser building for the data transfers to PostgreSQL database (it will allow us to aggregate data conveniently, receive transactions of a certain type on a specific address, etc.)This step will bring us some vital milestones: our database will contain all the transactions - new ones sourced directly from the blockchain will be also stored in our database that is convenient for the development needs (balance/rewards charts creation, etc.)Also, as a result we will possess the following connector methods: (isSystemAddress, validateAddress, getLastBlock, getNextBlock, getOneBlock, filterOperations, getDelegationBalanceInfo). | Yeskendir (Backend Developer), Pavel (Lead Backend Developer)120h |
| 4 | Preparation set 2 | Examination of Polkadot transfer methods and staking system | This step entails the connector methods: prepareTransfer, prepareDelegation, sendTransaction). | Yeskendir (Backend Developer), Pavel (Lead Backend Developer)30h |
| 5 | Transfers integration | Analysis of a network&#39;s transfer transaction; search for necessary libraries or APIs;determination of transaction preparation logic; writing logic; signing; writing the send logic | Upon the successful completion of this step, we will have transactions integrated into web and mobile versions, as well as Backend API methods for the execution of transfers&#39; transactions. | Pavel (Lead Backend Developer), Petr (Lead Frontend Developer), Yeskendir (Backend Developer), Alexander (Frontend Developer), Andrey (Mobile Developer)80 h |
| 6 | Integration of staking | Analysis of network&#39;s staking transaction, search for necessary libraries or APIs;determination of transaction preparation logic; writing logic; signing; writing the send logic. Polkadot validator list parsing. | By the end of this step, we will have staking integrated into web and mobile versions, as well as Backend API methods for the execution of staking transactions via our node. Trezor and Ledger integration for Polkadot. | Pavel (Lead Backend Developer), Petr (Lead Frontend Developer), Yeskendir (Backend Developer), Alexander (Frontend Developer), Andrey (Mobile Developer)80h |
| 7 | Transaction and price feed metrics adding | Finding a suitable price feed solution. Information collection from node&#39;s RPC via API or source libraries. | At this stage, we are preparing the relevant data for charts and the network&#39;s significant metrics. | Yeskendir (Backend Developer)20h |
| 8 | Mobile integration | Development of mobile app for interaction with Polkadot wallets using Web API| For mobile app development (Android &amp; iOS) we will use Flutter SDK. Polkadot wallets will be integrated with C++ trustwallet/wallet-core library. Furthermore, during this step we will work on screen layouts (with previously prepared design) and adaptation for different display resolutions. | Andrey (Mobile Developer)120h |
| 9 | Testing and debugging | Performing different types of testing. Verification of the main scenarios such as sending tokens, and staking in the various environments including Ledger and Trezor wallets. | During this step, we proceed with testing, bug listing on Jira, test-cases writing. As a result, we will have a fully working product with all the crucial bugs fixed. | Alexander (QA Engineer), Aleksey (QA Engineer)40h |

### **Overview**

- Total Estimated Duration: Duration of the whole project
- Full-time equivalent (FTE): Workload of an employed person ([see](https://en.wikipedia.org/wiki/Full-time_equivalent)) - 3,0625

![](https://citadel.one/staticf/table01.png)

![](https://citadel.one/staticf/ttable2.png)

- Total Costs: 1,665 BTC

![](https://citadel.one/staticf/table003.png)

## **Future Plans**

At Citadel, we focus on providing our users with seamless crypto experience. Thus, we will continue to improve our platform, add new features and promote already integrated ones. In the coming period we are planning to become a staking derivatives gateway.

## **Additional Information**➕

_Any additional information that you think is relevant to this application that hasn&#39;t already been included._

- **What work has been done so far?**

We have an already-working product, meaning that the platform has successful integration use-cases and is ready to provide full support for Polkadot. Additionally, we are looking forward to putting our marketing efforts in order to spread a word on Polkadot.

- **Are there are any teams who have already contributed (financially) to the project?**

No

- **Have you applied for other grants so far?**

No