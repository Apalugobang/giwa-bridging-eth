# 🚀 Giwa Bridging ETH

A simple ETH bridging project built with **TypeScript**.

## ✨ Features
- Cross-chain ETH bridging  
- Secure private key via `.env` (ignored from repo)  
- Modular `src/` structure  
- Ready-to-use scripts for **deposit** & **withdraw**  

---

## ⚙️ Installation

Clone this repository and install dependencies:

```bash
# 1. Clone repository
git clone git@github.com:Apalugobang/giwa-bridging-eth.git
cd giwa-bridging-eth

# 2. Install pnpm (if not installed)
npm install -g pnpm

# 3. Install dependencies
pnpm install

## 🔑 Setup

Create an .env file based on .env.example:

TEST_PRIVATE_KEY=your_private_key_here

## 🚀 Usage
Run Project

pnpm start

##🔹Deposit ETH to GIWA

pnpm run deposit --amount 0.1 --to giwa

##🔹Withdraw ETH from GIWA

pnpm run withdraw --amount 0.1 --from giwa

📝 License

MIT


---


