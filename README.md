Blockchain-Based Land Registry System


Overview
The Blockchain-Based Land Registry System is a decentralized solution designed to provide secure, transparent, and immutable land registration. By leveraging blockchain technology, this system eliminates fraudulent transactions, prevents data tampering, and ensures trustworthy property ownership records.

Why Blockchain for Land Registry? 

✔️ Tamper-Proof Records – Once registered, land details cannot be modified or erased.   
✔️ Decentralized & Transparent – No central authority; transactions are publicly verifiable.   
✔️ Automated Ownership Transfers – Smart contracts eliminate intermediaries.   
✔️ Efficient & Secure – Reduces paperwork, enhances security, and speeds up transactions.   

Key Features  
🔹 Decentralized Land Registration – Eliminates the risk of record manipulation.  
🔹 Ownership Verification – Easily retrieve and verify land ownership details.   
🔹 Smart Contract-Based Transactions – Automates the registration and transfer process.  
🔹 Immutable Ledger – Ensures land records remain permanent and verifiable.  

Technology Stack

Component	Technology Used.  
Blockchain:	Ethereum.     
Smart Contracts:	Solidity, Remix IDE.     

Smart Contract Functionalities    

Function	Description:   
registerLand(uint256 _id, string _location, uint256 _area)	Registers land with an ID, location, and area.  
getLandDetails(uint256 _id) returns (string memory location, uint256 area, address owner)	Fetches land details.   
transferOwnership(uint256 _id, address newOwner)	Transfers ownership to a new owner.   
getOwner(uint256 _id) returns (address)	Retrieves the current owner of the land.  

How to Use

1️⃣ Deploy the Smart Contract (Remix IDE).  
Open Remix Ethereum IDE.   
Create a new file: LandRegistry.sol   
Copy & paste the smart contract code   
Compile the contract (Solidity Compiler tab → Click Compile)   
Deploy the contract (Deploy & Run Transactions tab → Click Deploy)  
2️⃣ Interact with the Smart Contract  
📌 Register Land    
registerLand(1, "Hyderabad, India", 5000);

📌 Retrieve Land Details   
getLandDetails(1);

📌 Transfer Ownership   
transferOwnership(1, "0xNewOwnerAddress");

📌 Check Current Owner   
getOwner(1);

SnapShot Example:
![Screenshot 2025-02-06 075454](https://github.com/user-attachments/assets/6e09919b-f52f-48dd-8f1a-57bee8fcece8)

Future Enhancements 🚀     
✅ Store land documents securely using IPFS.   
✅ Implement Zero-Knowledge Proofs (ZKPs) for privacy.  
✅ Extend support for Polygon / Binance Smart Chain (BSC) for lower transaction fees.   
