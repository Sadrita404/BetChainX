# BetChainX - Decentralized Game-to-Earn dApp

Turn your gameplay into crypto! **BetChainX** is a fully decentralized application where users can participate in fun games, place bets, and earn crypto rewards using blockchain-powered NFTs and a unified token economy.

---

✨ **Features**

🎮 **Game Betting:** Play mini-games and place bets in $BCX tokens.  
🏆 **NFT Rewards:** Top players and winners earn NFTs representing rare in-game assets.  
💰 **Automatic Payouts:** Smart contracts handle fair payouts instantly.  
🤖 **AI-Powered Quizzes & Challenges:** AI generates real-time quizzes and predictions related to in-game events.  
🌐 **Unified Token Economy:** $BCX token simplifies transactions and cross-chain interoperability.  
🔐 **Fully Decentralized:** No centralized backend; all logic runs on-chain or in the client.  
📈 **Leaderboard & Stats:** Track performance and compete with other players.  
💌 **Social Connectivity:** Invite friends via wallet ping and share achievements.

---
**Project Demo**


[https://drive.google.com/file/d/1kpx932dG3bnsGIY3yVk79dsHSYCHAqry/view?usp=sharing](https://drive.google.com/drive/folders/1EpvFlDzOOCj7UNiGNRY5Wc7_E3cdeT_J?usp=sharing)

---
🎯 **How It Works**

1. Connect your wallet (MetaMask, WalletConnect, or compatible).  
2. Choose a game or challenge from the dashboard.  
3. Place bets using $BCX tokens or participate in quizzes.  
4. Smart contracts execute bets fairly and instantly.  
5. Earn NFTs or token rewards for top performance.  
6. Track your ranking on the real-time leaderboard.  

---

🚀 **Quick Start**

### For Users

1. Visit the deployed app.  
2. Connect a wallet compatible with your chosen chain.  
3. Obtain $BCX tokens from the faucet or exchange.  
4. Start playing games, placing bets, and earning rewards!  

### For Developers

#### Prerequisites
- Node.js 20+  
- MetaMask or compatible Web3 wallet  
- Test tokens from faucet (if using testnet)  

#### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/BetChainX.git
cd BetChainX

# Install dependencies
npm install

# Start development server
npm run dev

```

**Install Dependencies**

```
npm install
# or
yarn install
```

**Configure Private Key**
Create a .env file in the root of the project:

```
touch .env
```

**Add your private key and RPC URL:**

```
PRIVATE_KEY="your-wallet-private-key"
RPC_URL="https://alfajores-forno.celo-testnet.org"

#⚠️ Never commit your private key to a public repository.
Use .env to keep it secure.
```
**Deploy Smart Contracts (Optional)**
If you need to deploy smart contracts locally or to a testnet:

```
# Install Hardhat
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox

# Deploy contracts
export PRIVATE_KEY="your-wallet-private-key"
npx hardhat run scripts/deploy.js --network alfajores
#Replace alfajores with the network you are using.
```

**Connect Wallet in App**
Start the frontend server:

```
npm run dev
```
**Open the app in your browser (http://localhost:3000)
Click Connect Wallet
Your wallet should now be connected, and private key configured for testnet transactions.**


---

🏗️ **Tech Stack**

**Frontend**
- React + TypeScript
- Tailwind CSS
- Vite
- TanStack Query
- Wouter (Routing)

---

**Blockchain**
- Celo / Ethereum / Telos (EVM-compatible)
- Solidity Smart Contracts
- Web3.js + ContractKit
- Hardhat

---

**AI / ML**
- TensorFlow.js (AI-powered quizzes & predictions)
- react-webcam (for camera input in mini-games)

---

# 📁 Project Structure

<img width="578" height="301" alt="Screenshot 2025-10-26 at 5 28 33 AM" src="https://github.com/user-attachments/assets/88dfb9a0-bfb6-431e-8da2-23d38e5dd410" />

---
# Work Flow 

<img width="311" height="330" alt="Screenshot 2025-10-26 at 9 02 18 AM" src="https://github.com/user-attachments/assets/0643989a-7695-4db7-8662-f7843546f122" />



---


🎨 **Design Philosophy**
- Vibrant, game-focused UI with clear visual feedback
- Smooth animations for scores, rewards, and NFTs
- Mobile-first and responsive for all devices
- Accessibility-focused: ARIA labels, keyboard navigation

---

#Wire Frame

**Wallet Connection Workflow**

<img width="522" height="61" alt="Screenshot 2025-10-26 at 5 39 42 AM" src="https://github.com/user-attachments/assets/bdef1ca4-282c-4647-b131-09263e138516" />

---

**Game Play / Betting Workflow**


<img width="444" height="163" alt="Screenshot 2025-10-26 at 5 40 34 AM" src="https://github.com/user-attachments/assets/30f9e9fa-51cd-4ed5-96b5-be5419177cb7" />


---

**AI Quiz Workflow**


<img width="557" height="157" alt="Screenshot 2025-10-26 at 5 41 28 AM" src="https://github.com/user-attachments/assets/3291bbb0-414c-47a2-896c-e1837a62c2a7" />


---

**NFT Auction Workflow**

<img width="496" height="157" alt="Screenshot 2025-10-26 at 5 42 01 AM" src="https://github.com/user-attachments/assets/0cb85fc8-0d6e-47f8-b1d9-200bd5ee899b" />


---

**Leaderboard / Social Workflow**

<img width="491" height="79" alt="Screenshot 2025-10-26 at 5 42 47 AM" src="https://github.com/user-attachments/assets/fe0f1559-ee68-4c0c-8b8b-aa1507654918" />


---

**Rewards Workflow**

<img width="423" height="106" alt="Screenshot 2025-10-26 at 5 43 34 AM" src="https://github.com/user-attachments/assets/1b6a0e0d-cb51-4a01-9dde-746dbff9279f" />


---

# APP DEMO PICTURE

<img width="300" height="600" alt="Screenshot 2025-10-26 at 5 52 21 AM" src="https://github.com/user-attachments/assets/ac97e954-350d-450e-a127-4b5caa65ce1c" />

---

<img width="300" height="600" alt="Screenshot 2025-10-26 at 5 53 39 AM" src="https://github.com/user-attachments/assets/4fe19e49-4c4d-4e76-9144-8a683c5dddb4" />

---

<img width="300" height="600" alt="Screenshot 2025-10-26 at 5 55 05 AM" src="https://github.com/user-attachments/assets/96b0da29-994b-420a-ab4f-de3e7795ef3d" />

---



🔐 **Security**
- ✅ Smart contracts handle all funds and bets
- ✅ Fully decentralized and non-custodial
- ✅ Open-source for transparency
- ✅ Rate limiting and anti-cheat mechanisms in place
- ✅ Testnet deployment recommended before mainnet
  
---

🤝 **Contributing**
Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a Pull Request

---

📜 **License**
- MIT License — see LICENSE file for details

---

🆘 **Support**
- Documentation: See `DEPLOYMENT_GUIDE.md`
- Contract Details: See `contracts/DEPLOYMENT.md`
- Celo Docs: [https://docs.celo.org](https://docs.celo.org)
- Issues: Open a GitHub issue in this repository

---


🌍 **Roadmap**
- MVP: Betting mini-games + token rewards
- NFT badges for winners
- Leaderboards and weekly rewards
- AI-generated quizzes and challenges
- Cross-chain interoperability
- Social sharing & friend invites
- Mainnet deployment

---

🙏 **Acknowledgments**
- Built on Celo / EVM-compatible blockchain
- Powered by TensorFlow.js and on-chain smart contracts
- Inspired by gamification and play-to-earn principles
- Made with ❤️ for blockchain gamers and NFT enthusiasts

