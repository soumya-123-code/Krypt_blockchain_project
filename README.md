
Krypt - Web 3.0 Blockchain Application
🌐 Description
Krypt is a Web 3.0 blockchain application that allows users to send transactions over the blockchain. Each transaction is permanently recorded on the blockchain and paired with a gif for enhanced user experience.

🎥 Demo / UI
<img src="https://i.ibb.co/DVF4tNW/image.png" alt="Krypt Demo UI" />
✨ Main Functionalities
🔗 Connect MetaMask Wallet: Users can connect their MetaMask wallet to initiate Ethereum transactions.
📜 Blockchain-Paired Transactions: Each transaction includes an accompanying gif and is permanently stored on the blockchain.
👀 View Latest Transactions: Users can access their recent transactions and see the gifs associated with them.
🚀 Getting Started
🛠️ Steps to Run Locally
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/soumya-123-code/Krypt---Web-3.0-Blockchain-Application.git
Navigate to the Project Directory:

bash
Copy
Edit
cd Krypt---Web-3.0-Blockchain-Application  
Install Dependencies:

bash
Copy
Edit
npm i  
Run the Application in Development Mode:

bash
Copy
Edit
npm run dev  
🧰 Built With
Technology	Description
[Vite.js (React)]	Fast build tool and development environment for React.
[Tailwind CSS]	Utility-first CSS framework for styling.
[Solidity]	Language for writing smart contracts.
[Giphy API]	API to fetch gifs for transactions.
[Vercel]	Hosting platform for fast and reliable deployments.
📁 File Structure
plaintext
Copy
Edit
client  
├── images  
│   ├── animated.svg  
│   ├── hello.svg  
│   ├── logo.png  
├── src  
│   ├── components  
│   │   ├── Footer.jsx  
│   │   ├── Loader.jsx  
│   │   ├── Navbar.jsx  
│   │   ├── Services.jsx  
│   │   ├── Transactions.jsx  
│   │   ├── Welcome.jsx  
│   │   └── demo.jsx  
│   ├── context  
│   │   └── TransactionContext.jsx  
│   ├── hooks  
│   │   └── useFetch.jsx  
│   ├── utils  
│   │   ├── Transactions.json  
│   │   ├── constants.js  
│   │   ├── dummyData.js  
│   │   └── shortenAddress.js  
│   ├── App.css  
│   ├── App.jsx  
│   ├── favicon.svg  
│   ├── index.css  
│   ├── logo.svg  
│   ├── main.jsx  
│   └── index.js  
├── .eslintrc.js  
├── .gitignore  
├── .prettierrc  
├── README.md  
├── index.html  
├── package-lock.json  
├── package.json  
├── postcss.config.cjs  
├── tailwind.config.cjs  
├── vite.config.js  
└── yarn.lock  

smart_contract  
├── contracts  
│   └── Transactions.sol  
├── scripts  
│   └── deploy.js  
├── test  
│   └── sample-test.js  
├── hardhat.config.js  
├── package-lock.json  
├── package.json  
├── .gitignore  
├── LICENSE  
└── README.md  
📜 License
This project is licensed under the MIT License.

📬 Feedback
Feel free to contribute to this project or suggest new features!