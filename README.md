# Blockchain-simulation
Objective:
Build a simple blockchain consisting of 3 linked blocks to understand how blockchains maintain data integrity.

Features:

Block class with:

index

timestamp

data

previousHash

hash

nonce

Uses SHA-256 for hash generation.

Each block’s previousHash points to the hash of the previous block.

Displays all blocks with their details and hashes.

Tampering Demonstration:

After building the chain, change the data in Block 1.

Recalculate its hash.

Observe how all subsequent blocks become invalid unless their hashes are recomputed.

Highlights the importance of data immutability in blockchains.

Goal:
Understand how modifying a single block affects the entire chain’s integrity.















