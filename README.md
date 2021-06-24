REYN WHITEPAPER

The Reyn Protocol Whitepaper aims to educate readers on our vision, strategy and roadmap. Below we illustrate in detail our unique redistribution mechanism. 

It's an engineering achievement unheard of until now in the BSC ecosystem. We are happy to be the pioneers and are excited to showcase the new use cases that this will enable.

Safemoon was the one to bring awareness around RFI and HODL rewards. REYN will carry the innovation torch forward. We will share our vision with the world: the most complete auto-claim BNB reward mechanism.

# REYN in a nutshell

REYN is the next evolution of a yield-generating contract on the Binance Smart Chain (BSC): you get rewarded in BNB instead of tokens. 

The token contract employs a static rewards system—15% of every transaction is split in two:

- 10% BNB is redistributed to holders
- 5% is used to fuel the liquidity pool exchange growth

In order to fully understand the BNB redistribution, we need to educate you on the reflection concept:

**Classic redistribution**

This is a concept that was popularized by Safemoon. The mechanism incentivizes token holders to hold in order to earn dividends from the transactions (buys and sells). Redistribution is based on percentage (in the contract), current token balance and number of holders. 

TL; DR: *You receive more tokens automatically.*

**BNB redistribution**

Popularized by HODL and GhostFace, a transaction fee is applied to every single buy /sell order, tokens are then swapped in realtime for BNB and added to a POOL (similar to how liquidity pools work). Holders can then go to a website and manually claim the BNB earned at specific time (daily / weekly / etc..). The BNB they can collect are based on their token holdings % and the current pool size. 

TL;DR: *You hold, then go to the website and request your BNBs*

# REYN **redistribution**

Claiming manually is unintuitive for a couple of reasons:

- Need to connect your wallet manually to the website
- Time constraints as you need to return frequently to manually claim your BNBs
- Educating holders is complicated. It's difficult for them to understand the value until they go through the full claiming experience. More difficult to market.

We created a unique system that auto-claims for every single holder the amount due. We call it the **REYN PROTOCOL.**

The way it works for holders: **You buy tokens and hold them, every 60 minutes you'll automatically receive BNB in your wallet.** Not a single action is required. 

*Your REYN tokens amount is persistant and won't change.*

**Behind the scenes:**

- The contract keeps track in an array of all token holders
- The contract keeps an index into the array for processing
- Every transaction processes a certain number of users, depending on the transaction size (bigger token transfers can process more, since the gas will still be proportionally less than the value of the tokens)
- The token is based on a Dividend-Paying Token Standard, which means all BNB the contract gains will be split equally proportionally to the token holders.
- When a user is processed, the contract checks how many withdrawable dividends they have, and if it is above the minimum threshold for auto-claims, will either automatically claim those dividends for BNB, or automatically buy back tokens for them.

This system is fully automated and doesn't add minimal gas fees proportional to value transferred. The number of holders processed through each transaction is dynamic and based on transaction size. Holders will receive dividends from the queue based on their position in the array. It's a fair system, fully automated.  Minimum token balance is 10,000 Reyn tokens to receive BNB distributions.

**What if I don't want to wait?**

We will set up a function on the contract for impatient holders so they can claim manually.

# REYN **Launch**

The protocol will be launched on  Thursday 28h June, 2021 through one presale on BOUNCE.FINANCE.

- **Private + public presale**

Presale will be launched on bounce.finance. The presale link will only be sent in the telegram group with a password. 

- **DEX public listing**

Following the presale, REYN tokens will become available for purchase on PancakeSwap Exchange.

# Token Information (provisional)

**Network:** Binance Smart Chain (BEP-20)
**Ticker:** REYN
**Contract address:** 0xD5C1f636E5B65b8FBaB4C344BA45FaFCF6e9b7aC
**Decimals:** 9

🔆**TOTAL SUPPLY** : 1,000,000,000
🔆**TEAM / PARTNER Allocation**: 31,578,947 (3.1%)
🔆**TOKENS FOR PRESALE** : 518,372,093 (51.8%)
🔆 **TOKENS FOR PANCAKE LISTING** : 380,048,960 (38%)
🔆 **TOKENS FOR MARKETING WALLET**: 50,000,000 (5%)
🔆 **TOKENS FOR AIRDROP:** 20,000,000 (2%)
🔅 **Hard Cap** : 800BNB
🔅 **Presale Rate** : 610,465 per BNB
🔅 **Min./Max. Contribution** : 0.2BNB - 5BNB
🔅 **Presale Time** : 17/06 at 8PM (UTC) 
🔅 **Pancakeswap Listing Rate** : 549,418 per BNB
🔅 **Liquidity Locked: 80%** - Unlock Date : 6 months minimum

# Security of REYN

**Locked Liquidity** 
Initial liquidity will be locked for a minimum of 6 months to provide holders with peace of mind that the token can always be exchanged.  A trusted 3rd party, DXSALE, will operate as the middle man to ensure that all raised liquidity is locked in a secure locker for the full timeframe.

**Contract Audit Prior to Launch**
In an effort to increase transparency and ensure security, the team has purchased a top-tier audit with [Techrate](https://techrate.org/).  We'll be able to ensure no vulnerabilities can be found such as:

- Integer Overflow
- Integer Underflow
- Callstack Depth Attack
- Timestamp Dependency
- Parity Multisig Bug
- Transaction-Ordering Dependency

The token contract is verified and available for viewing on bscscan.

# Other features

**Anti-Dump Logic**
Price protection features such as max tx on sells are included.  Any transaction selling more than 0.1% of total supply will be rejected.  This prevents massive one time sells that drastically alter the token price.

**Extra 3% Sell fee**
Swing trading is a common practice that can affect price action. To incentivize holding and reducing pump/dump dynamics, we added an extra 3% sell fee on top of the initial 15% transaction fee. 

Total sell fee = 18% (12% BNB redistribution + 6% Liquidity pool)
