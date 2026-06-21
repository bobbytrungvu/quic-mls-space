# Core Cryptography Concepts

## Cryptographic Hash Functions

## Digital Signatures

## HMAC

## HKDF and Key Derivation Function

## Authenticated Encryption with Associated Data (AEAD)

AEAD combines encryption and authentication in a single cryptographic operation. MLS, TLS 1.3 and QUIC all rely on AEAD algorithms to ensure that messages remain confidential and that any unauthorised modification of ciphertext is detected during decryption.

## Secrets and Key Schedules

A secret is a cryptographic value from which other secrets or encryption keys can be derived using a key derivation function (KDF).

## Security Properties

### Confidentiality

In the context of this project, confidentiality means only group members can read the intended message.

### Integrity

Any modification to a message is detected.

### Authentication

The receiver of a message can verify the sender.

### Forward Secrecy (FS)

Forward Secrecy ensures that compromise of a participant’s current keys does not reveal past communications.

### Post-Compromise Security (PCS)

Post-Compromise Security allows the group to recover confidentiality after a compromised participant refreshes its cryptographic state.
