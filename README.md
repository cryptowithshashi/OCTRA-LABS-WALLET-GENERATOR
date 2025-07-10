# Octra Labs Wallet Generator & Validator Node Guide

Welcome to Octra Labs, a project focused on building decentralized tools and infrastructure.

## 🚀 How to Run Octra Wallet Generator

- Fork Repo & Open Codespace

```bash
https://github.com/octra-labs/wallet-gen
```

- Install Bun

```bash
curl -fsSL https://bun.sh/install | bash
```

- Restart Shell

```bash
exec $SHELL
```

- Check Bun Version

```bash
bun --version
```

- Open Port 8888

```bash
sudo apt update && sudo apt install ufw -y
sudo ufw allow 8888
```
- Clone Wallet Generator Repo

```bash
git clone https://github.com/octra-labs/wallet-gen
cd wallet-gen
```

- Install Dependencies

```bash
bun install
```

- Build Project

```bash
bun run build
```

- Run Wallet Generator

```bash
bun start
```

Click the popup window to proceed.

- Save Your Keys Securely: Backup your mnemonic, private/public key, and address in a safe place.

- Request Faucet Tokens: https://faucet.octra.network

# After Generating Wallet — Try These New Steps (Updated by OctraLabs)

Once you've generated your wallet, follow these updated steps to test the new Octra client features:

## 🔧 Step-by-Step:

- First run this command to see files:

```bash
ls
```

- Enter the client folder:

```bash
cd octra_pre_client
```

- Pull the latest updates:

```bash
git pull
```

- Clean your terminal screen:

```bash
clear
```

- If Python isn’t installed yet, run:

```bash
sudo apt update
sudo apt install python3 python3-pip -y
```

- Activate virtual environment:

```bash
source venv/bin/activate
```

- Now launch the client:

```bash
./run.sh
```

### What You’ll See
The wallet interface will open with multiple options. Use your keyboard arrow keys or number keys (`1`, `2`, `3`...) to navigate.

### 🪙 To Send a Transaction:

- Go to option 1: Send Transaction
- Press `1` again → Enter recipient address → Enter amount → Press `y` to confirm

### 🔐 To Encrypt Your Balance (New Feature):
- Go to option 4: Encrypt Balance

- Enter the amount of $OCT you want to encrypt

- Press `y` to confirm

- That's it — your tokens are now encrypted on-chain!



# 🛡️ Octra Validator Node Setup


- Generate a testnet wallet using the wallet generator instructions above.
- Claim testnet tokens with your address: https://faucet.octra.network/
- Verify your wallet and transactions: https://octrascan.io/
- Join the community Discord and await validator instructions: https://discord.com/invite/octra

### ⚠️ Validator node guide coming soon! Stay tuned.

❓ FAQ

Q: Can I run the wallet generator on GitHub Codespaces?Yes! GitHub Codespaces is perfect for quickly setting up and testing without a VPS.

Q: Do I need a VPS?Not necessarily. A VPS is recommended if you plan to run services persistently, but you can generate wallets and test using Codespaces.

Q: Where should I store my mnemonic and keys?Always back them up securely offline. Never share them publicly.

Q: How do I get testnet tokens?Use the faucet: https://faucet.octra.network

Q: Where can I ask more questions?Join the Discord: http://discord.gg/octra

## 📢 Disclaimer

This guide is a community contribution. All credits go to the Octra Labs development team for their repositories and official documentation. Please always refer to the original resources for the most up-to-date information.



## ABOUT ME

Twitter -- https://x.com/SHASHI522004

Github -- https://github.com/cryptowithshashi
