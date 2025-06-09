ECC-Secure-Payment-System:

A modern, user-friendly digital payment platform that leverages Elliptic Curve Cryptography (ECC) to ensure secure, authenticated, and efficient transactions. This project demonstrates how advanced cryptography can be integrated with a streamlined web interface to deliver robust payment security and a seamless user experience.

🚀 Features
ECC-Based Encryption: All sensitive transaction data is encrypted using ECC, providing strong security with smaller, faster keys compared to traditional algorithms.

Digital Signatures (ECDSA): Each transaction is signed with the sender's private key and verified using the public key, ensuring authenticity and integrity.

User Registration & Key Management: Users generate unique ECC key pairs at registration. Public keys are securely stored; private keys remain with the user.

Intuitive Web Interface: Built with Streamlit and Shadcn UI for a modern, responsive, and accessible user experience.

Transaction History: Users can view and verify their past transactions, with sensitive details masked for privacy.

Secure Backend: Python (Flask) backend handles cryptographic operations, transaction processing, and secure data storage with SQLite/TinyDB.

Session Management & Validation: Includes robust session handling, input validation, and detailed error feedback.

Optional Stripe Integration: Ready for integration with Stripe API for real-world payment tokenization and processing.


Technology Stack:
Frontend: Streamlit, Shadcn UI, Streamlit Option Menu, PIL, Pandas

Backend: Python, Flask, RESTful APIs

Database: SQLite, TinyDB

Cryptography: ECC (ecdsa library), SHA-256, Python cryptography library

Payments (Optional): Stripe API

Other Tools: Requests, Git, GitHub

How It Works
Register/Login: Users create an account and generate ECC key pairs.

Make Payments: Enter recipient, amount, and sign the transaction with your private key.

Transaction Processing: Backend verifies signatures, encrypts/decrypts data, and updates the database.

View History: Access your transaction records securely.
