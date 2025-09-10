# Giwa Bridging ETH

A simple ETH bridging project built with TypeScript.

## 🚀 Features
- Cross-chain ETH bridging
- Private key via `.env` (ignored from repo)
- Modular `src/` structure

## 📦 Installation
Clone this repository and install dependencies:

```bash
1. git clone https://github.com/Apalugobang/giwa-bridging-eth.git
cd giwa-bridging-eth

2. Install pnpm
If you don't have pnpm, install it first:

(`npm install -g pnpm`) 

3. Install Dependencies

(`pnpm install`)

⚙️ Setup
Create an .env file based on .env.example:

`TEST_PRIVATE_KEY=your_private_key_here`

▶️ Usage
Run the project with:

`pnpm start`

🔹 Deposit ETH to Giwa
Use the following command to deposit to Giwa:

`pnpm run deposit --amount 0.1 --to giwa`

🔹 Withdraw ETH from Giwa
Use the following command to withdraw from Giwa:

`pnpm run withdraw --amount 0.1 --from giwa`

🛠 Tech Stack

TypeScript

Node.js

pnpm

📄 License

MIT





