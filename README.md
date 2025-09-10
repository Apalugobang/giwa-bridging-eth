# Giwa Bridging ETH

A simple ETH bridging project built with TypeScript.

## 🚀 Features
- Cross-chain ETH bridging
- Private key via `.env` (ignored from repo)
- Modular `src/` structure

## 📦 Installation
Clone this repository and install dependencies:

```bash
git clone git@github.com:Apalugobang/giwa-bridging-eth.git
cd giwa-bridging-eth
pnpm install

⚙️ Setup

Create a .env file based on .env.example:
TEST_PRIVATE_KEY=your_private_key_here

▶️ Usage

Run the project with:
pnpm start
🔹 Deposit ETH to Giwa
pnpm run deposit --amount 0.1 --to giwa
🔹 Withdraw ETH from Giwa
pnpm run withdraw --amount 0.1 --from giwa

🛠 Tech Stack
TypeScript
Node.js
pnpm
