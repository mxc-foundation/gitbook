# Unbonding Scenarios

Unbonding is an important concept in blockchain networks like the MXC network because it enables participants to enter and exit the network in a way that maintains the security and stability of the network.\
\
Unbonding refers to the process of miners withdrawing their bonded MXC from their current bond. There are several scenarios where unbonding can occur, such as when a miner wants to leave the network or move from one tier to another.

When a miner unbonds their MXC, they must wait for a specified period before the MXC becomes available. During the unbonding period of 17280 blocks, the miner's MXC is still considered bonded and cannot be used for anything else. Throughout the 17280 blocks, an equal portion of bonded MXC will be unbonded and become available in the user’s wallet per block.

A miner may unbond MXC from NEO tier before the bond duration has expired, However, there are also penalties associated with unbonding before the end of the bond period. The formula for calculating the penalty fee is:

![](<../../../.gitbook/assets/image (14).png>)

Where:

* s = Staked Amount
* d = Blocks in bond duration
* u = Blocks left to fulfill the bond period
* x = penalty percentage in decimal, currently set to 0.2% or 0.002

Overall, unbonding is a crucial process that miners need to be aware of if they want to leave the network or move from one tier to another. It's essential to understand the penalties and unbonding periods associated with each tier to avoid any unwanted fees or delays.

\
