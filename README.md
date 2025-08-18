
-----

# Simple Blockchain Project

## Overview

This Python-based application demonstrates the fundamental concepts of blockchain technology. The project was developed for the **INFO6001: Blockchain Technology and Applications** unit at Southern Cross University. It showcases key principles such as block creation, cryptographic linking, and chain validation.

-----

## Features

  * **Block Generation:** The application automatically creates a genesis block and allows users to append new blocks to the chain.
  * **Cryptographic Integrity:** Each block is linked to the previous one using its unique hash, forming a secure and tamper-evident chain.
  * **Data Validation:** A built-in function verifies the entire blockchain to detect any unauthorized modifications to the blocks or their data.
  * **Interactive Interface:** A simple command-line menu guides the user to perform various actions, including adding data, viewing the chain, and validating its integrity.

-----

## How to Run

1.  **Clone the repository from GitHub:**

    ```bash
    git clone https://github.com/Enyi10/simple-blockchain.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd simple-blockchain
    ```

3.  **Execute the Python script:**

    ```bash
    python blockchain.py
    ```

-----

## Example Outputs

### Step 1 – Genesis Block Creation

The program initializes by generating the first block:

```
✅ Block #0 added successfully!
```

### Step 2 – Adding New Blocks

After adding two new blocks, the chain grows in length:

```
Enter block data: First transaction data
 Block #1 added successfully!

Enter block data: Second transaction data
 Block #2 added successfully!
```

### Step 3 – Displaying the Blockchain

The display option provides a clear, formatted view of all blocks and their details:

```
==================================================
                 BLOCKCHAIN CONTENTS
==================================================

--- Block #0 ---
Timestamp:   Mon Aug 18 15:04:05 2025
Data:        Genesis Block
Hash:        ...
Previous Hash: 0

--- Block #1 ---
Timestamp:   Mon Aug 18 15:05:05 2025
Data:        First transaction data
Hash:        ...
Previous Hash: ...

--- Block #2 ---
Timestamp:   Mon Aug 18 15:06:05 2025
Data:        Second transaction data
Hash:        ...
Previous Hash: ...
==================================================
```

### Step 4 – Blockchain Validation

The system verifies the chain's integrity:

```
 Blockchain is valid and has not been tampered with.
```

If a block is tampered with, the validation process will indicate a failure:

```
Enter block index to tamper: 1
Enter new data for the block: Malicious Data
 Block #1 data has been tampered with!

Enter your choice: 3
 Blockchain integrity compromised! Tampering detected.
```

-----

## Academic Integrity

I acknowledge that I have **not knowingly used GenAI** to complete this assessment. All code and documentation have been created by me without the use of artificial intelligence tools.
