# pqc-image-encryption
This repository contains the reference Python implementation for the research article “Post‐Quantum Secure Image Encryption via Hybrid Chaotic–Lattice Dynamics: Design, Analysis, and Implementation.” It provides fully functional scripts for encrypting and decrypting images using a hybrid scheme that combines:

1. CRYSTALS-Kyber1024 for post-quantum key encapsulation
2. 4D Chen hyper-chaotic map for pixel permutation
3. Ring-LWE-based diffusion with AES-style S-Box substitution
4. SHA3-512 HMAC for authentication

### Requirements

1. Python 3.8+
2. Packages:
    kyber_py (CRYSTALS-Kyber1024 interface)
    numpy
    pycryptodome (for AES S-Box and HMAC-SHA3)
    pillow (PIL)
    pysha3 (SHAKE-256)
