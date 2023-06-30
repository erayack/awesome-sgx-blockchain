[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![hackmd-github-sync-badge](https://hackmd.io/OTK1dtKORwSIfEYazin4qw/badge)](https://hackmd.io/OTK1dtKORwSIfEYazin4qw)

## Introduction
Welcome to the "Awesome SGX and TEE in Blockchain Resources" repository! This repository is a curated collection of valuable resources related to Intel Software Guard Extensions (SGX) and Trusted Execution Environments (TEE) in the context of blockchain technology.
SGX and TEE are technologies that provide secure execution environments for sensitive computations within the blockchain. They enable the protection of confidential data and the execution of trusted code, enhancing the security and privacy of blockchain applications.

In this repository, you will find a wide range of resources, including research papers, articles, tutorials, libraries, and projects focused on SGX and TEE integration in blockchain. These resources cover topics such as:


1. Introduction to SGX and TEE: Learn about the fundamentals of SGX and TEE technologies, their features, and how they can be leveraged in blockchain applications.
2. SGX and TEE in Blockchain Architecture: Explore different architectural patterns and design considerations for integrating SGX and TEE into blockchain networks, ensuring secure and trusted execution of smart contracts and sensitive operations.
3 . Development Tools and Libraries: Discover open-source libraries, frameworks, and development tools that facilitate the integration of SGX and TEE into blockchain applications. These resources can help you build secure and privacy-preserving decentralized applications.
4. Use Cases and Applications: Explore real-world use cases and applications that demonstrate the benefits of SGX and TEE in blockchain, such as secure data sharing, confidential transactions, and privacy-preserving smart contracts.

Trusted Execution Environments (TEEs) and SGX (Software Guard Extensions) plays a critical role in enhancing security by offering hardware-based memory encryption and isolation. SGX allows user-level code to allocate private regions of memory called enclaves, which are designed to be protected from processes running at higher privilege levels. This granular level of control and protection applies to other high-level processes running at the time, and even the operating system. By leveraging SGX, developers can enhance the security of their applications and protect sensitive code and data from unauthorized access.

TEEs and Intel SGX have various use cases in blockchain technology. They enable secure smart contract execution, ensuring the protection of sensitive data and logic. TEEs also facilitate confidential transactions, preserving privacy and confidentiality. Additionally, TEEs support privacy-preserving data analytics and secure oracles, ensuring data integrity and confidentiality. They can also play a role in decentralized identity systems, securely managing private keys and enabling secure authentication on the blockchain.


## Blogs & Writings
* [The Sting Framework (SF)](https://initc3org.medium.com/the-sting-framework-sf-ef00702c88c7)
* [PROF: Fair Transaction-Ordering in a Profit-Seeking World](https://initc3org.medium.com/prof-fair-transaction-ordering-in-a-profit-seeking-world-b6dadd71f086)
* [Block Building inside SGX](https://writings.flashbots.net/block-building-inside-sgx)
* [Running Geth within SGX: Our Experience, Learnings and Code](https://writings.flashbots.net/geth-inside-sgx)
* [SGX-Based Backrunning and Covert Channels](https://writings.flashbots.net/backrunning-private-txs-MPC#sgx-based-backrunning-and-covert-channels)
* [TEE-based Smart Contracts and Sealing Pitfalls](https://medium.com/initc3org/tee-based-smart-contracts-and-sealing-pitfalls-eccd5d751329)
* [MEV-SGX -- A sealed bid MEV auction design](https://ethresear.ch/t/mev-sgx-a-sealed-bid-mev-auction-design/9677)
* [Avalanche Bridge: Secure Cross-Chain Asset Transfers Using Intel SGX](https://medium.com/avalancheavax/avalanche-bridge-secure-cross-chain-asset-transfers-using-intel-sgx-b04f5a4c7ad1)
* [SUAVE Andromeda and Helios ](https://writings.flashbots.net/the-future-of-mev-is-suave#-suave-andromeda)
* [Blockchains + TEEs Day 1 Summary](https://decentralizedthoughts.github.io/2023-04-09-blockchainsplustees-day1-summary/)
* [Blockchains + TEEs Day 2 Summary](https://decentralizedthoughts.github.io/2023-04-17-blockchainsplustees-day2-summary/)
* [Blockchains in Trusted Execution Environments (TEEs)](https://medium.com/@nadeem.bhati/blockchains-in-trusted-execution-environments-tees-9343b6c3f9e8)
* [Intel® SGX and Blockchain: The iExec End-to-End Trusted Execution Solution](https://medium.com/iex-ec/iexec-end-to-end-sgx-solution-fee1e63297b2)
* [Why trusted execution environments will be integral to proof-of-stake blockchains](https://venturebeat.com/datadecisionmakers/why-trusted-execution-environments-will-be-integral-to-proof-of-stake-blockchains/)
* [4 Ways to Compare Trusted Execution Environments and Zero-Knowledge Proofs](https://oasisprotocol.org/blog/comparing-zkp-tee-privacy)
* [Trusted Execution Environments and the Polkadot Ecosystem](https://polkadot.network/blog/trusted-execution-environments-and-the-polkadot-ecosystem)
* [How Intel® SGX is hardening data privacy on the blockchain](https://www.intel.co.uk/content/www/uk/en/architecture-and-technology/software-guard-extensions/applied-blockchain-sgx-story.html)
* [How Secret Network Uses SGX](https://docs.scrt.network/secret-network-documentation/overview-ecosystem-and-technology/techstack/privacy-technology/intel-sgx/overview)


## Papers
* [Intel SGX Explained](https://css.csail.mit.edu/6.858/2020/readings/costan-sgx.pdf)
* [SoK: TEE-assisted Confidential Smart Contract](https://arxiv.org/pdf/2203.08548.pdf)
* [When Blockchain Meets SGX: An Overview, Challenges, and Open Issues](https://ieeexplore.ieee.org/document/9197584)
* [TEBDS: A Trusted Execution Environment-and-Blockchain-supported IoT data sharing system](https://www.sciencedirect.com/science/article/abs/pii/S0167739X22003326)
* [Lessons Learned from Blockchain Applications of Trusted Execution Environments and Implications for Future Research](https://arxiv.org/pdf/2203.12724.pdf)
* [A Blockchain Based on Gossip](https://www.zurich.ibm.com/dccl/papers/renesse_dccl.pdf)
* [Blockchain and Trusted Computing: Problems, Pitfalls, and a Solution for Hyperledger Fabric](https://arxiv.org/pdf/1805.08541.pdf)
* [Security with Intel SGX: Enhancements, Applications and Privacy](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/315410/Matetic-thesis-final-13122018-withoutCV.pdf?sequence=1&isAllowed=y)
* [SGXonerated: Finding (and Partially Fixing) Privacy Flawsin TEE based Smart Contract Platforms Without Breaking the TEE](https://eprint.iacr.org/2023/378.pdf)
* [Town Crier: An Authenticated Data Feed for Smart Contracts](https://eprint.iacr.org/2016/168.pdf)
* [Teechain:Scalable Blockchain Payments using Trusted Execution Environments](https://www.doc.ic.ac.uk/~fkelbert/papers/teechainarxiv17.pdf)
* [LucidiTEE: A TEE-Blockchain System for Policy-Compliant Multiparty Computation with Fairness](https://eprint.iacr.org/2019/178)
* [Hawk: The Blockchain Model of Cryptography and Privacy-Preserving Smart Contracts](https://eprint.iacr.org/2015/675.pdf)
* [PoQ: A Consensus Protocol for Private Blockchains Using Intel SGX](https://cs.boisestate.edu/~gdagher/pub/GD_PoQ_SecureComm_2020.pdf)
* *[General SGX-related papers from various topics, such as cloud computing, operating systems, and others.](https://github.com/vschiavoni/sgx-papers#sgx-papers)*

## Slides
* [SGX and cryptocurrencies](https://www.initc3.org/files/retreat/sgx_contracts.pdf)
* [SUAVE smart contract programming model:
 TEE-based smart contracts for block building](https://docs.google.com/presentation/d/18Fc1_TfMW3BEi_GF0YJtyrNyU1c2r9989WM9nC6-QtE/edit#slide=id.g225be28fa40_2_76)


## Useful Websites
* [sgx.fail](https://sgx.fail/)
* [Town Crier: An Authenticated Data Feed for Smart Contract](http://town-crier.org) 


## Codes & Repos
* [geth-sgx-gramine](https://github.com/flashbots/geth-sgx-gramine) - Geth (Go-Ethereum)-in-SGX provides an example of running go-ethereum in SGX by Flashbots.
* [FHE-in-TEE](https://github.com/MarbleHE/FHE-in-TEE) - A framework to run Fully Homomorphic Encryption (FHE) computations (especially using the SEAL library) on Trusted Execution Environments (TEEs). This framework also includes a scheme to verifiably offload some computations to untrusted hardware for faster evaluation.
* [Ledger BOLOS](https://github.com/LedgerHQ/bolos-enclave) - A simple, portable and flexible Trusted Computing Base environment for blockchain applications.
* [luckychain/lucky](https://github.com/luckychain/lucky) - Proof of luck Intel SGX and IPFS based blockchain.
* [Town Crier](https://github.com/bl4ck5un/Town-Crier) - Town Crier: an Authenticated Data Feeds for Smart Contracts 
* [infobiac/eEVM](https://github.com/infobiac/eEVM) - Enclave ready EVM (eEVM) is an open-source, standalone, embeddable, C++ implementation of the Ethereum Virtual Machine. http://microsoft.com/blockchain  
* [hyperledger-labs/fabric-private-chaincode](https://github.com/hyperledger-labs/fabric-private-chaincode) - This lab enables Secure Chaincode Execution using Intel SGX for Hyperledger Fabric. 
* [hyperledger/avalon](https://github.com/hyperledger/avalon) - Hyperledger Avalon (formerly Trusted Compute Framework)
* [smartcontractkit chainlink](https://github.com/smartcontractkit/chainlink) - node of the decentralized oracle network, bridging on and off-chain computation. 
* [skalenetwork/sgxwallet](https://github.com/skalenetwork/sgxwallet) - sgxwallet is the first-ever opensource high-performance hardware secure crypto wallet that is based on Intel SGX technology. 
* [Secret Network](https://github.com/enigmampc/SecretNetwork) - Secret Network is the first blockchain with data privacy by default for smart contracts and entirely based on Intel SGX technology. https://scrt.network/
* [phala-blockchain](https://github.com/Phala-Network/phala-blockchain) - Phala Network is a blockchain-based confidential computing cloud.
* [substraTEE](https://github.com/integritee-network/substraTEE) - Trusted Off-Chain Compute Framework for substrate blockchains
* [automata](https://github.com/automata-network/automata) - Web 3.0 Realized with Traceless Privacy and Seamless Compatibility.

## Videos & Talks & Workshops
* [Private Smart Contracts are Worth the Price of the SGX, Andrew Miller](https://www.youtube.com/watch?v=L0bp6V1pn0s)
* [SGX Panel: Andrew Miller, Jonathan Passerat Palmbach, Phil Daian, Justin Drake](https://youtu.be/vokDXJmPCSI)
* [Enabling Cross Chain Transfers Using SGX](https://youtu.be/f2bU55ngO_c)
* [Blockchains + TEEs: Day 1](https://youtu.be/9-nhNQO5_Js)
* [Blockchains + TEEs: Day 2](https://youtu.be/zIU3gFTb2PM)

## Other
* [SGX Block Builder on Etherscan](https://etherscan.io/address/0xc83dad6e38bf7f2d79f2a51dd3c4be3f530965d6)
