# KittehCoin (2013)
> **This repository is archived.** The project continues as **[KittehCoin 2.0](https://github.com/kittehcoin/KittehCoin2.0)** (ticker **MEOWS**) at [www.kittehcoin.ca](https://www.kittehcoin.ca).
Kitteh sez MEOW.
This tree is the original KittehCoin source, last published as **0.8.6.2**. It launched around 24 December 2013 as a Scrypt coin with Kimoto Gravity Well. No premine was performed before release. The code is kept here as a historical record. It is no longer built, released, or operated.
**KittehCoin 2.0** is the same project, rewritten on current Litecoin Core: same ports, same **K** addresses, same reward schedule. It is a **new chain**, not a continuation of the 2013 ledger. Wallets, mining, and documentation live at the links below.
| | Current project |
|---|---|
| Website | https://www.kittehcoin.ca |
| Source | https://github.com/kittehcoin/KittehCoin2.0 |
| Ticker | MEOWS |
---


KittehCoin [MEOW] 0.8.6.2 with Kimoto Gravity Well
=================

Kitteh sez MEOW - visit the official bitcointalk thread at [https://bitcointalk.org/index.php?topic=1340334.0](https://bitcointalk.org/index.php?topic=1340334.0)
Coin inception was roughly December 24, 2013, 09:14:00 AM UTC, when the thread was created. No pre-mining whatsoever was performed before release.

Proof of Work: '''Scrypt'''

RPC Port '''22565'''
P2P Port '''22566'''

Root Seed(s):
dnsseed.kittehcoinblockexplorer.com


Coin parameters
---------------

Target Spacing: '''60 Seconds'''  
Target Timespan: '''Kimoto Gravity Well, min blocks @ 36 max blocks @1008'''  
Max Money: '''25,000,000,000 MEOW'''  
Minimum Transaction Fee: 1 MEOW.  


Mining reward algorithm
-----------------------

Multi-tiered reward system. Random reward amounts with a guaranteed minimum reward of 1,000 MEOW per block.
Max reward starts at 50,000 and halves every 200k blocks per tier until end of tier 3. After tier 3 halving moves to once every 100k blocks.
After tier 5 reward is fixed at 2,000 MEOW per block, plus transaction fees, until 25B MEOW is reached.


Average reward per block per tier (average = mean/tier + 10%)  

- Tier 1: 27,500  MEOW / block,  5,500,000,000 MEOW EST. TOTAL
- Tier 2: 13,750  MEOW / block,  2,750,000,000 MEOW EST. TOTAL
- Tier 3:  6,875  MEOW / block,  1,375,000,000 MEOW EST. TOTAL
- Tier 4: 3,427.5 MEOW / block,    687,000,000 MEOW EST. TOTAL
- Tier 5: 1718.75 MEOW / block,    343,500,000 MEOW EST. TOTAL

MEOW Mining Rewards Table:  

- Blocks 1 — 200,000: 1,000 – 50,000 MEOW Reward
- Blocks 200,001 — 400,000: 1,000 – 25,000 MEOW Reward
- Blocks 400,001 — 500,000: 1,000 – 12,500 MEOW Reward
- Blocks 500,001 — 600,000: 1,000 – 6,250 MEOW Reward
- Blocks 600,001 — 700,000: 1,000 – 3,125 MEOW Reward
- Blocks 700,001 + : 2,000 Reward (flat)

