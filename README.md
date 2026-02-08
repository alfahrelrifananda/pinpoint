[![Latest release](https://img.shields.io/github/v/release/alfahrelrifananda/pinpoint?style=for-the-badge)](https://github.com/alfahrelrifananda/pinpoint/releases)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![License](https://img.shields.io/github/license/alfahrelrifananda/pinpoint?style=for-the-badge)](LICENSE)

# Pinpoint

**[Pinpoint](https://github.com/alfahrelrifananda/pinpoint)** is a privacy-focused network information app built with Flutter. Detect your public IP, check for VPN/Tor usage, and assess your network privacy with ease.

[![Get it on GitHub](https://img.shields.io/badge/Get%20it%20on-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alfahrelrifananda/pinpoint/releases)

## **Features**

- **Public IP Detection** – Automatically detect your public IP address with geolocation
- **VPN & Tor Detection** – Identify if you're using VPN or Tor networks
- **Network Interface Info** – View detailed local network information
- **Privacy Assessment** – Check for potential privacy leaks
- **Custom Providers** – Add your own IP lookup services
- **Privacy-First** – All data processed locally on your device

## **Tech Stack**

- **Language:** Dart
- **Framework:** Flutter
- **UI:** Material Design 3
- **State Management:** StatefulWidget with AutomaticKeepAliveClientMixin
- **Network:** HTTP package
- **Storage:** SharedPreferences

## **Getting Started**

### **Prerequisites**

- [Flutter SDK](https://flutter.dev/docs/get-started/install) 3.0+ (latest stable version)
- Android Studio / VS Code with Flutter extensions
- Android device or emulator (API 24+)

### **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/alfahrelrifananda/pinpoint.git
   cd pinpoint
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Run the app:
   ```bash
   flutter run
   ```

### **Build for Production**

```bash
# Android
flutter build apk --release

# iOS
flutter build ios --release

# Web
flutter build web --release
```

## **Usage**

- **Launch** the app to automatically check your network status
- **Pull down** to refresh or use the refresh button
- **Access settings** to add custom IP lookup providers
- **View detailed** information about your network privacy

## **Detection Methods**

### VPN Detection
- ISP and organization name analysis
- Pattern matching for known VPN providers
- Hosting provider identification
- ASN validation

### Tor Detection
- Organization name checking
- Tor Project API validation
- Third-party service verification
- Known Tor ASN database

## **Privacy**

All data is processed locally on your device. No information is sent to our servers. The app uses third-party IP lookup services to gather network information, but your data never passes through Pinpoint's infrastructure.

## **Contributing**

Contributions are what make the open-source community thrive! Feel free to:

- Fork the project
- Open issues for bugs or feature requests
- Submit pull requests with improvements
- Follow [Effective Dart](https://dart.dev/guides/language/effective-dart) guidelines

## **Acknowledgments**

Thanks to the Flutter team and the open-source community for making this project possible.

## **License**

This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](LICENSE) file for more details.
