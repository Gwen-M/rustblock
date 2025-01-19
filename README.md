# RustBlock 🦀⛓️

A blockchain prototype implementation in Rust, featuring a very minimal web interface for easy interaction. This project demonstrates the core concepts of blockchain technology while maintaining a clean and modular architecture.

## 🚀 Features

- **Blockchain Core**
  - Block creation and validation
  - Chain integrity verification
  - Proof of existence through SHA-256 hashing
  - Genesis block initialization

- **Web Interface**
  - Real-time block visualization
  - Manual block creation
  - Peer management interface
  - RESTful API endpoints

- **Peer Network** (Work in Progress)
  - Basic peer connection management
  - Groundwork laid for P2P communication
  - Chain synchronization (planned)

## 🛠️ Technology Stack

- **Backend**: Rust
- **Web Server**: Rouille
- **Cryptography**: SHA-256
- **Concurrency**: Parking Lot
- **Serialization**: Serde
- **Frontend**: HTML, JavaScript

## 📋 Prerequisites

- Rust (latest stable version)
- Cargo package manager

## 🚀 Getting Started

1. Clone the repository

```bash
git clone https://github.com/Gwen-M/rustblock.git
cd rustblock
```

2. Build the project

```bash
cargo build
```

3. Run the server

```bash
cargo run
```

4. Open your browser and navigate to `http://localhost:8000`

## 🔌 API Endpoints

- `GET /blocks` - Retrieve all blocks in the chain
- `POST /mintBlock` - Create a new block
- `GET /peers` - List all connected peers
- `POST /addPeer` - Connect to a new peer

## 🚧 Project Status

This project is a prototype and some features are still under development. The peer-to-peer networking functionality is partially implemented, with the groundwork laid for future development of complete node synchronization and block propagation.

## 🎯 Future Improvements

- [ ] Complete P2P network implementation
- [ ] Block propagation across nodes
- [ ] Consensus mechanism
- [ ] Network resilience and fault tolerance
- [ ] Advanced block validation rules

## 📜 License

All rights reserved

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request.

## ⚠️ Disclaimer

This is an educational project meant to demonstrate blockchain concepts. It is not intended for production use.