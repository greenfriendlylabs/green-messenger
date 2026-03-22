# Greenfriendly Messenger

> A privacy-focused, blockchain-based messaging application built on Terra Classic with end-to-end encryption and premium GFT token integration.
>
## Overview

Greenfriendly Messenger is a decentralized messaging platform that leverages the Terra Classic blockchain for secure, encrypted communication. With built-in support for GFT (Greenfriendly Token) holders, the app offers premium features and exclusive status for token owners.

![G7BRAfEXkAAEtBf](https://github.com/user-attachments/assets/bfb1b71d-99fd-437f-aff6-c26c072b6058)

<img style="width:32%; height:auto;" alt="image" src="https://github.com/user-attachments/assets/cd9e7e9d-1679-4797-81b0-fe6dd7ba6646" />
<img style="width:32%; height:auto;" src="https://github.com/user-attachments/assets/7b941bce-9b45-4874-93e2-22245a434e07" />
<img style="width:32%; height:auto;" alt="image" src="https://github.com/user-attachments/assets/97162254-f23a-41b8-9b1b-19478a1fe76f" />


## Key Features

### 🔐 End-to-End Encryption
- **ECDH Key Exchange** - Secure key derivation using Elliptic Curve Diffie-Hellman
- **AES-256-GCM Encryption** - Military-grade encryption for all messages
- **On-Chain Security** - Public keys retrieved directly from blockchain transactions
- **Toggle Encryption** - Switch between encrypted and plaintext messaging

### 🎫 GFT Premium Membership
- **Premium Member Badge** - Exclusive golden badge for GFT token holders (≥1 GFT)
- **GFT Verified Contacts** - See which contacts own GFT tokens
- **Real-time Balance Updates** - Automatic checking every 30 seconds
- **CW20 Token Integration** - Direct querying of GFT smart contract

### 💬 Messaging Features
- **Real-time Messaging** - Send and receive encrypted messages instantly
- **Online Status** - See when contacts are active (5-minute activity window)
- **Contact Management** - Add, edit, delete, and favorite contacts
- **Message History** - All messages stored locally with encryption status indicators
- **Dark/Light Mode** - Beautiful UI with theme switching

### 💰 Wallet Integration
- **Terra Classic Wallet** - Full wallet management with seed phrase support
- **LUNC Balance** - View your LUNC token balance
- **GFT Balance** - See your Greenfriendly Token holdings
- **One-Click Refresh** - Update balances with a single click
- **Address Management** - Copy wallet addresses easily

### 🎨 User Interface
- **WhatsApp-Inspired Design** - Familiar, intuitive interface
- **Responsive Layout** - Works on all screen sizes
- **Avatar System** - Colorful avatars for contacts
- **Status Indicators** - Visual feedback for encryption, online status, and GFT ownership
- **Smooth Animations** - Polished user experience

## Usage

### Getting Started

1. **Create or Import Wallet**
   - Enter your 24-word seed phrase
   - Or generate a new wallet
   - Your wallet is stored locally and encrypted

2. **Add Contacts**
   - Click "Add Contact" button
   - Enter Terra Classic address (terra1...)
   - Enter a friendly name
   - Public key is automatically retrieved from blockchain

3. **Send Messages**
   - Select a contact from the list
   - Toggle encryption on/off as needed
   - Type your message and send
   - Watch for encryption indicators (🔐 or 🔓)

4. **Check Balances**
   - Go to Settings (⚙️)
   - Click the refresh button (🔄)
   - View your LUNC and GFT balances

### GFT Premium Features

To unlock premium features, you need **1 or more GFT tokens**.

**What you get:**
- ⭐ Premium Member badge displayed on your profile
- 🎫 GFT balance shown in wallet settings
- 🎫 Verification badge visible to your contacts
- Enhanced credibility and trust in the community

**How to get GFT:**
- GFT Contract: `terra17hnu4prwa3varxrws0sy9hffkmqv8tfmfpldg4e9fq58flrmuz2qlhymr5`
- Acquire through Terra Classic DEXs or exchanges
- Minimum 1 GFT required for premium status

## Security Considerations

### Encryption
- **ECDH**: Secure key agreement protocol
- **AES-256-GCM**: Authenticated encryption with associated data
- **Unique IVs**: Each message uses a unique initialization vector
- **No Server Storage**: All encryption happens client-side

### Wallet Security
- **Local Storage Only**: Seed phrases stored in browser localStorage
- **No Cloud Backup**: Your keys never leave your device
- **User Responsibility**: Always backup your seed phrase securely

### Privacy
- **On-Chain Metadata**: Message metadata (sender, recipient, timestamp) visible on blockchain
- **Encrypted Content**: Message content encrypted and unreadable on-chain
- **Contact Discovery**: Requires knowing Terra Classic addresses

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## Support

For issues, questions, or suggestions:
- Create an issue on GitHub
- Join our Terra Classic community

## Acknowledgments

- Terra Classic Community
- Greenfriendly Token (GFT) Project
- CosmJS Team
- React and Vite Teams

## 🙋‍♂️ Get Involved

If you encounter any issues or have questions:
- 🐛 [Report bugs](https://github.com/greenfriendlylabs/green-messenger/issues)
- 💡 [Request features](https://github.com/greenfriendlylabs/green-messenger/issues)
- ⭐ Star the repo if you find it useful!

## ☕ Support the Project

If you like this project, support further development with a repost or coffee:
```
terra1l9q4guus5vjxl84d5qea068vcen32l04jmc55w
```
```
terra1672k239zq3rus05y0ckg4c7cd5kddyd53qnqvv
```
Or scan the QR code on the faucet page to contribute directly. Link: [Go to Green Faucet](https://www.greenfriendlylabs.com/green-faucet/)

---

**Built with ❤️ on Terra Classic**

*Secure messaging for the decentralized future*
