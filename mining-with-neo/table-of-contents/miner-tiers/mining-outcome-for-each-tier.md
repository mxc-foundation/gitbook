# ⚖ Mining Outcome for Each Tier

Mining outcomes for NEO Miner are distributed through a three-tier system: Gold, Silver, and Bronze. The amount of mining outcome received depends on the tier the miner is in and their performance. Since the specific, individual mining depends on the user’s own factors, the mining outcome may vary for all users, even if they are in the same tier.

However, the mining outcome for each tier can be estimated, since the NEO mining protocol utilizes a fixed coefficient that determines the relative ratio of each tier in the entire protocol in Total Pool allocation.

These values determine the proportions of the different pools, but the actual MXC amount distributed depends on the Total Pool (TP) and the number of miners in each tier, which both may be dynamic.

![](<../../../.gitbook/assets/image (9).png>)

Taking these coefficients into consideration, miners can use the following formula to calculate how many MXC tokens from the TP are allocated to each tier pool.

* mTier = Number of Miners (m) in Tier (tier)
* TP = Total Pool

![](<../../../.gitbook/assets/image (13).png>)

Let’s assume that the Total Pool is currently at 10,000,000 MXC (TP= 10000000), mGold = 500,  mSilver = 1500, mBronze = 500, X = 0.16, Y = 0.3, and Z = 0.54

![](<../../../.gitbook/assets/image (2).png>)

The following distribution takes place for each miner in their respective tiers, in the following average, assuming that all miners are in exact identical state.

* Bronze → 2000 MXC per miner
* Silver → 3750 MXC per miner
* Gold → 6750 MXC per miner

In conclusion, the NEO mining algorithm operates on a three-tier system: Gold, Silver, and Bronze. The amount of mining outcome a miner receives depends on their tier and performance. The actual MXC amount distributed to miners depends on the Total Utility Pool (TP), the number of miners in each tier, and most importantly the current state of each miner.

\
