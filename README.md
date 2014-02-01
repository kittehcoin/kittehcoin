KittehCoin [MEOW] 0.6.3.1
=================

Kitteh sez MEOW - visit the official bitcointalk thread at [https://bitcointalk.org/index.php?topic=383068.0](https://bitcointalk.org/index.php?topic=383068.0)

Coin inception was roughly December 24, 2013, 09:14:00 AM UTC, when the thread was created. No pre-mining whatsoever was performed before release.

Proof of Work: '''Scrypt'''

RPC Port '''22565'''
P2P Port '''22566'''


New v0.7.0 clients can be found in the release/ folder of this repository.


Known Alive Peers
-----------------


Coin parameters
---------------

Target Spacing: '''60 Seconds'''
Target Timespan: '''1 hours'''  
Max Money: '''25,000,000,000 MEOW'''
Minimum Transaction Fee: 1 MEOW.


Mining reward algorithm
-----------------------

Multi-tiered reward system. Random reward amounts with a guaranteed minimum reward of 1,000 MEOW per block. Max reward starts at 100,000 and halves per tier until end of tier 6. 200,000 blocks per reward tier up to block 1,200,001. Reward is then fixed at 1,000 MEOW per block, plus transaction fees, until Max Money is reached.


Average reward per block per tier (average = mean/tier + 10%)  

Tier 1: 27,500  MEOW / block,  5,500,000,000 MEOW EST. TOTAL
Tier 2: 13,750  MEOW / block,  2,750,000,000 MEOW EST. TOTAL
Tier 3:  6,875  MEOW / block,  1,375,000,000 MEOW EST. TOTAL
Tier 4: 3,427.5 MEOW / block,    687,000,000 MEOW EST. TOTAL
Tier 5: 1718.75 MEOW / block,    343,500,000 MEOW EST. TOTAL
Tier 6: 1717.75 MEOW / block,    171,500,000 MEOW EST. TOTAL

Estimated time to block 800,001  (@ 60 seconds per block):  555.55 days

MEOW Mining Rewards Table:  

Blocks 1 — 200,000: 1,000 – 50,000 MEOW Reward
Blocks 200,001 — 400,000: 1,000 – 25,000 MEOW Reward
Blocks 400,001 — 500,000: 1,000 – 12,500 MEOW Reward
Blocks 500,001 — 600,000: 1,000 – 6,250 MEOW Reward
Blocks 600,001 — 700,000: 1,000 – 3,125 MEOW Reward
Blocks 700,001 — 800,000: 1,000 – 1,561 MEOW Reward
Blocks 800,001+ — 2,000 Reward (flat)

