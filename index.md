# My Git WebHome 🔧

A privacy-preserving smart lock system that uses zero-knowledge proofs to verify identity without revealing personal data.

## Features ✨

- ✅ Biometric-based authentication
- ✅ Zero-Knowledge Proofs using Groth16 (Circom + SnarkJS)
- ✅ Secure & private identity verification
- ✅ Web interface for management

## Technologies Used 🧰

- [Circom](https://docs.circom.io/) for circuit design
- [SnarkJS](https://github.com/iden3/snarkjs) for proof generation & verification
- Node.js for server-side logic
- HTML/CSS + JS for the frontend

## How It Works 🔁

1. **User provides biometric input**
2. **Proof is generated locally using zk-SNARKs**
3. **Smart lock verifies the proof**
4. **Access is granted or denied without revealing who**

## Getting Started 🚀

### Prerequisites

- Node.js
- Circom
- SnarkJS

### Installation

```bash
git clone https://github.com/yourusername/smart-lock.git
cd smart-lock
npm install
