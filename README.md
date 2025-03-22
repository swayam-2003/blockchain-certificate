# Blockchain Certificate System 🎓

A secure and tamper-proof digital certificate generation and validation system built with blockchain technology.

## 🌟 Features

- **Secure Certificate Generation**: Issue certificates with blockchain verification
- **Instant Validation**: Verify certificates using unique IDs
- **Role-Based Access**: Separate interfaces for issuers and students
- **Decentralized Storage**: IPFS integration for certificate metadata
- **User Authentication**: Secure login system
- **Smart Contract Integration**: Automated certificate validation

## 🚀 Quick Start Guide

### Prerequisites

1. **Node.js and npm**
   - Download and install from [nodejs.org](https://nodejs.org/)
   - Recommended version: Node.js 16.x or later

2. **MetaMask**
   - Install the [MetaMask browser extension](https://metamask.io/)
   - Create a wallet and get some test ETH from a faucet

3. **Ganache**
   - Download and install from [trufflesuite.com](https://trufflesuite.com/ganache/)
   - This will be your local blockchain for development

4. **Firebase Account**
   - Create a project at [firebase.google.com](https://firebase.google.com)
   - Enable Authentication and Firestore

5. **Pinata Account**
   - Sign up at [pinata.cloud](https://pinata.cloud)
   - Get your API keys for IPFS storage

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/blockchain-certificate-system.git
   cd blockchain-certificate-system
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configure Environment Variables**
   Create a `.env` file in the root directory:
   ```env
   PORT=3000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   PINATA_API_KEY=your_pinata_api_key
   PINATA_SECRET_API_KEY=your_pinata_secret_key
   FIREBASE_API_KEY=your_firebase_api_key
   FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   FIREBASE_PROJECT_ID=your_firebase_project_id
   FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
   FIREBASE_APP_ID=your_firebase_app_id
   ```

4. **Deploy Smart Contracts**
   ```bash
   # Start Ganache
   # Then in a new terminal:
   truffle migrate --network development
   ```

5. **Start the Application**
   ```bash
   npm start
   ```

6. **Access the Application**
   - Open your browser and go to `http://localhost:3000`
   - Connect your MetaMask wallet
   - Log in with your credentials

## 👥 User Roles

### Issuer (Educational Institution)
1. Log in with your institution email
2. Navigate to the certificate generation page
3. Fill in student details and course information
4. Generate and issue certificates

### Student
1. Log in with your student email
2. Go to the certificate validation page
3. Enter your certificate ID
4. View and verify your certificate

## 🔧 Configuration

### Firebase Setup
1. Create a new Firebase project
2. Enable Email/Password authentication
3. Create a Firestore database
4. Copy your Firebase configuration

### Pinata Setup
1. Create a Pinata account
2. Generate API keys
3. Test IPFS upload functionality

### Smart Contract Deployment
1. Update contract address in `src/config/contract.js`
2. Verify contract on Etherscan (optional)

## 🐛 Troubleshooting

### Common Issues

1. **MetaMask Connection Error**
   - Ensure MetaMask is installed and unlocked
   - Connect to the correct network (Ganache for development)
   - Check if you have enough ETH for gas fees

2. **Firebase Authentication Error**
   - Verify Firebase configuration
   - Check if email/password authentication is enabled
   - Ensure correct API keys are set

3. **IPFS Upload Failed**
   - Verify Pinata API keys
   - Check internet connection
   - Ensure file size is within limits

### Getting Help

- Check the [Issues](https://github.com/yourusername/blockchain-certificate-system/issues) page
- Create a new issue with detailed error information
- Join our [Discord community](your_discord_link)

## 📚 Documentation

For detailed documentation, visit our [Wiki](your_wiki_link)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Ethereum](https://ethereum.org/)
- [IPFS](https://ipfs.io/)
- [Firebase](https://firebase.google.com/)
- [Pinata](https://pinata.cloud/)
- [Truffle](https://trufflesuite.com/)

## 📞 Support

For support, email support@yourdomain.com or join our Discord channel.
