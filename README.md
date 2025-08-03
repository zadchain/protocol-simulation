# Zadchain Protocol Simulation

This repository contains the official Python proof-of-concept for the Zadchain protocol, a next-generation Layer-0 designed by Zadlab. This simulation is intended to be a readable and technically sound demonstration of our core architectural innovations.

## Core Innovations Demonstrated

* **The Tesseract Fabric:** A dual-layer architecture featuring the `NexusChain` (ordering layer) and `S_Shard` (execution layer).
* **The Chronos Engine:** Our novel mechanism for MEV-resistance, demonstrated by the separation of concerns between the Nexus Chain and S-Shards.
* **Proof-of-Contribution (PoC):** Our unique consensus model, with the `ProspectEngine` implementation available in `zadchain/consensus/popt.py`.

## How to Run the Simulation

### 1. Setup

Clone the repository and install the required libraries.

```bash
git clone [https://github.com/Zadchain/protocol-simulation.git](https://github.com/Zadchain/protocol-simulation.git)
cd protocol-simulation
pip install -r requirements.txt
