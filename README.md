# Post-Quantum Cryptography: SQUIRRELS

## Overview
This presentations is on Post-Quantum Cryptography, specifically focusing on the SQUIRRELS project. The presentations cover various aspects of post-quantum cryptographic methods, key generation, signature schemes, and security.

## Contents
- **[Presentation 1](Post-Quantum-Cryptography-SQUIRRELS-Presentation1.pdf)**:
- An introduction to post-quantum cryptography and the SQUIRRELS project, including its design rationale, main mechanisms, advantages, and limitations.
- **[Presentation 2](Post-Quantum-Cryptography-SQUIRRELS-Presentation2.pdf)**:
- A detailed discussion on GGH to GPV, co-cyclic lattices, key generation computations, and hybridizing attacks for sparse secrets.

## Key Points

### Presentation 1: Introduction to SQUIRRELS
- **Design Rationale**:
  - Historical context and main mechanisms.
  - Overview of the Squirrel family and their security advantages.
- **Main Mechanism**:
  - Explanation of GPV improvement of GGH.
  - Key components such as public and secret keys, hashing, and signature generation.
- **Advantages**:
  - Security based on generic lattice problems.
  - Efficiency in signature generation and verification.
- **Limitations**:
  - Time-consuming key generation process.
  - Complexity of working with unstructured lattices.

### Presentation 2: Advanced Topics in SQUIRRELS
- **GGH to GPV**:
  - Improvements in security by randomizing lattice point selection.
- **Co-cyclic Lattices**:
  - Importance and cryptographic significance of co-cyclic lattices.
  - Use of Hermite Normal Form for efficient signature verification.
- **Key Generation Computations**:
  - Detailed steps for generating lattice vectors and ensuring security parameters.
- **Hybridizing Attacks**:
  - Strategies for attacking sparse secret vectors and estimating guess probabilities.
- **Recommended Parameters**:
  - Guidelines for parameter selection to maintain security and efficiency.
- **Reference Implementation**:
  - Benefits of using optimized libraries like GMP and Flint for efficient computations.

## Authors
- Daymon Wu
- Al Fahim
- Jaraad Hussain
- Leonardo Yeung
