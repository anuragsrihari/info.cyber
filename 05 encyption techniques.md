# Encryption Techniques
## Learning Objectives 
- understand cryptography basics
- Differenciate between symmetric and asymmetric encryption
- Learn hashing and digital signature concepts
## Cryptography
Cryptography is a technique of securing information and communication using codes to ensure confidentiality, integrity, and authenticaion
## Symmetric Encryption 
- uses one key for both encryption and dencryption
- Fast, suitable for bulk data encryption.
## Asymmetric Encryption 
- uses two keys: public key (for encryption) & private keys (for dencryption).
- used for secure key exchange and digital communication.
# Hashing
- converts data into fixed-length string.
- one-way process-cannot be reversed.
- used of password storage and integrity checking.
- common algotrithms: SHA-256, MDS (deprecated).
## Digital Signature and Certificates
- ensure authenticity and non-repudiation.
- a digital signature uses private key to sign data and public key to verify.
- certificates (X.509) are issued by certificate authorities (CAs) for trust verification (used in HTTPs).
# Example
When visiting https://bank.com
- browser verifies certificate signed by CA to ensure authenticity.

