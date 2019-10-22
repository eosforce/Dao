# About the Modification to Adjust Node Block-Producing Stability Value

According to EOSForce Mainnet Improvement Proposal FIP#7, the block-producing reward matters a great deal to the block-producing stability. And this is why recently some nodes produce blocks normally but only gain little profit. After missing blocks, the stability value will be reset to 1000, while the stability value of other nodes is up to 4800, so there will be a gap of nearly 5 times in block-producing. It is stipulated in the contract that 1 will be added with no block missing within each cycle of 207 blocks. According to this calculation, it takes 27 days to reach the uppermost stability value after the block missing.

In fact, the deployments of different nodes is different, the stability of different server networks is different, the network itself is not 100% usable, and the stability of the network can’t be controlled by the nodes. Currently, TPS on EOSC mainnet has not reached a certain magnitude. At this stage, the requirement for 27 days is unreasonable. It is proposed to modify the stability value to 2000 to make the profits of the stably block-producing nodes double that of the profits of the block-missing nodes. After the modification, it takes 7 days to reach the uppermost stability value after the block missing.

Proposer: eosawake  
Proposal time: 2011.10.12
