# Dental Care - Professional Dental Practice Management App

## 📱 Overview

DentalConnect is a comprehensive Flutter-based mobile application designed to streamline dental practice operations. The app provides a modern, user-friendly interface for dental professionals to manage appointments, track orders, and handle patient information efficiently.

## 🚀 Features

### 🔐 Authentication & Security
- **Secure Login/Registration**: Firebase Authentication integration
- **Multi-language Support**: English and Arabic localization
- **Biometric Authentication**: Local authentication support
- **Password Strength Validation**: Real-time password strength checking
- **Session Management**: Secure token-based authentication

### 🏠 Home Dashboard
- **appoinments Management**: View and manage daily dental appointments 
- **appointments History**: Comprehensive historical data access
- **Pull-to-Refresh**: Easy data synchronization

### 👤 Profile Management
- **Personal Information**: Complete profile management system
- **Profile Editing**: Easy profile information updates
- **Photo Upload**: Profile picture management
- **Account Settings**: User preferences and settings

### 🎨 User Interface
- **Responsive Design**: Adaptive layout for various screen sizes
- **Dark/Light Theme**: Customizable theme support
- **Modern UI**: Material Design 3 implementation
- **Smooth Animations**: Enhanced user experience with animations
- **Accessibility**: Support for different accessibility needs

## 🛠 Technical Architecture

### Frontend Framework
- **Flutter**: Cross-platform mobile development
- **Dart**: Programming language
- **BLoC Pattern**: State management architecture
- **Provider**: Dependency injection

### Backend Services
- **Firebase**: Authentication and cloud services
- **Firestore**: NoSQL database
- **Firebase Storage**: File storage
- **RESTful APIs**: Custom backend integration

## 📱 Screenshots

### Authentication Screens
- Login screen with email/password and social login options
- Registration screen with comprehensive form validation

### Main Application
- Home dashboard with patient appointments
- Profile management interface
- Settings and preferences

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (3.5.4 or higher)
- Dart SDK
- Android Studio / VS Code
- Firebase project setup

### Installation

1. **Clone the repository**
   ```bash 
   git clone https://github.com/yhabbeh/dental-appointment.git
   cd dental
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   - Create a Firebase project
   - Add `google-services.json` to `android/app/`
   - Configure Firebase options in `lib/firebase_options.dart`

4. **Run the application**
   ```bash
   flutter run
   ```

## 🔧 Configuration

### Environment Setup
- Configure API endpoints in `lib/core/apis/api_paths.dart`
- Set up localization in `assets/l10n/`
- Configure theme settings in `lib/shared/theme_manager/`

### Firebase Configuration
1. Enable Authentication methods (Email/Password, Google)
2. Set up Firestore database
3. Configure Firebase Storage rules
4. Add security rules for data access

## 🌐 Localization

The app supports multiple languages:
- **English**: Primary language
- **Arabic**: RTL support with proper text direction

Localization files are located in `assets/l10n/`:
- `app_en.arb`: English translations
- `app_ar.arb`: Arabic translations

## 📦 Deployment

### Android
1. Update version in `pubspec.yaml`
2. Configure signing in `android/app/build.gradle.kts`
3. Build release APK
4. Upload to Google Play Store

### iOS
1. Update version in `pubspec.yaml`
2. Configure signing in Xcode
3. Build release IPA
4. Upload to App Store Connect

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support and questions:
- **Email**: yousef.habbeh@hotmail.com 
- **Issues**: [GitHub Issues](https://github.com/yhabbeh/dental-appointment/issues)

## 🔄 Version History

### v1.0.0 (Current)
- Initial release
- Authentication system
- Profile management
- Multi-language support

### Upcoming Features
- Push notifications
- Advanced analytics
- Patient management
- Appointment scheduling
- Payment integration

---

**Built with ❤️ using Flutter & Firebase**
