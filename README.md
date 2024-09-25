# Pico Wallet Mobile Application Overview
The **Pico Wallet** is a mobile application designed for users to manage their cryptocurrency assets, enabling them to send, receive, and swap tokens. It integrates decentralized features, allowing users to browse decentralized applications (dApps) through an in-app browser. The app provides an intuitive interface with functionalities that cater to both everyday users and administrators managing backend systems. The projects were completed using a combination of manual testing techniques and test management tools.

Here’s a more detailed breakdown of the project's features, architecture, and goals:

# Core Functionalities

**User Registration and Authentication:**
Registration: New users can register using their email. The registration process includes validation checks such as avoiding duplicate emails.
Login: After registration, users can log in securely using their credentials.
Forgot Password: The app includes a mechanism for users to reset their passwords securely.

**Wallet Management:**
Send/Receive Tokens: Users can transfer cryptocurrencies between wallets, with the app ensuring the correct display of balances after each transaction.
Token Support: The app supports multiple tokens, allowing users to manage a range of assets.

**Token Swap:**
Token Exchange: Users can swap one token for another directly within the app, using integrated smart contract functionality or third-party services for token exchange.
Real-time Balance Updates: After performing a swap, the wallet updates in real-time to reflect the newly acquired tokens.

**In-App Browser:**
Decentralized Web Access: Users can interact with dApps directly from within the Pico Wallet app. This feature is designed for seamless integration with the blockchain ecosystem, allowing users to explore and use various dApps without leaving the wallet.
Bookmarking and Favorites: The browser supports bookmarking of frequently visited dApp URLs.

**Collectibles and NFTs:**
Display of NFTs: Users can view their non-fungible tokens (NFTs) in the collectibles section of the app. These could include art, digital goods, and other blockchain-backed assets.
Management of Digital Assets: The app supports managing, transferring, and selling NFTs.
Admin Panel:

**Advanced Management:**
Admin users have special permissions to manage the application’s backend. This could involve setting permissions, managing system configurations, or even monitoring user activity.
Audit Logs: The admin panel provides visibility into critical actions taken by users, including sensitive transactions.

**Settings and Customizations:**
Profile Management: Users can update their personal details, including changing their email, managing security features like two-factor authentication, and more.
Notification Management: Users can customize what kind of push notifications they want to receive, such as transaction alerts, promotions, and app updates.
Security Settings: Settings like PIN code protection, biometric security, and passphrase options enhance user security.

**Main Screen Overview:**
Balance Display: Users can see their current wallet balance, showing each asset they hold.
Recent Transactions: A history of recent transactions is shown on the main screen for quick access.
Quick Access to Functions: Send, receive, and swap buttons are accessible directly from the main screen.

# Tools

 Description | Tools Used |
-------------|------------|
Tested a web application for functionality and usability. | JIRA, Selenium |
Tested a mobile application for compatibility across different devices. | BrowserStack |
Tested a desktop application for security vulnerabilities. | Burp Suite |

## Technical Overview and Architecture

**Technology Stack:**

**Frontend**: The mobile app likely uses a hybrid or native framework like React Native or Flutter to ensure compatibility across iOS and Android platforms.
**Backend**: The app may rely on a backend service built using Node.js, Python (Django/Flask), or another web server, possibly with blockchain integration for interacting with smart contracts.
**Blockchain Integration**: Interaction with the Ethereum blockchain or similar for managing tokens and NFTs, with the integration of APIs like Web3 for wallet functionality.
**Database**: A secure database system (such as PostgreSQL or MongoDB) is used for user data, with encrypted storage for sensitive information.

**Security:**
**Private Key Management**: Users are responsible for their wallet’s private keys, meaning the app likely has mechanisms in place to help users securely store and back up their keys.
**Two-Factor Authentication**: Optional 2FA is included for login security.
**Encrypted Transactions**: All transaction data is encrypted end-to-end, ensuring that no sensitive information is leaked.

**Smart Contract Support:**
**Token Contracts:** The app supports standard token types like ERC-20 (for fungible tokens) and ERC-721 (for NFTs), with the ability to interact directly with these contracts.
**Swapping Mechanism**: Token swapping could use protocols like Uniswap or other decentralized exchanges (DEX) to facilitate trades.


## Templates
- Test Plan
- Test Cases
- Bug Report
- RTM
- Test Reports
- Test Metrics


