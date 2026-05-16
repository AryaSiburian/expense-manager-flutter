# Flutter Finance Tracker

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-3.0+-02569B?style=for-the-badge&logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.0+-00B4AB?style=for-the-badge&logo=dart)
![BLoC](https://img.shields.io/badge/BLoC-State%20Management-8842F7?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A beautiful, feature-rich personal finance management application built with Flutter, enabling users to track income, expenses, and visualize their financial data.

[Features](#features) • [Tech Stack](#tech-stack) • [Getting Started](#getting-started) • [Screenshots](#screenshots) • [Contributing](#contributing)

</div>

---

## 📱 About

Flutter Finance Tracker is a comprehensive mobile application designed to help users manage their personal finances efficiently. With an intuitive interface and powerful features, it allows users to track transactions, categorize expenses, visualize spending patterns, and maintain complete control over their financial data—all stored securely on their device.

---

## ✨ Features

- 💰 **Dashboard Summary** - Real-time overview of income, expenses, and account balance
- ➕ **Transaction Management** - Add and delete transactions with ease
- 📜 **Transaction History** - View all transactions with advanced filtering by category
- 📊 **Financial Visualization** - Beautiful chart visualizations of monthly expenses
- 🌓 **Dark/Light Mode** - Seamless theme switching for comfortable viewing
- 💾 **Local Data Persistence** - All data is securely stored locally using Hive database
- 📱 **Responsive Design** - Optimized UI that works across different screen sizes

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **Flutter** | Cross-platform UI toolkit |
| **Dart** | Programming language |
| **BLoC** | State management |
| **get_it** | Dependency injection / service locator |
| **Hive** | Local storage persistence |
| **fl_chart** | Chart visualizations |

---

## 🏛️ Architecture

Clean Architecture with 3 layers:
- **Presentation** — pages, widgets, bloc
- **Domain** — entities, repositories interface, usecases
- **Data** — models, repositories implementation, datasources

---

## 📁 Folder Structure

```
lib/
├── core/
│   └── di/
│       └── injection.dart
├── data/
│   ├── datasources/
│   ├── models/
│   └── repositories/
├── domain/
│   ├── entities/
│   ├── repositories/
│   └── usecases/
├── presentation/
│   ├── bloc/
│   ├── pages/
│   └── widgets/
└── main.dart
```

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Flutter SDK** (version 3.0 or higher) - [Download here](https://flutter.dev/docs/get-started/install)
- **Dart SDK** (included with Flutter)
- **Git** - [Download here](https://git-scm.com/downloads)
- **Android Studio** or **Xcode** (for iOS development)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/AryaSiburian/expense-manager-flutter.git
   cd fintech-flutter
   ```

2. **Install dependencies**

   ```bash
   flutter pub get
   ```

3. **Run code generation** (if using any code generators)

   ```bash
   flutter pub run build_runner build
   ```

4. **Connect a device or emulator**

   ```bash
   flutter devices
   ```

### Running the Application

- **Run in debug mode:**

  ```bash
  flutter run
  ```

- **Run in release mode:**

  ```bash
  flutter run --release
  ```

- **Run on specific device:**

  ```bash
  flutter run -d <device_id>
  ```

### Build APK/IPA

- **Build APK (Android):**

  ```bash
  flutter build apk
  ```

- **Build iOS app:**

  ```bash
  flutter build ios
  ```

---

## 📸 Screenshots

<div align="center">

| Dashboard | Transactions | Add Transaction |
|-----------|--------------|-----------------|
| ![Dashboard](https://via.placeholder.com/250x500?text=Dashboard) | ![Transactions](https://via.placeholder.com/250x500?text=Transactions) | ![Add Transaction](https://via.placeholder.com/250x500?text=Add+Transaction) |

| Charts | Dark Mode | Settings |
|--------|-----------|----------|
| ![Charts](https://via.placeholder.com/250x500?text=Charts) | ![Dark Mode](https://via.placeholder.com/250x500?text=Dark+Mode) | ![Settings](https://via.placeholder.com/250x500?text=Settings) |

</div>

*Screenshots are placeholders. Replace with actual app screenshots.*

---

## 🤝 Contributing

Contributions are welcome and greatly appreciated! To contribute to this project:

1. **Fork the repository**

   ```bash
   git clone https://github.com/yourusername/expense-manager-flutter.git
   ```

2. **Create a feature branch**

   ```bash
   git checkout -b feature/amazing-feature
   ```

3. **Make your changes**

   - Follow the existing code style and patterns
   - Write clear, descriptive commit messages

4. **Commit your changes**

   ```bash
   git commit -m 'Add: amazing-feature'
   ```

5. **Push to the branch**

   ```bash
   git push origin feature/amazing-feature
   ```

6. **Open a Pull Request**

   - Describe the changes you've made
   - Reference any related issues

### Code Guidelines

- Follow Dart style guide: [Effective Dart](https://dart.dev/guides/language/effective-dart)
- Use meaningful variable and function names
- Add comments for complex logic
- Write unit tests for new features

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

```
MIT License

Copyright (c) 2024 Flutter Finance Tracker

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 📞 Contact & Support

For questions, suggestions, or bug reports, please:

- Open an [Issue](https://github.com/AryaSiburian/expense-manager-flutter/issues)
- Create a [Discussion](https://github.com/AryaSiburian/expense-manager-flutter/discussions)
- Reach out via email

---

<div align="center">

Made with ❤️ by the Flutter Finance Tracker Community

⭐ If you find this project helpful, please give it a star!

</div>
