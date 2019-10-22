# Improve node information and adjust node penalty rule

### Proposal 1:
Please complete the account information content of the bpinfo contract by each node, which can be completed in the BP management platform:
1. The node account information will be displayed on the wallet and browser, which is convenient for the user to have a comprehensive understanding of the node.
2. The extension field needs to fill in the bp.json content. The bp.json content contains the P2P node information of the primary network and the P2P node information of the test network.Each node needs to actively open P2P nodes for cross-connection between nodes to maintain stable operation of the EOSC main network.The existence of the test network is the guarantee of the security and success of the upgrade of the main network, so the test network is also important.Because the P2P node information is publicly available, in order to ensure the security of the server, each node server needs to enable the IP whitelist and open access only to the P2P node IP. This means that the server without the P2P node cannot connect to the primary network and cannot continue to produce blocks.In addition, relevant detection tools will be developed to detect the availability of P2P nodes in real time. When the P2P nodes are unable to connect, the Secretariat will notify the relevant nodes and urge them to recover as soon as possible.After the P2P node replaces the IP, it is necessary to update the bpinfo contract record in time.

### Proposal 2:
After a period of testing, the node penalty function found that the current rule "16 votes pass" operation is difficult to practice. Since the node penalty is supervised, it is not necessary to require more than 2/3 nodes to pass, and it is proposed to pass more than 1/2 node (12 votes) to improve the operability of this function.

proposalSponsor: eosawake   
Proposal time: 2011.10.11
