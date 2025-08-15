# 🛏️ Pillow - Mental Health & Wellness Journal

<div align="center">
  <img src="assets/icons/launcher.png" alt="Pillow App Logo" width="200" height="200"/>
  
  [![Flutter](https://img.shields.io/badge/Flutter-3.3.4+-02569B?style=flat&logo=flutter)](https://flutter.dev)
  [![Dart](https://img.shields.io/badge/Dart-3.0+-0175C2?style=flat&logo=dart)](https://dart.dev)
  [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
  [![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen)]()
  [![Version](https://img.shields.io/badge/Version-2.1.1-blue)]()

  **A privacy-first mental health companion that helps you track your wellness journey, manage medications, and find emotional support.**
  
  *Your data stays on your device. Always.*

</div>

---

## 📱 About Pillow

Pillow is a comprehensive mental health and wellness tracking application designed with privacy at its core. Unlike other health apps, **all your data remains securely stored on your device** and never leaves your phone. The app combines mood tracking, medication management, guided meditation, and AI-powered symptom prediction to provide a holistic approach to mental wellness.

> **⚠️ IMPORTANT DISCLAIMER**: This is an experimental research project made open source for educational and development purposes. This app is **NOT a medical device** and does not claim to improve your mental or physical health in any way. It should **NEVER be considered a replacement for professional healthcare providers**, licensed therapists, psychiatrists, or medical professionals. Always consult with qualified healthcare providers for medical advice, diagnosis, or treatment.

### 🌟 Why Pillow?

- **🔒 Privacy First**: Zero data collection - everything stays on your device
- **🧠 AI-Powered**: Smart symptom prediction using TensorFlow Lite
- **💊 Medication Tracking**: Never miss a dose with smart notifications
- **📊 Wellness Insights**: Beautiful charts and correlation analysis
- **🎵 Emotional Support**: Curated audio content for healing
- **📱 Cross-Platform**: Built with Flutter for iOS and Android

---

## ✨ Features

### 📝 **Journal & Mood Tracking**
- Daily mood logging with rich descriptions
- Symptom tracking with AI-powered predictions
- Correlation analysis between mood, symptoms, and medications
- Beautiful visualizations and trends

### 💊 **Smart Medication Management** 
- Comprehensive medication database with custom dosages
- Smart notification system with snooze and mark-taken actions
- Adherence tracking and reports
- Visual pill identification

### 🎵 **Guided Meditation & Audio Support**
- Curated healing audio tracks:
  - "The Voice You Needed"
  - "You're Not a Burden"
  - "What You Feel is Real"
  - "When You Miss Who You Used to Be"
  - And more...
- Breathing exercises with visual guidance
- Mindfulness sessions

### 📊 **Wellness Analytics**
- Interactive charts showing mood patterns
- Medication adherence statistics
- Symptom correlation analysis
- PDF report generation for healthcare providers
- Data export functionality

### 🤖 **AI-Powered Insights**
- TensorFlow Lite model for symptom prediction
- Personalized wellness recommendations
- Pattern recognition in mood and symptoms

### 🔔 **Smart Notifications**
- Medication reminders with action buttons
- Daily mood check-ins
- Wellness insights notifications
- Customizable notification sounds

---

## 🚀 Getting Started

### Prerequisites

- Flutter 3.3.4 or higher
- Dart 3.0 or higher
- Android Studio / VS Code
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/rudi-q/pillow-health-journal-app.git
   cd pillow-health-journal-app
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

### Building for Release

**Android:**
```bash
flutter build apk --release
# or
flutter build appbundle --release
```

**iOS:**
```bash
flutter build ios --release
```

---

## 🏗️ Architecture

Pillow follows clean architecture principles with clear separation of concerns:

```
lib/
├── core/
│   ├── models/          # Data models
│   ├── services/        # Core services (Hive, Navigation)
│   ├── theme/          # App theming
│   ├── util/           # Utilities and helpers
│   └── widgets/        # Reusable widgets
├── features/
│   ├── journal/        # Mood tracking and journaling
│   ├── pillbox/        # Medication management
│   ├── wellness/       # Analytics and insights
│   ├── breathing/      # Breathing exercises
│   ├── meditation/     # Guided meditation
│   └── profile/        # User settings
└── main.dart
```

### Key Technologies

- **State Management**: Riverpod
- **Local Database**: Hive (NoSQL)
- **AI/ML**: TensorFlow Lite
- **Charts**: FL Chart
- **Audio**: Just Audio
- **Notifications**: Flutter Local Notifications
- **PDF Generation**: PDF package
- **Navigation**: Go Router

---

## 🧪 Testing

Pillow includes comprehensive testing:

```bash
# Run all tests
flutter test

# Run integration tests
flutter drive --target=integration_test/app_test.dart

# Run specific test files
flutter test test/features/journal/
```

### Test Coverage
- Unit tests for business logic
- Widget tests for UI components
- Integration tests for user flows
- Notification action testing

---

## 🤝 Contributing

We welcome contributions from the community! Whether you're fixing bugs, adding features, or improving documentation, your help is appreciated.

### How to Contribute

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Add tests** for new functionality
5. **Run tests** and ensure they pass
   ```bash
   flutter test
   ```
6. **Commit your changes**
   ```bash
   git commit -m "Add amazing feature"
   ```
7. **Push to your branch**
   ```bash
   git push origin feature/amazing-feature
   ```
8. **Open a Pull Request**

### Development Guidelines

- Follow [Flutter style guide](https://dart.dev/guides/language/effective-dart/style)
- Write tests for new features
- Update documentation as needed
- Ensure privacy-first principles are maintained

### Areas We Need Help

- 🌐 **Internationalization**: Help translate the app
- 🎨 **UI/UX**: Improve accessibility and user experience
- 🧪 **Testing**: Add more test coverage
- 📚 **Documentation**: Improve guides and tutorials
- 🤖 **AI/ML**: Enhance symptom prediction models

---

## 🛡️ Privacy & Security

### Privacy First Design
- **No data collection**: All data remains on your device
- **No analytics tracking**: We don't track user behavior
- **No cloud sync**: Data never leaves your device
- **Open source**: Full transparency in code

### Security Features
- Local encryption for sensitive data
- Secure local notifications
- No network requests for personal data
- Privacy-focused third-party dependencies

---

## ⚠️ Medical Disclaimer & Research Notice

### 🔬 **Experimental Research Project**
This application is an **experimental research project** developed for educational, research, and open-source development purposes. It is made available to the community to advance understanding of mental health tracking technologies and privacy-preserving app development.

### 🏥 **Not a Medical Device or Healthcare Service**
**IMPORTANT:** This app is **NOT**:
- A medical device or diagnostic tool
- A substitute for professional medical advice, diagnosis, or treatment
- Intended to cure, treat, prevent, or diagnose any medical condition
- A replacement for therapy, counseling, or psychiatric care
- Clinically validated or FDA-approved

### 👩‍⚕️ **Professional Healthcare Advisory**
**ALWAYS consult with qualified healthcare professionals** including but not limited to:
- Licensed physicians and psychiatrists
- Licensed therapists and counselors
- Certified mental health professionals
- Your primary care provider

**Before making any decisions about your mental health, medication, or treatment based on information from this app.**

### ⚠️ **Emergency Situations**
If you are experiencing a mental health emergency or crisis:
- **Call emergency services immediately (911, 988 Suicide & Crisis Lifeline)**
- **Contact your local crisis intervention center**
- **Go to your nearest emergency room**
- **This app cannot and should not be used for emergency situations**

### 📜 **Limitation of Liability**
By using this experimental research application, you acknowledge that:
- The developers, contributors, and maintainers assume no responsibility for any health outcomes
- All data and insights provided are for informational and research purposes only
- You use this application at your own risk
- Any decisions regarding your health should be made in consultation with qualified healthcare providers

### 🔍 **Research and Data Use**
This is a research project designed to:
- Explore privacy-preserving mental health tracking technologies
- Demonstrate on-device AI/ML capabilities
- Advance open-source mental health tools development
- **All your data remains on your device and is never transmitted or collected**

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Additional Terms:** By using this software, you acknowledge that you have read and understood the Medical Disclaimer above and agree to use this experimental research application in accordance with these terms.

---

## 🙏 Acknowledgments

- **Flutter Team** for the amazing framework
- **TensorFlow Lite** for on-device ML capabilities
- **Hive** for fast local storage
- **All contributors** who help make Pillow better
- **Mental health advocates** who inspire this work

---

## 📞 Support

Need help or have questions?

- 📧 **Email**: pillow@doubl.one
- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/rudi-q/pillow-health-journal-app/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/rudi-q/pillow-health-journal-app/discussions)

---

## 🔮 Roadmap

- [ ] **Multi-language support**
- [ ] **Apple Health / Google Fit integration**
- [ ] **Enhanced AI models**
- [ ] **Accessibility improvements**
- [ ] **Desktop support**
- [ ] **Advanced analytics**

---

<div align="center">
  <h3>🕊️ "Your mental health matters. Your privacy matters more." 🕊️</h3>
  
  **Made with ❤️ for mental health awareness**
  
  ⭐ **Star this repo if you found it helpful!** ⭐
</div>
