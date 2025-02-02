# Land Registry using Blockchain
A decentralized land registry system built using Ethereum, Solidity, and Web3. It ensures transparency, security, and immutability for property transactions.

**Features**
User authentication via MetaMask
Smart contracts for secure land ownership records
Transparent property transactions
Blockchain-based verification
Web3.js integration for frontend

** Tech Stack**
Smart Contract: Solidity
Blockchain: Ethereum, Ganache
Development Environment: Remix IDE, Truffle
Frontend: Web3.js
Wallet: MetaMask

** Installation & Setup**
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
npm install
truffle migrate --network development
Ensure Ganache is running and MetaMask is configured.

Usage
Connect MetaMask
Deploy contracts
Register land & verify ownership

**User Guide**
➤ Register a New Land Parcel
Select an Ethereum account (from Ganache).
Enter the Land ID, Location, and Area.
Click "Register Land" to store it on the blockchain.
➤ Transfer Land Ownership
Enter the Land ID to transfer.
Select a new owner from the available Ethereum accounts.
Click "Transfer Ownership" to update blockchain records.
➤ View Land Details
Enter the Land ID to check details.
Click "Fetch Details" to view registered information.
