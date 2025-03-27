# FundMe Foundry Project

This project uses **Foundry** to develop and deploy smart contracts, including support for **zkSync** and **Ethereum testnets**. The `Makefile` provides a set of commands to streamline development, testing, and deployment.

## **📌 Prerequisites**
Ensure you have the following installed on your system:
- [Foundry](https://getfoundry.sh/)
- [Node.js & NPM](https://nodejs.org/)
- [zkSync CLI](https://era.zksync.io/docs/tools/zksync-cli/)
- [Anvil](https://book.getfoundry.sh/anvil/)

## **⚙️ Setup & Installation**
### **1️⃣ Install Dependencies**
Run the following command to install required dependencies:
```sh
make install

### **2️⃣ Update Dependencies**
To update installed libraries:
```sh
make update
```

---

## **🚀 Development Workflow**
### **🛠 Build & Compile**
To compile the contracts:
```sh
make build
```
For **zkSync** specific builds:
```sh
make zkbuild
```

### **🧪 Run Tests**
To execute all tests:
```sh
make test
```
For zkSync tests:
```sh
make zktest
```

### **📸 Snapshot**
To generate a snapshot of test results:
```sh
make snapshot
```

### **🧹 Clean the Project**
Removes compiled artifacts:
```sh
make clean
```

### **📜 Format Code**
To format Solidity contracts:
```sh
make format
```

---

## **🚀 Deployment**
### **📡 Local Deployment (Anvil)**
To start a local **Anvil** node:
```sh
make anvil
```
For zkSync local node:
```sh
make zk-anvil
```

### **🌍 Deploy to Ethereum (Sepolia)**
To deploy on **Sepolia testnet**:
```sh
make deploy-sepolia
```

### **🔗 Deploy to zkSync**
To deploy on zkSync:
```sh
make deploy-zk
```
For zkSync **Sepolia**:
```sh
make deploy-zk-sepolia
```

---

## **💰 Funding & Withdrawals**
### **🔹 Fund Contract**
```sh
make fund
```
### **🔸 Withdraw Funds**
```sh
make withdraw
```

---

## **📖 Help**
To list all available commands:
```sh
make help
```

This project simplifies smart contract development using Foundry, enabling Ethereum and zkSync deployment. Happy coding! 🚀
```
