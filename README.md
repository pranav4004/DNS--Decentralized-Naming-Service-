# Decentralized Naming Service (DNS)

## Overview
The Decentralized Naming Service (DNS) project is a blockchain-based application designed to provide a secure and decentralized method for domain name registration and resolution. Utilizing the Ethereum blockchain and smart contracts written in Solidity, this project aims to eliminate central points of failure and censorship inherent in traditional DNS systems.

## Features
- **Decentralization**: Domain names are registered and managed on the blockchain, ensuring no single entity has control.
- **Security**: Enhanced security through the immutability and transparency of blockchain technology.
- **Smart Contracts**: Implemented using Solidity for domain registration, ownership transfers, and resolution.
- **React Frontend**: User-friendly interface built with React to interact with smart contracts.
- **OpenSea Integration**: Domains can be listed and traded on the OpenSea marketplace.
- **Deployment**: The smart contracts are deployed on the Sepolia test network.

## Technologies Used
- **Solidity**: Smart contract programming language.
- **Ethereum**: Blockchain platform for deploying the smart contracts.
- **React**: Frontend library for building user interfaces.
- **JavaScript**: Frontend development and integration with the blockchain.
- **Web3.js**: JavaScript library for interacting with the Ethereum blockchain.
- **OpenSea**: NFT marketplace integration.
- **Sepolia Test Network**: Deployment of smart contracts.
- **Hardhat**: Ethereum development environment.

## Project Structure
- `contracts/`: Contains Solidity smart contracts.
- `public/`: Public assets and files for the React application.
- `scripts/`: Deployment and interaction scripts for smart contracts.
- `src/`: Source code for the React frontend application.
- `README.md`: Project documentation (this file).

## Installation

### Prerequisites
Ensure you have the following installed on your system:
- Node.js
- npm (Node Package Manager)
- Hardhat
- MetaMask (for interacting with the Ethereum network)

### Setup
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/dns-project.git
    cd dns-project
    ```

2. Install the required packages:
    ```sh
    npm install
    ```

3. Compile the smart contracts using Hardhat:
    ```sh
    npx hardhat compile
    ```

4. Deploy the smart contracts to the Sepolia test network:
    ```sh
    npx hardhat run scripts/deploy.js --network sepolia
    ```

5. Start the React development server:
    ```sh
    npm start
    ```

## Usage

### Interacting with the Frontend
1. Open your browser and navigate to `http://localhost:3000`.
2. Connect your MetaMask wallet to the Sepolia test network.
3. Register a new domain, transfer ownership, or resolve domain names using the user-friendly interface.

### OpenSea Integration
1. List your registered domains on the OpenSea marketplace.
2. Trade domains as NFTs, leveraging the decentralized and secure nature of the blockchain.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries or issues, please contact pranavsampat123@gmail.com.
