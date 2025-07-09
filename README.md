# SandCat
Sand Cat is a privacy-first, open-source application that enables quantum-secure, peer-to-peer Bitcoin transactions using encrypted QR codes — with or without an internet connection.

Built from the belief that financial privacy is essential to human freedom, Sand Cat ensures individuals can request or send Bitcoin securely, without exposing wallet addresses, personal metadata, or relying on centralized infrastructure.

In a time where AI is improving surveillance and government overreach is threatening financial sovereignty, Sand Cat offers the digital equivalent of handing someone physical cash — only faster, borderless, and quantum-resistant.

Why Sand Cat Exists
Today, even non-KYC Bitcoin users face real-world risks:
- Reused addresses expose total wallet balances
- QR code scanners leak payment info
- Messaging platforms store and correlate transaction data
- Blockchain analysis firms map entire social graphs of Bitcoin activity

Sand Cat prevents all of that by combining end-to-end encrypted communication with quantum-safe cryptography and offline QR code transmission.

It’s not just a messaging app. It’s a freedom tool.

How Sand Cat Works
Sand Cat uses two core technologies from the NIST post-quantum cryptography standardization process:

CRYSTALS-Kyber for key exchange (quantum-safe alternative to ECDH)

CRYSTALS-Dilithium for digital signatures (verifiable authentication)

Here's the simplified flow:
- A user creates a Bitcoin payment request, optionally including an amount and memo (following the BIP-21 standard)
- That request is encrypted with the recipient’s Kyber public key and digitally signed using the sender’s Dilithium private key
- The encrypted payload is encoded into a QR code
- The recipient scans and decrypts the QR to retrieve the request, verifying the sender’s signature in the process

This can all be done peer-to-peer — even offline — with no server, phone number, or account required.
