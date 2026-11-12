# Blockchain Fundamentals

## What is Blockchain?
Blockchain is a decentralised digital ledger that records transactions or information in blocks linked together using cryptography. It operates across multiple computers called nodes, allowing participants to maintain and verify shared records without relying entirely on a central authority. Its structure makes unauthorised modification difficult and promotes data integrity and transparency.

## Why Is Blockchain Difficult to Modify/Change?
Blockchain is difficult to modify because of cryptographic hashing, the linking of blocks, decentralisation and consensus mechanisms. Each block has its own hash and contains the hash of the previous block, creating a connected chain. Changing information in an earlier block changes its hash and breaks the connection with subsequent blocks. Other network participants can detect invalid changes and reject them according to the network's consensus rules.

## Cryptographic Hashing
Cryptographic hashing converts input data into a fixed-length digital fingerprint using a mathematical algorithm. In blockchain, hashes help verify data integrity and detect unauthorised modifications. For example, SHA-256 produces a 256-bit hash (64 hexadecimal characters), and even a small change in the original data produces a significantly different hash. Bitcoin uses SHA-256, while Ethereum uses Keccak-256 for its standard hashing operations.

## Linking of Blocks
Blockchain consists of interconnected blocks, with each block containing transaction data, its own hash and the hash of the previous block. This creates a chronological chain where every block is linked to the one before it. If information in an earlier block is modified, its hash changes, breaking the expected connection with subsequent blocks and making the alteration detectable.

## Decentralisation
Decentralisation means that control and responsibility are distributed across multiple participants rather than being managed by one central authority. In blockchain, multiple computers called nodes maintain copies of the ledger, while network participants perform validation and consensus according to the network's rules. This reduces dependence on a single point of control.

## Consensus Mechanism
A consensus mechanism is the process through which participants in a blockchain network agree on valid transactions and the state of the blockchain. Two common mechanisms are Proof of Work (PoW), where miners compete using computational power to add blocks, and Proof of Stake (PoS), where validators stake cryptocurrency and participate in proposing and validating blocks. Consensus helps maintain agreement and security across the network.

## Why Do Hackers Target Blockchain?
Hackers target blockchain because it involves valuable digital assets, financial transactions and sensitive information. Their objectives may include stealing cryptocurrency, exploiting smart contract vulnerabilities, obtaining private keys, manipulating transactions and disrupting network operations. Common attack methods include phishing, Sybil attacks, 51% attacks, double-spending and smart contract exploits.

## What Is Ethereum?
Ethereum is a decentralised blockchain platform that allows developers to build and run applications, execute smart contracts and transfer digital assets without depending entirely on a central authority. Unlike Bitcoin, which was primarily designed as a digital currency system, Ethereum was designed to support programmable applications. Its native cryptocurrency is called Ether (ETH), which is used to pay transaction fees and participate in the network's Proof of Stake mechanism.

### What Can Ethereum Do?
- Send and receive digital currency.
- Run smart contracts.
- Support decentralised applications (DApps).
- Support decentralised finance (DeFi).
- Create and manage digital assets and tokens.

## What Is a Smart Contract?
A smart contract is a computer program deployed on a blockchain that executes predefined instructions when specified conditions are met. It operates according to rules written in code and can carry out transactions without requiring a traditional intermediary.

### Example of a Smart Contract
Imagine a buyer and seller agree to use a smart contract as an escrow service:
- The buyer sends 0.1 ETH into the smart contract.
- The contract holds the payment securely.
- Once the buyer confirms that the agreed conditions have been met, the contract releases the payment to the seller.

This demonstrates how smart contracts can automate agreements and transactions using predefined rules.
