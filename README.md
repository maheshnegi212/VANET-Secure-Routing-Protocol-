# VANET-Secure-Routing-Protocol-
VANET Secure Routing Protocol - Full Report
Introduction
This project aims to implement a secure routing protocol for Vehicular Ad Hoc Networks (VANET) using
digital signatures and hash functions. It simulates vehicles transmitting messages and validates their integrity
to protect against common VANET attacks such as impersonation, message modification, and data
tampering.
Objective
To design and simulate a lightweight and efficient secure routing protocol that ensures data integrity and
authentication in VANET communication using cryptographic hash functions and digital signatures.
Simulation Tools Used
- Python for simulation logic
- Matplotlib for plotting
- Pandas for data handling
- Hashlib for cryptographic hashing
Cryptographic Techniques
The simulation utilizes SHA256, MD5, SHA1, Blake2b, and SHA3_256 hash functions to ensure message
integrity. A salted hash technique is used for enhanced security against replay attacks.
Functionality and Features
- Simulates multiple vehicles with speed and location
- Detects vehicle collisions
- Validates message integrity using hashes
- Displays graphs for hash generation time, vehicle speeds, and positions over time
Performance Metrics
VANET Secure Routing Protocol - Full Report
The implemented simulation evaluates:
- Hash function computation time
- Vehicle speed consistency
- Movement paths and potential collisions
- Integrity validation efficiency
Conclusion
The project demonstrates the effectiveness of integrating cryptographic techniques in VANET simulations. It
provides a strong base for further development into full routing protocol integration with network simulators
like NS-2, NS-3, or OMNeT++.
