# XenMiner

XenMiner uses the Argon2 hashing algorithm to simulate the mining process. It's designed to efficiently use all available CPU cores for the mining process, optimizing hash rates.

## Features

- **Parallel Mining**: Utilizes all available CPU cores for the mining process.
- **Dynamic Difficulty**: Adjusts the mining difficulty based on data fetched from a server.
- **Block Verification**: After mining, each block is verified to ensure its integrity.
- **Progress Tracking**: Uses tqdm to display a real-time progress bar and hash rate.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed.
- `requests`, `passlib`, and `tqdm` Python packages installed. You can install these using pip:

  ```bash
  pip install requests passlib tqdm
