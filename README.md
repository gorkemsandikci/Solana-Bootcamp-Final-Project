# Restaurant Review DApp - README

Welcome to the **Restaurant Review DApp** project repository! This decentralized application (DApp) leverages blockchain technology to manage restaurant reviews on the Solana network. Users can add new reviews for restaurants, including details such as title, location, rating, and description.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
- [Usage](#usage)
- [Smart Contracts](#smart-contracts)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Overview

The **Restaurant Review DApp** provides users with the ability to manage and interact with restaurant reviews on the Solana blockchain. This project ensures transparency and trust in the restaurant review process through the use of smart contracts. Users can add new reviews or update existing ones seamlessly.

## Features

- Add new restaurant reviews with title, location, rating, and description.
- Update existing restaurant reviews with new rating and description.
- Seamless integration with Ethereum blockchain.
- Transparent and secure restaurant review management.

## Getting Started

Follow these steps to set up the project locally and start managing restaurant reviews on the Solana blockchain.

### Prerequisites

1. Crypto Wallet: Ensure you have a [Phantom](https://phantom.app/) or [Solflare](https://solflare.com/) wallets installed on your browser.

2. Navigate to testnet (Devnet) network in your choosen wallet.

3. Get your to SOL tokens at [https://faucet.solana.com](https://faucet.solana.com/)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/gorkemsandikci/solana-bootcamp.git
    ```

2. Navigate to the project directory:

    ```bash
    cd /final-project/restaurant-review
    ```

3. Install required npm packages:

    ```bash
    npm install
    ```

## Usage

1. Start a local Solana network (e.g., using Ganache). 

2. Start the development server:

    ```bash
    npm start
    ```

4. Open your web browser and navigate to `http://localhost:3000` to access the DApp.

5. Connect your Solana wallet (e.g., MetaMask) to the DApp.

6. Add or update restaurant reviews, monitor activity, and interact seamlessly.

## Smart Contracts

The smart contracts in this project facilitate the restaurant review management process. They handle adding and updating restaurant reviews.

- `lib.rs`: Handles the broad logic of creating transactions, adding and updating reviews.
- `instruction.rs`: Defines the program's instruction data for executing the program.
- `state.rs`: Oversees the basic state of the program and handles some common errors.

## Frontend

The review page frontend is built using modern web technologies including React.js.

- **React.js**: Powers the DApp's user interface.
- **solana/web3.js , solana/wallet-adapter-react**: The Solana JavaScript API for smart contract interaction.
- **Phantom / Solflare**: Solana wallets for secure transactions.

## Contributing

Contributions to this project are welcome! To contribute:

1. Fork the repository.

2. Create a new branch for your feature/bug fix.

3. Make changes and test thoroughly.

4. Commit with clear and concise messages.

5. Push changes to your fork.

6. Submit a pull request describing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for your interest in the Restaurant Review DApp project! For questions or suggestions, reach out to us or open an issue on [GitHub](https://github.com/gorkemsandikci/solana-bootcamp). Happy reviewing on the blockchain! 🌮🍔🚀
