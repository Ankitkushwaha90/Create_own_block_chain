# Blockchain Project

## Overview
This project demonstrates a simple blockchain application built with Node.js. It provides essential features such as handling peer-to-peer communication, blockchain data storage, and REST APIs for interacting with the blockchain.

## Features
- Blockchain-based data handling
- RESTful API for blockchain interaction
- Peer-to-peer communication with Redis
- Real-time blockchain updates

## Prerequisites
Ensure that you have the following software installed:
- [Node.js](https://nodejs.org/) (v14.x or later)
- [Redis](https://redis.io/)
- A package manager like `npm` or `yarn`

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd BlockchainProject
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the Redis server:
   ```bash
   redis-server
   ```

## Available Scripts
### Start the Application
```bash
npm start
```
Runs the application on the default port defined in `index.js`.

### Development Mode
```bash
npm run dev
```
Starts the application in development mode using `nodemon` for hot reloading.

### Peer Communication Mode
```bash
npm run dev-peer
```
Starts the application with peer-to-peer communication enabled.

## Project Structure
```
BlockchainProject/
├── index.js        # Entry point for the application
├── package.json     # Project metadata and dependencies
├── node_modules/    # Installed packages
└── README.md        # Documentation
```

## Dependencies
- **body-parser:** Parse incoming request bodies in a middleware
- **express:** Web framework for building APIs
- **hex-to-binary:** Convert hexadecimal to binary
- **redis:** Redis client for Node.js
- **request:** Simplified HTTP client

### Dev Dependencies
- **cross-env:** Set environment variables across platforms
- **nodemon:** Automatically restarts the application during development

## How to Contribute
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-branch-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch-name
   ```
5. Create a pull request.

## License
This project is licensed under the ISC License.

