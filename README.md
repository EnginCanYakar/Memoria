<p align="center">
  <img src="screenshots/feature_graphic.png" alt="Memoria banner" width="700"/>
</p>

<h1 align="center">Memoria</h1>
<p align="center"><b>Your Personal Diary & Photo Album</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/State%20Management-BLoC-3f51b5" alt="BLoC"/>
  <img src="https://img.shields.io/badge/Backend-Firebase-FFCA28?logo=firebase&logoColor=black" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/License-All%20Rights%20Reserved-red" alt="License"/>
</p>

Memoria is a private diary and photo album app built with Flutter. Capture your everyday moments with text, photos, voice notes, mood, and location — all kept offline, encrypted, and completely private on your device.

> 📲 **Download on Google Play:** [Add your Play Store link here]

---

## ✨ Features

| | |
|---|---|
| 😊 **Mood Tracking** | Tag each memory with how you felt in that moment |
| 📸 **Photos, Videos & Voice** | Add rich media to every entry — not just text |
| 📍 **Location Memories** | Every memory can be pinned to where it happened |
| 🗺️ **Memories Map** | See all your memories laid out on an interactive map (Standard / Light / Dark) |
| 💾 **Offline & Local Storage** | Works fully offline — your data stays on your device |
| 🔒 **100% Private & Secure** | Lock the app with a PIN or biometric (fingerprint) authentication |
| ⭐ **Favorites** | Mark your favorite moments and revisit them anytime |
| 🎨 **Customizable Themes** | Personalize card colors and design your diary the way you feel |
| 🔍 **Search** | Quickly find entries by title or date |

---

## 📱 Screenshots

<p align="center">
  <img src="<img width="1024" height="500" alt="Feature graphic" src="https://github.com/user-attachments/assets/1f1771f5-71ee-471f-b5fc-f3344b69b2b3" />
/>
  <img src="screenshots/add_memory.jpeg" width="200"/>
  <img src="screenshots/memories_map.jpeg" width="200"/>
  <img src="screenshots/security_lock.png" width="200"/>
  <img src="screenshots/favorites_themes.jpeg" width="200"/>
</p>

---

## 🛠️ Tech Stack

- **Framework:** Flutter
- **State Management:** BLoC
- **Architecture:** Clean Architecture (`core`, `data`, `domain`, `presentation` layers)
- **Backend / Services:** Firebase
- **Design:** Figma
- **Storage:** Local/offline-first storage

### Project structure

```
lib/
├── core/           # Shared utilities, constants, theming, base classes
├── data/           # Data sources, repositories implementation, models
├── domain/         # Entities, repository interfaces, use cases
├── presentation/   # UI, BLoC/Cubit, pages, widgets
├── ad_helper.dart
├── firebase_options.dart
└── main.dart
```

This project follows **Clean Architecture** principles, separating concerns into distinct layers to keep the codebase scalable, testable, and maintainable.

---

## 🚀 Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (stable channel)
- Android Studio / VS Code with Flutter & Dart plugins
- A Firebase project (if you want to run the backend-dependent features yourself)

### Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/memoria.git
cd memoria

# Install dependencies
flutter pub get

# Run the app
flutter run
```

> ⚠️ **Note:** This repository does **not** include Firebase configuration files (`google-services.json`, real values inside `firebase_options.dart`) or signing keys for security reasons. To run the app with your own Firebase backend, create a project in the [Firebase Console](https://console.firebase.google.com/) and generate your own config files with the FlutterFire CLI:
> ```bash
> flutterfire configure
> ```

---

## 🔐 Security & Privacy

Memoria was built with privacy as a core principle:

- All diary entries are stored **locally on the device**
- Optional **PIN or biometric lock** for app access
- No data is shared with third parties

---

## 📄 License

**All Rights Reserved.**

This source code is shared publicly for **portfolio and educational viewing purposes only**.
You may **not** copy, modify, distribute, sublicense, or use this code (in whole or in part) for commercial or non-commercial purposes without explicit written permission from the author.

If you'd like to use any part of this project, please reach out first.

---

## 👤 Author

Developed and maintained by **[Your Name]**.

- Play Store: [Add link]
- Contact: [Add email or LinkedIn]

---

<p align="center">Made with ❤️ using Flutter</p>
