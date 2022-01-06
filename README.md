# The PreservationDAO

## Change

We aim to preserve habitat by purchasing land of significant ecological value.

## The Way There



## Current State of the DAO

We would prefer not to rush this project, so we are currently waiting for L2s to mature before making a determination on where to launch. 


 
## Next steps: 

* setting up LLC 
* Setting up a DAO
* Discuss areas to focus on
* how do we use Ethereum




## Possible Setup for PreservationDAO
There are many ways to set up a DAO. Generally I would expect preservationDAO to govern over a treasury, so we need a government process. The DAO will also probably want to issue tokens representing the amount of land preserved from deforestation. I would suggest to following setup for doing this. This is by far not the final word on setting up preservationDAO but rather a contribution to fruitful discussions.


## PreservationDAO Governance
A general problem of governance tokens is that it invites speculators not interested in the progress of the protocol/DAO but just holding it for the sake of future gains. This leads to general low voter turnout and results in votes which can be tipped by single large actors even though they are far away from owning a majority of circulating tokens. A more detailed discussion on problem of governance is given by Vitalik Buterin on his blogpost on coin voting governance.

To prevent problems of low voter turnout and minority dominance. I would be in favor of having voting power enshrined in NFTs instead of ERC-20 tokens. Each NFT belongs to a certain address transfer can be possible, but its nature as an NFT prevents it to have a liquid token market which reduces the interest for short term speculators.

In addition participants can earn voting power by two ways. They could either:

* Participate in the daily business of the PreservationDAO help in the discussions, spread the word or with other resources. This is a personal NFT which can not be moved to another address and therefore is linked to a specific account address.
* Lock up some ETH in the DAO. The locked up ETH can be used by the DAO to earn interest on it. This interest can be spent to buy protected land (more on that later). If a user wants to leave he can receive the full initial amount by returning his NFT and by that also returning his voting rights.

Sensible time locks or a maximum voting power needs to be set for addresses depositing ETH to get voting rights. Otherwise at the evening of the vote a whale could deposit large amounts of ETH just to sway a vote in a certain direction. Quadratic voting could also be considered to limit the number of votes a single address could have. In addition we could distribute Forest tokens (see below) to all participants of a vote. This would give an additional incentive to participate in the governance.

With this approach I think we can prevent the DAO governance be captured by short term speculators and still have a relatively open governance where many can contribute. This approach also losely follows “Solution 2: non-coin-driven governance” in Vitaliks blog post.


## Forest Tokens (Tokenised Protected Land)
This would be a standard ERC-20 token which can be bought, transferred and traded on any of the decentralised exchanges. Each token would represent a certain real world asset. The easiest one to understand would be a square meter of rainforest. In reality protecting rainforest is a bit more complex than just sending money and claim it to be protected. So, maybe it needs to represent something else, like captured CO2 equivalents. BUt whatever this token represents it will fully tradeable and open to speculators. If there is high demand and the price rises above our issuance price people can buy it directly from the preservationDAO which then transfers the money to buy the land. If the price falls below our issuance price, people and companies can buy it on the secondary market.

There will be a possibility to burn your tokens to make sure they will not be resold later on. This burning would then allow the address which initiated the burning allow to claim that they protected a certain amount of land. Liquid tokens would not allow that as they can be resold to the next party.


## Revenue Channels for the DAO
The DAO would have two main revenue sources:

* A small percentage of the price of the Forest token would flow to the DAO which then can earn interest and pay for expenses. All unspent interest will be used to buy forest tokens and distributed to governance participants.
    Governance rights can be earned by locking up ETH (or other currencies) in a vault. This is fully redeemable upon exit.
There are also other possible sources of revenue which are open to discussion:

* If the price rises above our issuance price we could arbitrage the difference ourselves by minting forest tokens and sell them on AMMs (e.g. Uniswap) above the issuance price. This will only be possible as long as MEV extractors have not found this opportunity.
    We could use some of the Forest tokens which the DAO buys for governance participants to provide liquidity in one of the pools itself and earn additional interest on it.

