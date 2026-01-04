# 🚀 Neou.io - An Outer Worldly Adventure

![Neou.io Banner](https://neou.io/videos/HowToPlay.png)

**A multiplayer space adventure game built with Unity WebGL and Photon PUN 2.0**

## 🌌 Live Demo
Play the game now at: **[https://neou.io](https://neou.io)**

## 🎮 About the Game

Neou.io is an immersive multiplayer space adventure game where players explore uncharted galaxies, battle cosmic enemies, and compete in real-time space combat. Built with cutting-edge WebGL technology, the game delivers a seamless gaming experience directly in your browser.

### ✨ Key Features
- **Real-time Multiplayer**: Battle with players worldwide in intense space adventures
- **Cross-platform Play**: Works on desktop, tablet, and mobile devices
- **No Downloads Required**: Instant play directly from your browser
- **Leaderboard System**: Compete for top rankings and earn special rewards
- **Customizable Characters**: Unique skins, abilities, and equipment
- **Multiple Game Modes**: Moon Ran races, Team Battles, and Survival Mode

## 🛠️ Technology Stack

| Component | Technology |
|-----------|------------|
| Game Engine | Unity 2022.3+ |
| Multiplayer | Photon PUN 2.0 |
| Backend | Firebase (Auth, Realtime Database) |
| Frontend | HTML5, CSS3, JavaScript |
| Hosting | GitHub Pages |
| Domain | Custom Domain (neou.io) |

## 📁 Project Structure
neou.io/
├── index.html # Main game page
├── about.html # About page
├── privacy.html # Privacy policy
├── terms.html # Terms of service
├── manifest.json # PWA manifest
├── README.md # This file
├── Build/ # Unity WebGL build files
│ ├── NeouWebGL.loader.js
│ ├── NeouWebGL.framework.js
│ ├── NeouWebGL.data
│ └── NeouWebGL.wasm
├── icons/ # PWA icons
│ └── icon-192.png
└── videos/ # Game assets
└── HowToPlay.png

text

## 🚀 Local Development

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local HTTP server (for testing)
- Basic understanding of HTML/CSS/JavaScript

### Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/neou.io.git
   cd neou.io
Serve the files locally:

bash
# Using Python 3
python3 -m http.server 8000

# Or using Node.js
npx http-server
Open in browser:

text
http://localhost:8000
🌐 Deployment
This project is automatically deployed via GitHub Pages:

Push changes to the main branch

GitHub Pages automatically deploys from the root directory

Custom domain configured through GitHub Pages settings

SSL certificate automatically provided by GitHub

Deployment Notes:
The site is served from the repository root

CNAME file contains: neou.io

Build files are generated from Unity and committed directly

No build process required for deployment

🔧 Firebase Configuration
The game uses Firebase for:

User authentication (email/password, anonymous)

Realtime database (leaderboards, player stats)

Cloud Functions (server-side logic)

Firebase Services Used:
Authentication: User sign-in/sign-up

Realtime Database: Player data, leaderboards, party system

Cloud Functions: Secure username validation, crown awards

Hosting: (Optional) For Cloud Functions

🎯 Game Features Implementation
Multiplayer System
Real-time synchronization via Photon PUN 2.0

Room-based matchmaking

Party system for team play

User System
Account creation with username/email

Anonymous guest accounts

Password reset functionality

Email verification

Leaderboards
Real-time crown tracking

Multiple game mode support

Global and friend-based rankings

Social Features
Friend system (send/accept/reject requests)

Party invitations

Online status indicators

📱 Progressive Web App (PWA)
Neou.io is a fully functional PWA:

Installable: Add to home screen on mobile/desktop

Offline Capable: Caches game assets

Responsive: Adapts to all screen sizes

App-like Experience: Fullscreen, standalone mode

PWA Features:
manifest.json configuration

Service worker for caching

iOS PWA installation instructions

Fullscreen support

🔒 Privacy & Security
All passwords are securely hashed

Firebase Security Rules protect database access

HTTPS encryption for all communications

GDPR-compliant privacy practices

📈 Analytics & Ads
Google AdSense: For monetization (pending approval)

Firebase Analytics: Game performance tracking

Custom Analytics: Player retention, game mode popularity

🐛 Known Issues & Limitations
iOS Safari Audio: Requires user interaction to start audio

WebGL Memory: Large game assets may cause memory issues on low-end devices

Firebase Limits: Free tier has concurrent connection limits

🔮 Future Improvements
Additional game modes

More customization options

Social sharing features

Tournament system

Mobile app versions (iOS/Android)

Cloud save synchronization

🤝 Contributing
While this is primarily a solo project, suggestions and feedback are welcome:

Fork the repository

Create a feature branch

Make your changes

Submit a pull request

📄 License
This project is proprietary. All rights reserved.

Game code: Proprietary

Assets: Original or properly licensed

Third-party libraries: Respective licenses apply

👨‍💻 Developer
Game Developer & Publisher
Passionate about creating immersive gaming experiences that push the boundaries of browser-based games.

📞 Support
For technical issues or game support:

Website: https://neou.io

Email: support@neou.io

Made with ❤️ and Unity | Hosted on GitHub Pages | © 2023 Neou.io

"Exploring the universe, one game at a time."
