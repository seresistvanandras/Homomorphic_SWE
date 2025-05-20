# Homomorphic Signature-based Witness Encryption (HSWE)
Python (and Rust soon!) implementation of the schemes described in the Homomorphic Signature-based Witness Encryption (HSWE) paper.

Eprint: [Homomorphic Signature-based Witness Encryption and Applications](https://eprint.iacr.org/2025/443.pdf)

We provide proof-of-concept implementations for the BLS- and RSA-based HSWE schemes. We also enclose a few micro-benchmarks.

A long term ToDO would be to also implement a Solidity decryptor contract that allows to decrypt on-chain a BLS-based HSWE ciphertext. For that, one would need to implement target group arithmetic in the EVM.

## Contributing and contact       
**PRs, issues are welcome. You can reach me out on [Twitter](https://twitter.com/Istvan_A_Seres) or [ethresear.ch](https://ethresear.ch/u/seresistvanandras).**
