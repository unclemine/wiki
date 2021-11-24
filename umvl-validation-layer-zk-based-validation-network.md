# UMVL (Validation Layer) - ZK Based Validation Network

UMVL continuously generates simple zero-knowledge proofs through decentralized nodes to prove the existence of computing power. For the generation and verification scheme of the proof of computing power, please see our research paper:

[https://docsend.com/view/yk7u6azcwdjep4md](https://docsend.com/view/yk7u6azcwdjep4md)

[https://docsend.com/view/tirqvgrpwknixc4d](https://docsend.com/view/tirqvgrpwknixc4d)

Since the proof of computing power is generated off-chain and cannot be used directly by smart contracts, we also need a set of middleware tools to credibly transmit the generated proofs to the chain. We call this the computing power oracle. The UM computing power oracle is the interface between the off-chain computing power proof and the on-chain smart contract. It consists of a series of APIs and smart contracts. First of all, the computing power oracle uses the computing power proof generated by the off-chain nodes as input, and through the collaboration between the nodes, the credible proof is transmitted to the specified on-chain contract in real-time.

Any user can prove that the holder of a certain address has a specific amount and type of computing power running by reading the on-chain data.

Third-party applications can integrate these proof data into their own business logic to build various decentralized applications centered on computing power resources and computing power assets. In addition, UMVL can also accept feedback input from other smart contracts, thereby generating feedback signals on the real-world computing power and guiding the allocation of computing power resources off the chain.