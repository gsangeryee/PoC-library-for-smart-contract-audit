# Smart Contract Audit PoC Library

This repository is a curated collection of **reproducible Proof-of-Concept (PoC) test cases** for smart contract vulnerabilities, written in Foundry using `forge`. It is designed as a companion to a structured auditing vault, enabling researchers and auditors to:

- Study real-world vulnerability patterns.
- Reuse testing techniques across audits.
- Reproduce attacks in a controlled environment.

## Usage

### Prerequisties

- Foundry
- Solc-compatible environment

### Run a PoC

```bash
cd token-bridge
forge install
forge build
forge test

```

## PoC Index
### Cross-chain-PoC
- from [Cfrin-Security-and-auditing](https://github.com/Cyfrin/security-and-auditing-full-course-s23?tab=readme-ov-file#-section-7-bridges-chains-signatures-intro-to-yulassembly--bridge-boss-audit)
- PoC: cross-chain-arbitrary-from


## 📜 License
MIT License © 2025 [saneryee]