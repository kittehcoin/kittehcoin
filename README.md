KittehCoin [MEOW]
=================

Kitteh sez MEOW - visit the official bitcointalk thread at [https://bitcointalk.org/index.php?topic=383068.0](https://bitcointalk.org/index.php?topic=383068.0)

Coin inception was roughly December 24, 2013, 09:14:00 AM UTC, when the thread was created. No pre-mining whatsoever was performed before release.

Proof of Work: '''Scrypt'''

RPC Port '''22565'''
P2P Port '''22566'''


New v0.7.0 clients can be found in the release/ folder of this repository.


Known Alive Peers
-----------------

Dec 31st 2013
198.199.117.221:22566
75.187.169.137:22566
23.247.148.108:22566
31.17.57.59:22566
123.247.148.108:22566
74.102.174.137:22566
218.215.236.104:22566

Dec 29th 2013
198.199.117.221:22566
24.184.43.249:22566
78.188.9.117:22566
24.125.252.211:22566
93.78.120.235:22566
120.147.85.204:22566
27.33.1.58:22566
31.17.57.59:22566


Coin parameters
---------------

Target Spacing: '''30 Seconds'''  
Target Timespan: '''1 hours'''  
Max Money: '''50,000,000,000 MEOW'''  
Minimum Transaction Fee: 1 MEOW.


Mining reward algorithm
-----------------------

Multi-tiered reward system. Random reward amounts with a guaranteed minimum reward of 1,000 MEOW per block. Max reward starts at 100,000 and halves per tier until end of tier 6. 200,000 blocks per reward tier up to block 1,200,001. Reward is then fixed at 1,000 MEOW per block, plus transaction fees, until Max Money is reached.


Average reward per block per tier (average = mean/tier + 10%)  

Tier 1: 55,000  MEOW / block, 11,000,000,000 MEOW EST. TOTAL  
Tier 2: 27,500  MEOW / block,  5,500,000,000 MEOW EST. TOTAL  
Tier 3: 13,750  MEOW / block,  2,750,000,000 MEOW EST. TOTAL  
Tier 4:  6,875  MEOW / block,  1,375,000,000 MEOW EST. TOTAL  
Tier 5: 3,437.5 MEOW / block,    687,500,000 MEOW EST. TOTAL  
Tier 6: 1718.75 MEOW / block,    343,750,000 MEOW EST. TOTAL  

Estimated time to block 1,200,001  (@ 30 seconds per block):  416.66 days 

Estimated amount MEOW minted by block 1,200,001: 21,656,250,000 MEOW  
Maximum possible MEOW minted by block 1,200,001: 39,375,000,000 MEOW  
Minimum possible MEOW minter by block 1,200,001:  1,200,000,000 MEOW  

MEOW Mining Rewards Table:  

Blocks         1 — 200,000:   1,000 - 100,000 MEOW  
Blocks   200,001 — 400,000:   1,000 -  50,000 MEOW  
Blocks   400,001 — 600,000:   1,000 -  25,000 MEOW  
Blocks   600,001 — 800,000:   1,000 -  12,500 MEOW  
Blocks   800,001 — 1,000,000: 1,000 -   6,250 MEOW  
Blocks 1,000,001 — 1,200,000: 1,000 -   3,125 MEOW  
Blocks 1,200,001 — MAX_COINS:           1,000 MEOW  

