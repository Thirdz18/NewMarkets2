🌍 GoodMarket - Universal Basic Income Web Platform

A comprehensive web-based platform built for the GoodDollar ecosystem, providing Universal Basic Income (UBI) users with multiple ways to earn and spend their G$ tokens through interactive quizzes, bonuses, and mobile top-up services.

🚀 Features

🎓 Learn & Earn System
- Interactive 10-question quizzes about GoodDollar and cryptocurrency
- Earn 200 G$ per correct answer (up to 2000 G$ per quiz)
- 24-hour cooldown system to prevent abuse
- Real-time scoring and reward distribution

🎁 12-Hour Bonus System
- Automated bonus distribution every 12 hours
- Claim 50 G$ bonuses regularly
- Smart cooldown management
- Transaction logging and history tracking

📱 Mobile Top-up Service
- International mobile phone credit top-up using G$ tokens
- Support for multiple countries and operators
- Real-time payment processing and confirmation
- Order tracking and history management

💰 Wallet Integration
- Web3 wallet connectivity for G$ token balance checking
- Real-time balance updates and transaction monitoring
- Support for Celo blockchain network
- Secure wallet address verification

📊 Analytics Dashboard
Comprehensive real-time analytics for users and administrators
- User activity tracking and engagement metrics
- Platform-wide statistics and performance monitoring
- Individual user progress and earning history

🛠️ Tech Stack

- **Backend**: Flask (Python)
- **Blockchain**: Web3.py with Celo network integration
- **Frontend**: HTML/CSS/JavaScript with real-time updates
- **Authentication**: Wallet-based UBI verification system

## 📦 Project Structure

```
GoodMarket/
├── main.py                 # Main Flask application
├── blockchain.py           # UBI verification and session management
├── analytics_service.py    # Analytics and metrics service
├── learn_and_earn/         # Learn & Earn quiz system  
├── hour_bonus/             # 12-hour bonus system
├── goodmarket/             # Mobile top-up marketplace
└── templates/              # HTML templates
    ├── login.html          # Login page
    ├── overview.html       # Main overview page
    ├── dashboard.html      # User dashboard
    └── analytics.html      # Analytics dashboard
```

🔧 Setup & Installation

Prerequisites
- Python 3.11+
- Supabase account and project
- Celo network access
- Environment variables configured

Environment Variables
```bash
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_supabase_anon_key
CELO_RPC_URL=https://forno.celo.org
GOODDOLLAR_CONTRACT=0x62B8B11039FcfE5aB0C56E502b1C372A3d2a9c7A
CHAIN_ID=42220
LEARN_WALLET_PRIVATE_KEY=your_learn_wallet_private_key
HOUR_BONUS_AMOUNT=50.0
MERCHANT_ADDRESS=your_merchant_wallet_address
```

### Installation
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure environment variables
4. Run the application:
   ```bash
   python main.py
   ```

## 🌐 Usage

1. **Login**: Connect with your GoodDollar wallet address
2. **UBI Verification**: System verifies UBI claim within last 36 hours
3. **Explore Features**:
   - Take educational quizzes to earn G$ tokens
   - Claim 12-hour bonuses
   - Purchase mobile top-ups with G$ tokens
   - View real-time analytics and transaction history

## 📊 Key Metrics

- **Users**: 45+ active users
- **Quizzes**: 55+ completed with rewards distributed
- **Bonuses**: 155+ hourly bonuses claimed
- **Top-ups**: 47+ mobile credit orders processed
- **G$ Disbursed**: 79,510+ G$ tokens distributed
- **G$ Received**: 24,279+ G$ tokens received for services

## 🔒 Security Features

- UBI verification ensures only active GoodDollar users access features
- Session management with secure login system
- Anti-fraud measures with cooldown periods
- Blockchain-based transaction verification
- Wallet address masking for privacy

🌍 Multi-language Support
The platform includes Google Translate integration supporting 30+ languages for global accessibility.

📱Mobile-Friendly Design

Responsive design optimized for mobile devices with touch-friendly interfaces and clear navigation.

🚀 Deployment
The application is configured for deployment on Replit with automatic dependency management and port forwarding.
📞 Community Support

**Omar Jauro** - Community Lead Niger - Collaborator
📧 omar@goodmarket.live
**Betz Lenz** - Community Moderator - Developer

## 🤝 Contributing

This project is part of the GoodDollar ecosystem. For contributions and support, contact the community moderator team.

## 📄 License

Built for the GoodDollar community - promoting financial inclusion through blockchain technology.

---

**GoodMarket** - *Empowering financial inclusion through Universal Basic Income and blockchain technology* 🌟
