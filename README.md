# Decentralized G-Drive 3.0

**Decentralized Image Upload and Sharing**

This project facilitates decentralized image upload and sharing on the blockchain using Solidity for the smart contract and React for the front-end interface. It enables users to securely upload images to IPFS (InterPlanetary File System) and share access with specified users through smart contract functionality.

# Features

**•	Decentralized Storage:** Images are uploaded to IPFS, ensuring decentralized and immutable storage.

**•	Smart Contract:** Utilizes Solidity smart contracts on the Ethereum blockchain for access control and ownership management.

**•	Access Control:** Users can grant or revoke access to their uploaded images to specific individuals through the smart contract.


# Technologies Used
**•	Solidity:** Smart contract development for ownership and access control.

**•	React:** Front-end interface for uploading images and managing access.

**•	IPFS:** Decentralized storage protocol for hosting uploaded images.

# Usage
**Installation**
1. Clone the repository
    
       git clone https://github.com/your-username/decentralized-image-upload.git
2. Install dependencies for the hardhat:
   
       # Navigate to the root directory
       cd Dgdrive3.0
       # Install hardhat dependencies
       npm install
 
3. Compile the smart contract for artifacts:
   
       # Compile Smart Contract
       npx hardhat compile
4. Deploy the Solidity smart contract to an Ethereum testnet or local development environment.
   
       # Deploy Smart Contract
       npx hardhat run scripts/deploy.js --network <network-name>
5. Install dependencies for the React front end:
   
       # Navigate to the React client directory
       cd client 
       # Install React dependencies
       npm install
6. Run the react application:
   
       # Start React Application
       npm start
   
**Configuration**
1. Set up environment variables:
   
   o	btain API keys for Pinata to interact with IPFS.

   o	Update the React component (FileUpload.js) with your Pinata API keys.

**Usage**

Once the setup and configuration are complete, follow these steps to utilize the decentralized image upload and sharing system:

**1. Install Metamask:**

     o Ensure Metamask is installed and configured in your browser for Ethereum interactions.
  
**2. Update Contract Address:**

    o After smart contract deployment, make sure to update the contract address in App.js within the React application.
  
**3. Upload Image before "Get Data":**

    o Click "Get Data" only after uploading an image on Pinata. Otherwise, it will throw an error stating "You don't have access".
  
**4. Accessing Other User Images:**

    o Use the "Get Data" button to access other users' images. Input the user's address in the designated box, but remember, you can only access their images if they've granted you access through the smart contract. 
    o Otherwise, it will throw an error saying "You don't have access".
  
**These steps will ensure smooth navigation and utilization of the system while maintaining access control and avoiding potential errors.**

![image](https://github.com/Ashu784/Decentralized-Google-Drive/assets/95235468/1aff95ac-72a0-4d96-a8e5-31a1a76008d6)
![image](https://github.com/Ashu784/Decentralized-Google-Drive/assets/95235468/0fa7d197-b0a2-4a9e-9116-bb4a57ce61fe)
![image](https://github.com/Ashu784/Decentralized-Google-Drive/assets/95235468/c36d0ee4-60be-4dbe-babe-6c485096ebdb)
![image](https://github.com/Ashu784/Decentralized-Google-Drive/assets/95235468/821b00d7-5bfd-46a0-8844-56f099d8f749)
![image](https://github.com/Ashu784/Decentralized-Google-Drive/assets/95235468/6abccccb-0e70-4b97-9274-a30ff61c98d1)
![image](https://github.com/Ashu784/Decentralized-Google-Drive/assets/95235468/ed75722e-1493-4b2e-9786-6d739d296d4f)





