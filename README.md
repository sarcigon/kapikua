# KAPIKUA 🏆

**KAPIKUA** is a professional, high-performance Domino Score Tracker built with Capacitor, Tailwind CSS, and Lucide Icons. Designed specifically for high-resolution Android devices (like the Galaxy S25+), it offers a zero-scroll, immersive experience for your domino nights.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Android-green.svg)

## ✨ Features

- **🎯 Zero-Scroll UI**: Optimized for high-res screens to keep all game controls visible at once.
- **🏆 DOS MAS! Victory**: Full-screen celebration and haptics when a team hits 200 points.
- **📊 Match Ledger**: Track lifetime wins/losses for all players.
- **🌓 Dark Mode**: Built-in slate-dark theme for low-light environments.
- **🛠️ Flexible Formats**: Support for 2v2 competitive matches or training sessions.

## 📦 Sharing the App

If you want to share the app with friends or fellow players:
1.  Navigate to `android/app/build/outputs/apk/debug/`.
2.  Share the **`kapikua.apk`** file.
3.  **Note**: This is a debug-signed APK. On most Android devices, the recipient will need to "Allow installation from unknown sources" in their security settings to install it.

## 🛠️ Development

### Prerequisites
- Node.js & npm
- Android Studio
- Capacitor CLI (`npm install -g @capacitor/cli`)

### Setup
1. Clone the repository.
2. Run `npm install`.
3. Sync Capacitor: `npx cap sync android`.
4. Open in Android Studio: `npx cap open android`.

### Build
To generate a new APK:
```bash
cd android
./gradlew assembleDebug
```

## 🤝 Contributing

Contributions are welcome! If you find a bug or have a layout suggestion for specific devices:
1. Fork the project.
2. Create your Feature Branch.
3. Commit your changes.
4. Push to the Branch.
5. Open a Pull Request.

## ⚖️ License
Distributed under the MIT License.
