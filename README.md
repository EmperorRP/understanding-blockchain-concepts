# Basics of blockchain in layman terms
(Blockchain Theory) and protocols such as proof-of-work, proof-of-stake, liquidity pools, DEXs, Block construction, TX propagation and mempool, Nodes and clients, other EVM blockchains, AMMs, lending, collateral, staking, and DeFi protocols

This repo is supposed to be a blog style repo explaining blockchain concepts in a simple manner, in my own terms. Star this repo if you find it useful!

## What is cryptocurrency?
Cryptocurrency is a token, it is a token that can be used like normal currency but through the internet, worldwide. It is a technology that is powered by blockchain. It uses cryptography to carry out secure transactions digitally. 

## What is blockchain?
Like the name says, it is a chain of blocks. Every block consists of transactions and tracks assets. It is a database that is shared across all the nodes connected to the blockchain. Blockchain is mainly used for security and openness of transactions.
PS: haters call it is a glorified global linked list 

## How is a block constructed?
The goal of a blockchain is to expand itself by adding more blocks at the end. At the end, once a block is added, it is difficult to change the blockchain contents and state of the previous blocks unless a common consensus has been achieved. Depending on the protocol, this is how the next block is constructed: 

1. __PoW or Proof of Work__
> If miners solve a complex math problem with the help of cryptography. Once solved, the block is available for transactions and the miner is rewarded with cryptocurrency. 

2. __PoS or Proof of Stake__
> Based on an individual’s stake, a validator is chosen at random and makes cryptocurrency transactions to add a new block to the blockchain. Much more cost efficient and energy efficient than PoW.


## What are nodes and clients?
Clients, especially in Ethereum refer to software program that holds all the info about all transactions to ensure security of the data. Nodes are computers that are connected together on the blockchain and run the same client.

## What is transaction propagation?

## What’s a mempool ?
A mempool is short for memory pools. It can be considered a “waiting area” for transactions on the blockchain. For example, let’s suppose that A wants to send some ETH to B on Ethereum. This transaction doesn’t happen directly, instead, there is some waiting time during which the transactions are getting verified and validated. These transactions are stored temporarily in the mempool and that’s when they get verified. Once verified, the transaction becomes successful. 

## What is Bitcoin?
Bitcoin is a blockchain network that enables users to do peer to peer transactions which means that people can use the cryptocurrency as an alternative to cash payments digitally.
