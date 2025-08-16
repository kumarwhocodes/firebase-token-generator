# 🔐 Firebase Token Generator

> A simple web application to generate Firebase ID tokens using Google authentication

###

[![Try it now](https://img.shields.io/badge/Try_it_now-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://firebase-token-generator-peach.vercel.app/)

## 🚀 Quick Start

### Using the Live Version

1. Visit the [live demo](https://firebase-token-generator-peach.vercel.app/)
2. Enter your Firebase Project ID
3. Enter your Firebase Web API Key
4. Click "Sign In with Google"
5. Copy your generated token

### Getting Firebase Credentials

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Select your project
3. Go to **Project Settings** ⚙️
4. In the **General** tab, find your **Project ID**
5. In the **Web API Key** section, copy the API key

## 💻 Local Development

### Prerequisites

- A modern web browser
- Firebase project with Google authentication enabled

### Clone & Run

```bash
# Clone the repository
git clone https://github.com/yourusername/firebase-token-generator.git

# Navigate to project directory
cd firebase-token-generator

# Open in browser (no build step required!)
open index.html
```

### Firebase Setup

1. **Enable Google Authentication:**
   - Go to Firebase Console → Authentication → Sign-in method
   - Enable Google provider
   - Add your domain to authorized domains

2. **Configure Web App:**
   - Go to Project Settings → General
   - Add a web app if you haven't already
   - Copy the config values

## 🔧 Configuration

No configuration files needed! Just enter your credentials in the web interface:

- **Project ID**: Your Firebase project identifier
- **API Key**: Your Firebase web API key

## 📁 Project Structure

```
firebase-token-generator/
├── index.html          # Main application file
└── README.md          # This file
```

## 🛡️ Security Notes

- ✅ No credentials are stored or transmitted to any server
- ✅ All authentication happens client-side with Firebase
- ✅ Tokens are generated locally in your browser
- ✅ No backend or database required

## 🚀 Deploy Your Own

### Deploy to Vercel 

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/firebase-token-generator)

## 🤝 Contributing

Contributions are welcome! Feel free to:

- 🐛 Report bugs
- 💡 Suggest features
- 🔧 Submit pull requests

## 📄 License

MIT License - feel free to use this project for any purpose.

---

<div align="center">
  <strong>Made with ☕</strong>
</div>