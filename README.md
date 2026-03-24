# 📖 Al Quran & Azkar App

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![BLoC](https://img.shields.io/badge/BLoC-Cubit-8A2BE2?style=for-the-badge)
![Clean Architecture](https://img.shields.io/badge/Clean-Architecture-green?style=for-the-badge)

A modern, feature-rich Islamic mobile application built with **Flutter** — providing Quran reading, daily Azkar, accurate prayer times, and Qibla direction, all in one elegant experience.

> 🤝 **Team Project** — Built collaboratively by [Mohamed Esham](https://github.com/Mohamedesham) & [Hazem Lotfy](https://github.com/HazemLotfy74) as part of our ITI Front-End & Cross Platform training program.

</div>

---

## 📱 Screenshots

| Home | Azkar | Prayer Times | Qibla |
|------|-------|--------------|-------|
| ![Home](Alquran%20Screenshots/home.jpeg) | ![Azkar](Alquran%20Screenshots/azkar.jpeg) | ![Prayer](Alquran%20Screenshots/pray%20time.jpeg) | ![Qibla](Alquran%20Screenshots/qibla.jpeg) |

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📖 **Holy Quran** | Full Quran reading with clean Arabic typography |
| 🤲 **Daily Azkar** | Morning, evening & various supplications |
| 🕌 **Prayer Times** | Accurate times based on your real-time GPS location |
| 🧭 **Qibla Direction** | Live compass pointing toward Mecca |
| 📶 **Offline Support** | Core features available without internet |
| 🌙 **Arabic UI** | Fully localized Arabic language interface |
| 🎨 **Clean UI** | Modern, distraction-free design |

---

## 🛠️ Tech Stack

### Core
- **Flutter** — Cross-platform UI framework (Android & iOS)
- **Dart** — Programming language

### Architecture & State Management
- **Clean Architecture** — Separation of concerns across Data, Domain & Presentation layers
- **BLoC / Cubit** — Predictable, scalable state management
- **GetIt** — Service locator for dependency injection

### APIs & Services
- **REST API** — Quran content & Azkar data
- **Adhan Library** — Precise Islamic prayer time calculations
- **Location Services** — GPS-based prayer times & Qibla
- **Connectivity Plus** — Network state detection

---

## 🏗️ Architecture

This app follows **Clean Architecture** principles, structured into three main layers:

```
lib/
├── core/                  # Shared utilities, constants, theme
├── features/
│   ├── quran/
│   │   ├── data/          # API calls, models, repositories impl
│   │   ├── domain/        # Entities, use cases, repo contracts
│   │   └── presentation/  # UI screens, BLoC/Cubit, widgets
│   ├── azkar/
│   ├── prayer_times/
│   └── qibla/
└── main.dart
```

**Key principles applied:**
- ✔ Separation of concerns between layers
- ✔ Dependency inversion via repository pattern
- ✔ Testable business logic isolated from UI
- ✔ Scalable feature-first folder structure

---

## 👨‍💻 Team Contributions

### Mohamed Esham
- UI design & screen implementation across all features
- BLoC/Cubit state management integration
- REST API integration for Quran & Azkar data

### Hazem Lotfy
- Project setup & architecture foundation
- Prayer times & Qibla direction implementation
- Location services & sensor integration

---

## 🚀 Getting Started

### Prerequisites
- Flutter SDK `>=3.0.0`
- Dart SDK `>=3.0.0`
- Android Studio / VS Code

### Installation

```bash
# Clone the repository
git clone https://github.com/Mohamedesham/alquran.git

# Navigate to the project directory
cd alquran

# Install dependencies
flutter pub get

# Run the app
flutter run
```

---

## 📦 Key Dependencies

```yaml
dependencies:
  flutter_bloc: ^8.x      # State management
  get_it: ^7.x            # Dependency injection
  adhan: ^2.x             # Prayer time calculations
  geolocator: ^10.x       # GPS location
  connectivity_plus: ^5.x # Network detection
  dio: ^5.x               # HTTP client
```

---

## 🎓 About This Project

This app was developed as part of the **ITI (Information Technology Institute) Front-End & Cross Platform Development Track** graduation projects. It demonstrates real-world application of:

- Flutter cross-platform development
- Clean Architecture in mobile apps
- Islamic app domain knowledge & API integration
- Team collaboration using Git & GitHub

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

Made with ❤️ by **Mohamed Esham** & **Hazem Lotfy** — ITI Graduates 🎓

</div>