I think the DAO will have minimal expenses anyway but it might become necessary to pay for audits and such for the attached LLC.


## Advantages Disadvantages of this Approach
Disadvantages

* Not having a token airdrop will definitely reduce the buzz we will get from the Crypto space.
* Complex governance structure. 1 token 1 vote is a very simple concept.
* We cannot use governance tokens to pay for expenses.

Advantages

* Possibility of having a sustainable governance process.
* By allowing contributors having a vote we will be able to get interested parties more involved in the preservationDAO and its goal.
* Slow and steady growth will make it possible to adjust course if a problem arises before the problem gets to large.
* We well be able to attract people which want to contribute without them having to spend small fortunes on governance tokens.


## TLDR (Too long did not read)
PreservationDAO issued NFTs can be used to make governance more sustainable and the issued Forrest token will be tokenised protected land.


CREDIT: https://hackmd.io/@haurog/BkW8kuiFY



## Which Network to Choose for PreservationDAO
At the moment Ethereum is in rapid change. The high fees push low value transactions out of the main chain (L1) into rollups (L2) or sidechains. There are a lot of promising candidates onto which we could deploy the PreservationDAO each with their own advantages and disadvantages. Here I list some of the candidates with their respective pros and cons. The ones I mention here are the ones which I used and interacted with. I think I listed the most reliable general purpose options here. There are many other rollups and sidechains listed on L2beat which are not discussed here as they will have to prove themselves to be more than just short lived incentivised cash grab.


## Ethereum Main Chain
Pros

* Most neutral layer
* Proven to be stable and reliable
* many projects run on it -> many yield farming opportunities
* all DAO tools support the main layer
* many offramps

Cons

* Too expensive to start anything small
* Future will not be on this layer
* Still running on Proof of Work (Might be attacked for being on the wasteful L1)

-> Not ideal candidate


## Arbitrum
Pros

* Already a lot of projects deployed -> Yield farming possibilities
* Fraud proof system is implemented (Funds should be safe.)
* some offramps support it

Cons

* Block producers are centralized
* More expensive than Optimism -> An upcoming update should improve that.

They had a short (less than 1 hour) outage in September and are running reliably since then.

-> Good candidate


## Optimism
Pros

* Cheaper than Arbitrum

Cons

*  Block producers are centralised.
*  Fraud Proofs still not implemented.
*  Not many projects deployed.
*  Sequencer went down during Lyra airdrop/claim -> still early.

The only advantage optimism has over arbitrum is that it is cheaper,otherwise it is behind arbitrum in every metric.

-> Not better than Arbitrum


## Polygon
Pros

* Very cheap to use
* KlimaDAO is on it -> Gives the layer good credibility
* A lot of projects are on it -> yield farming
* Running for about a year now
* some offramps support it

Cons

* Not a rollup, rather sidechain like -> they want to move to a rollup in the future.
* Highly centralized -> They want to move to a rollup in the future.

I am using polygon regularly even though I am personally not a big fan of them. Their whole story of “We are a rollup” rubbed me the wrong way and in my book it was a pretty shady tactics when they turned a lot of crypto OGs into advertisers for them by giving them a seat on their board. In the last months they redeemed themselves by offering a reliable sidechain with a lot of traction. And their goal of turning polygon into a zk rollup when they are ready is very promising. Their recent hack however, leaves a few question marks for me and I am not so sure about the competence of their dev team.

-> Good candidate


## Starknet
Pros

* Proper ZK rollup
* Fast and crazily cheap

Cons

* Still in alpha stage.
* No DAO tools -> Everything would need to be programmed by us.
* Programming toolchains are also in alpha stage
* Cannot send ETH to Starknet on the mainnet at the moment.

I played with the Network on the testnet as well as on the mainnet, deployed some dummy contracts and tried (and failed) to set up my local IDE to program a contract locally. All in all I think they are promising, but pretty far away from usable.

-> Not usable now


## ZKsync
Pros

* Proper ZK rollup
* Fast and Crazily cheap (zkporter will make transactions cost almost nothing)
* V1 is running for over a year now

Cons

