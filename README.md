# 🤖 HiveraBot

<div align="center">

![HiveraBot Logo](https://i.postimg.cc/rpfwBN2G/IMG-20241221-005425-839.jpg)

[![Python Version](https://img.shields.io/badge/python-3.12.3%2B-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Telegram](https://img.shields.io/badge/Telegram-@zsan0x-blue.svg)](https://t.me/zsan0x)

*Your ultimate automation companion for Hivera Telegram bot 🚀*

</div>

## ✨ Features

- 🎯 **Smart Task Management**
  - Auto-fetch daily tasks and missions
  - Intelligent task completion algorithms
  - Real-time task status monitoring

- 🔄 **Power Boost Automation**
  - Automated contribution system
  - Strategic power boosting
  - Optimal timing calculations

- 🛡️ **Multi-Account Support**
  - Secure proxy integration
  - Account rotation mechanism
  - Load balancing capabilities

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Termux (for Android users)
- Basic knowledge of Telegram bots

### 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/zsan0x/HiveraBot.git
   cd HiveraBot
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up configuration files**
   - `config.json`: Bot settings
   - `auth_data.txt`: Authentication data
   - `proxies.txt`: Proxy list (optional)

## 🔐 Authentication Setup

### Getting Your Auth Data

1. Navigate to the Hivera website
2. Log in to your account
3. Open Developer Tools (`Ctrl+Shift+I` or `Cmd+Option+I`)
4. Go to the Network tab
5. Filter requests by `XHR`
6. Look for requests containing `auth_data`
7. Copy the auth_data value

![Auth Data Location](https://github.com/zsan0x/HiveraBot/blob/main/AuthData.jpg)

## 📱 Running on Termux

```bash
git clone https://github.com/zsan0x/HiveraBot
cd HiveraBot
pip install -r requirements.txt
nano config.json
nano auth_data.txt
python main.py
```

## ⚙️ Configuration

Edit `config.json` to customize your bot:

```json
{
    "auto_claim": true,
    "auto_contribute": true,
    "auto_contribute_timer": 300,
    "use_proxy": false
}
```

## 📁 Project Structure

```
HiveraBot/
├── main.py           # Main bot script
├── config.json       # Configuration file
├── auth_data.txt     # Authentication data
├── proxies.txt       # Proxy list
└── requirements.txt  # Python dependencies
```

## 🤝 Support & Contact

- **Telegram**: [@zsan0x](https://t.me/zsan0x)
- **Issues**: [GitHub Issues](https://github.com/zsan0x/HiveraBot/issues)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This bot is for educational purposes only. Use at your own risk and make sure to comply with Hivera's terms of service.

---

<div align="center">

Made with ❤️ by [@zsan0x](https://t.me/zsan0x)

⭐ Star this repo if you found it useful! ⭐

</div>
