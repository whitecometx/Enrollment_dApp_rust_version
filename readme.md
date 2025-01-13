Solana Enrollment dApp (Rust Version)

This project demonstrates interaction with the Solana blockchain using Rust. It includes scripts for generating a keypair, requesting an airdrop, transferring tokens, and enrolling in the Turbin3 prerequisite program.

Prerequisites

- Rust
- Solana CLI
- Cargo

Features

1. Keypair Generation

Generate a new Solana wallet:

cargo test keygen -- --nocapture

2. Wallet Conversion

Convert between wallet formats:

cargo test wallet_to_base58 -- --nocapture
cargo test base58_to_wallet -- --nocapture

3. Airdrop

Request an airdrop of 2 devnet SOL:

cargo test airdrop -- --nocapture

4. Transfer SOL

Transfer all SOL from your dev wallet to another address:

cargo test transfer_sol -- --nocapture

5. Enroll in Turbin3 Prerequisite Program

Enroll in the Turbin3 prerequisite program:

cargo test enroll -- --nocapture

