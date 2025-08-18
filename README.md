# Simple Blockchain Project

## Overview
This is a simple blockchain application implemented in Python. It demonstrates the core concepts of blockchain technology including:

- Creating blocks
- Linking blocks via hashes
- Validating the integrity of the blockchain

The project was created for the INFO6001: Blockchain Technology and Applications assessment at Southern Cross University.

---

## Features
- **Genesis Block Creation:** The first block in the chain.
- **Add New Blocks:** Users can input custom data to create new blocks.
- **Hash Linking:** Each block stores the hash of the previous block to maintain the chain.
- **Blockchain Display:** View all blocks with their timestamps, data, hashes, and previous hashes.
- **Blockchain Validation:** Verify if any block has been tampered with.
- **Interactive Menu:** Add blocks, display blockchain, validate, or exit the program.

---

## How to Run
1. Clone this repository:
   
```bash
git clone https://github.com/Enyi10/simple-blockchain.git

3. Navigate to the project directory:

```bash
cd simple-blockchain

3.Run the blockchain application:

```bash
python blockchain.py

Example Outputs
Step 1 – Genesis Block Creation

When the program first runs, the Genesis Block is created automatically:

Genesis Block created!
Block 0 [Timestamp: 2025-08-17 12:00:00]
Data: Genesis Block
Hash: 6d8a1c8e9b93f2e9b6b5a6a8d7d2e9d6a7b9c3d1e0a1f2c3b4d5e6f7a8b9c0d1
Previous Hash: 0

Step 2 – Adding New Blocks

When a user adds new data, the chain updates:

New Block added!
Block 1 [Timestamp: 2025-08-17 12:05:00]
Data: First transaction data
Hash: 3a6b1c9d7e2f8a0b6c1d9a3f5b7c8d2e1f4a3c6e8b9d0f2a1b3c5d7e9f0a2b3c
Previous Hash: 6d8a1c8e9b93f2e9b6b5a6a8d7d2e9d6a7b9c3d1e0a1f2c3b4d5e6f7a8b9c0d1

New Block added!
Block 2 [Timestamp: 2025-08-17 12:10:00]
Data: Second transaction data
Hash: 4b7c2d8e9f1a3b5c7d8e9f0a1b2c3d4e5f6a7b8c9d0e1f2a3b4c5d6e7f8a9b0c
Previous Hash: 3a6b1c9d7e2f8a0b6c1d9a3f5b7c8d2e1f4a3c6e8b9d0f2a1b3c5d7e9f0a2b3c

Step 3 – Display Blockchain

Selecting the option to display shows the full chain:

Block 0 [Timestamp: 2025-08-17 12:00:00]
Data: Genesis Block
Hash: 6d8a1c8e9b93f2e9b6b5a6a8d7d2e9d6a7b9c3d1e0a1f2c3b4d5e6f7a8b9c0d1
Previous Hash: 0

Block 1 [Timestamp: 2025-08-17 12:05:00]
Data: First transaction data
Hash: 3a6b1c9d7e2f8a0b6c1d9a3f5b7c8d2e1f4a3c6e8b9d0f2a1b3c5d7e9f0a2b3c
Previous Hash: 6d8a1c8e9b93f2e9b6b5a6a8d7d2e9d6a7b9c3d1e0a1f2c3b4d5e6f7a8b9c0d1

Block 2 [Timestamp: 2025-08-17 12:10:00]
Data: Second transaction data
Hash: 4b7c2d8e9f1a3b5c7d8e9f0a1b2c3d4e5f6a7b8c9d0e1f2a3b4c5d6e7f8a9b0c
Previous Hash: 3a6b1c9d7e2f8a0b6c1d9a3f5b7c8d2e1f4a3c6e8b9d0f2a1b3c5d7e9f0a2b3c

Step 4 – Blockchain Validation

When checking validity:

Blockchain is valid ✅


If someone tampers with a block’s data:

Blockchain is invalid ❌
