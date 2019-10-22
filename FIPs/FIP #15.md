# A Proposal to Adjust Block Missing Fault Tolerance Value

According to FIP#7 EOSFORCE Mainnet Improvement Proposal, if the node misses blocks, the stability value will be reset. However, according to the actual operation of EOSC mainnet, due to the different stability of the server network and the influence of uncontrollable human factors, the node cannot guarantee 100% stable block-producing.

So it is proposed to adjust the fault tolerance value of block missing to 3 blocks. That is, when the node does not miss more than 3 blocks, the stability of block-producing will not be reset.

Proposer: eosawake  
Proposed time: October 18, 2019
