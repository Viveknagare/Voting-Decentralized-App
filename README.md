Blockchain E-Voting Application

This is a decentralized E-Voting application built using Solidity (Hardhat) for smart contracts, React for the frontend, and Node.js + Express for the backend. It ensures transparency, security, and immutability in the voting process using blockchain technology.


🚀 Tech Stack

- Smart Contracts:** Solidity, Hardhat
- Backend:** Node.js, Express.js
- Frontend:** React, Ethers.js / Web3.js
- Blockchain Network:** Local Hardhat Network / Testnet (Volta)


 📁 Project Structure

/client → React frontend
/contracts → Solidity smart contracts
/scripts → Hardhat scripts
/backend → Node + Express backend
/hardhat.config.js → Hardhat config

 🛠️ Setup Instructions

 1. Clone the repository

git clone https://github.com/your-username/blockchain-voting-app.git
cd blockchain-voting-app

2. Install Hardhat and dependencies

npm install
npx hardhat compile

3. Deploy Smart Contracts

Start Hardhat local node:- npx hardhat node

4. In a new terminal, deploy the contracts:

npx hardhat run scripts/deploy.js --network localhost

4. Backend Setup

cd backend
npm install
node index.js  # or nodemon index.js

5. Frontend Setup

cd ../client
npm install
npm start

