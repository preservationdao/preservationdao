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
