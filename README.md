# 3D Model Marketplace DApp

## 🌟 **Overview**  
A decentralized application (DApp) built on Ethereum, empowering users to list, purchase, and rate 3D models. This DApp utilizes **Web3.js** to communicate with smart contracts deployed on the Ethereum blockchain, and is integrated with **MetaMask** for account management.

---

## ✨ **Features**

- **List Models:** Users can upload their 3D models, providing a name, description, and price.
- **Purchase Models:** Models can be purchased using Ether, securely processed on the blockchain.
- **Rate Models:** After purchasing, users can leave ratings to help evaluate model quality.
- **Withdraw Funds:** Creators can easily withdraw earnings from model sales.
- **Model Display:** A list of all available models, with details such as price, creator info, and average rating.

---

## 📋 **Requirements**
- **Node.js**: To run the application.
- **MetaMask**: Browser extension for managing Ethereum accounts.

---

## ⚙️ **Installation**

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/3d-model-marketplace.git
   cd 3d-model-marketplace
   ```

2. **Install Dependencies**  
   Install required packages using a package manager like npm:  
   ```bash
   npm install web3
   ```

3. **Deploy the Smart Contract**  
   Deploy the contract to an Ethereum test network (like Rinkeby or Ropsten) and update the `contractAddress` variable in the code with your deployed contract’s address.

4. **Add ABI File**  
   Ensure the `abi.json` file (containing the smart contract's ABI) is in the root directory.

---

## 🚀 **Usage**

1. **Start the Application**  
   Serve the HTML file using a local server like http-server:  
   ```bash
   npx http-server
   ```

2. **Open in Browser**  
   Visit: `http://localhost:8080` (or your server's port).

3. **Connect MetaMask**  
   Ensure MetaMask is installed and connected to the correct Ethereum network. Allow the app to access your account.

4. **Interacting with the DApp**  
   - **List a Model**: Fill in the name, description, and price in Ether, then submit.
   - **Purchase a Model**: Input the model ID and confirm your purchase.
   - **Rate a Model**: Enter the model ID and rating.
   - **Withdraw Funds**: Withdraw any sales earnings with a simple click.

---

## 📁 **Code Structure**

- `index.html`: The user interface for interacting with the marketplace.
- `app.js`: Handles the logic for interacting with the Ethereum smart contract.
- `abi.json`: Contains the ABI of the deployed smart contract.

---

## 🤝 **Contributing**
Contributions are welcome! Fork the repo and submit a pull request.

---

## 📜 **License**
This project is licensed under the **MIT License**. See the LICENSE file for details.

---

![Uploading Снимок экрана 2024-10-04 в 15.08.46.png…]()


