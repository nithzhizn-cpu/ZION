![Platform](https://img.shields.io/badge/platform-Linux-blue)
![PQC](https://img.shields.io/badge/Post--Quantum-ML--KEM-green)
![Architecture](https://img.shields.io/badge/architecture-Local%20Agent-purple)
![Mesh](https://img.shields.io/badge/network-P2P%20Mesh-orange)
![License](https://img.shields.io/badge/license-MIT-yellow)
![Status](https://img.shields.io/badge/status-Alpha-red)

# ZION

### Post-Quantum Secure Messenger

**ZION** is an open-source secure communication platform designed around a **Local Agent Architecture**, **Post-Quantum Cryptography**, and **Peer-to-Peer Mesh Networking**.

Unlike traditional messengers, cryptographic operations are isolated from the user interface and performed by a dedicated local agent running on the user's device.

---

## Core Features

- 🔐 Local Cryptographic Agent
- 🛡️ Post-Quantum Cryptography (ML-KEM)
- 🔑 ECDH Key Exchange
- 🔒 AES-256-GCM Encryption
- 🌐 Peer-to-Peer Mesh Networking
- 👤 Decentralized Identity
- 📡 Bootstrap Discovery Network
- 🎙 Secure Voice Communication (WebRTC)
- 🖥 Linux Desktop Client (Tauri)
- 📂 Self-Hosted Friendly
- 🔓 Open Source

---

## Architecture

```text
UI
 ↓
Local Agent
 ↓
Post-Quantum Layer (ML-KEM)
 ↓
AES-256-GCM Transport
 ↓
P2P Mesh Network
 ↓
Remote Agent
 ↓
UI