* No smart contracts on V1 -> should follow soon, but is delayed by several months now.

Their V1 payment layer is extremely good and reliable. Unfortunately the smart contracts (V2) are still missing.

-> Not usable now


## Conclusion
The best candidates we have is either Arbitrum or Polygon. The best one in my opinion is Polygon even though it is personally not my favorite it has the most traction at the moment. In the end, the choice between the two probably depends on available DAO toolings on each chain. This conclusion might change as soon as some large exchanges support on-/offramps to any of these rollups/sidechains and any of those start with token incentivised yield farming.

CREDIT: https://hackmd.io/@haurog/rJNsOVCst



## DAO tools
Here I mention tools that are available for DAOs to align their members and come to an agreement over the direction the DAO has to go. This list is definitely incomplete and we also do not need all the tools now. Some tools work better for small DAOs, some better for large DAOs and some are only needed if the DAO is more like a company with paid workers. This overview should help to guide us what is here and what we could pick. A part of the following lists is based on the blog post by Nichinan Kesonpat: Organization Legos.


## Discussion and Votes
* Discord: for fast everyday discussions, small talk and alignments. Centralized and possible to censor, but probably ok for us. Later on we might need to separate the everyday chitchat and the proposal focused discussions. Good for simple signal voting as well.
* Discourse: More focused discussion of improvement proposals. General forum. For signal voting.
* Snapshot: To vote on proposals. In my impression a lot of DAOs use snapshot. It is a signal voting which after which an on-chain voting happens or a multisig acts upon it.
* Tally: Good for the last step. The on-chain voting.
* Boardroom: Good aggregator for various DAOs, their proposals and on-chain voting results. Might do more, but I am not sure about it


## DAO Frameworks and Tools
* Moloch: Widely used. Can be spun up using daohaus. Daohaus supports Arbitrum and Polygon. Everything looks a bit self made. Not bad it just has a bit of a DIY feel to it. Seems to work well with Gnosis safe through the safeminion module.
* Aragon: Various DAO types are possible. A reputation based one might be the meet our needs perfectly. They provide pretty much everything you need. Feels overwhelming but looks quite professional. Long term looks like the most promising option.
-> not on Arbitrum, but possible on Polygon
* Openzeppelin Governor: Don’t know how many DAOs use it. Can be spun up easily, but it is not so obvious to me what these options do.
* Colony: Not as widely used. Looks quite nice. On XDAI and mainnet only.
* DAOStack: Not as widely used. Simple but nice. XDAI and mainnet only.
* Gnosis safe: multisig wallet (needed to sign transactions) -> With their bridge tool we can control funds on any EVM compatible (supported) network. Pretty much every EVM network is supported. Creation costs about 0.01 ETH (on Arbitrum) depending on the number of accounts in the multisig.
* Gnosis safesnap (Now called “Reality”): Part of the Gnosis safe with the Zodiac modules. Automated sending of transactions depending on (off-chain) governance outcome.
* Gnosis Zodiac: Part of Gnosis Safe. Modules to extend the multisig wallet with DAO focused functionalities.


## People Focused Tools
* Coordinape: Tool gauge and see who interacts with whom and get a quantitative basis to hand out rewards.
* Opolis: If people of a DAO need Payroll and Benefits (US only).


## Managing a DAO
* The overview from the Consensys Blockchain Bootcamp is quite comprehensive.


## Conclusion
For serious DAOs it looks like there is no way around Aragon. It looks professional, suitable for many different DAOs and easy to maintain. For us it might be too early, especially if we want to keep to Arbitrum.

To me it looks like Gnosis safe and their additional modules are perfect and will allow us to move forward for quite some time. As far as I understand, the Gnosis framework is very modular and being built right now. So maybe new modules will become available in time during our growth.

A problem with this approach is that an already deployed ERC-20 (forest token) might not be easily integrated into a DAO framewrok deployed at a later state. So we will probably have to choose the FAO framework at the time we deploy our ERC-20. But maybe the forest token also does not need to be part of the DAO framework.

CREDIT: https://hackmd.io/@haurog/rJ52dNgnF
