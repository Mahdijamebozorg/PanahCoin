# Panah Coin – A Gold Trading Platform for Sellers  

**Panah Coin** is a Flutter-based mobile and web application (PWA) designed for gold sellers to manage financial transactions, monitor real-time coin prices, and operate with an advanced admin panel.  
This repository showcases my work as a **Flutter developer** on the Panah Coin project.  

---

## 📱 About the App  

Panah Coin is a specialized platform that enables gold sellers to:  

- Register, approve, and reject financial transactions  
- View and manage real-time gold coin prices  
- Use multi-level admin panels with custom roles  
- Apply two-factor authentication with OTP  
- Generate advanced reports with time filters  

A **Progressive Web App (PWA)** version is also available: [Panah Coin PWA](https://mahdijamebozorg.github.io/panah-coin/)  

---

## 📌 Key Highlights  

- Multi-level admin panel with user management  
- Real-time gold coin prices for various coin types  
- OTP-based two-factor authentication  
- Automatic price calculations for new transactions  
- Admin customization for prices and offsets  
- Global app settings and maintenance mode  
- Clean and maintainable Flutter codebase  

---

## 🛠️ Tech Stack & Dependencies  

Here’s a summary of the main technologies and packages used in the project:  

| Category | Package |
| ---------------- | ------------------------------- |
| **Framework** | [Flutter](https://flutter.dev/) |
| **State Management / Utilities** | [Get](https://pub.dev/packages/get), [Equatable](https://pub.dev/packages/equatable), [Logger](https://pub.dev/packages/logger), [Shared Preferences](https://pub.dev/packages/shared_preferences) |
| **HTTP Client** | [Dio](https://pub.dev/packages/dio), [Pretty Dio Logger](https://pub.dev/packages/pretty_dio_logger) |
| **UI Components** | [Flutter SVG](https://pub.dev/packages/flutter_svg), [Expandable](https://pub.dev/packages/expandable), [Skeletonizer](https://pub.dev/packages/skeletonizer), [Flutter Spinkit](https://pub.dev/packages/flutter_spinkit), [Lottie](https://pub.dev/packages/lottie), [Pinput](https://pub.dev/packages/pinput), [Fading Edge ScrollView](https://pub.dev/packages/fading_edge_scrollview) |
| **Localization** | [Flutter Localization](https://pub.dev/packages/flutter_localization), [Shamsi Date](https://pub.dev/packages/shamsi_date), [Persian DateTime Picker](https://pub.dev/packages/persian_datetime_picker), `flutter_localizations` (SDK) |
| **Platform / Auth** | [Local Auth](https://pub.dev/packages/local_auth), [Smart Auth](https://pub.dev/packages/smart_auth), [URL Launcher](https://pub.dev/packages/url_launcher), [Package Info Plus](https://pub.dev/packages/package_info_plus), [Path Provider](https://pub.dev/packages/path_provider) |
| **Development** | [Flutter Lints](https://pub.dev/packages/flutter_lints), [Flutter Launcher Icons](https://pub.dev/packages/flutter_launcher_icons), [Flutter Gen](https://pub.dev/packages/flutter_gen), [Build Runner](https://pub.dev/packages/build_runner), [Flutter Native Splash](https://pub.dev/packages/flutter_native_splash) |

**Backend:** Node.js  
**Database:** MongoDB  
**Authentication:** JWT + OTP  

---

## 🗂️ Project Structure  
lib/
├── components/ # Reusable UI components
├── models/ # Data models
├── pages/ # Application screens
├── services/ # Business logic services
├── states/ # State management
├── utils/ # Utility functions
├── main.dart # App entry point
└── routes.dart # App routing


---

## 📸 Screenshots  

The app includes multiple key screens for different functionalities:  

| Screen | Screenshot |
| ------ | ----------- |
| **Login** | <img src="./screenshots/login.jpg" alt="login" width="300"/> |
| **OTP Verification** | <img src="./screenshots/otp.jpg" alt="otp" width="300"/> |
| **User Dashboard** | <img src="./screenshots/home.jpg" alt="home" width="300"/> |
| **Transaction Management** | <img src="./screenshots/bills.jpg" alt="bills" width="300"/> |
| **New Transaction** | <img src="./screenshots/add_bill.jpg" alt="add-bill" width="300"/> |
| **Admin Panel** | <img src="./screenshots/admin_drawer.jpg" alt="admin" width="300"/> |
| **Users List** | <img src="./screenshots/users.jpg" alt="users" width="300"/> |
| **Customized Prices** | <img src="./screenshots/prices.jpg" alt="prices" width="300"/> |
| **Settings** | <img src="./screenshots/settings.jpg" alt="settings" width="300"/> |

---

## 📄 License  

This is a proprietary project. All rights reserved.  

---

## 🔄 Dev Setup  

For development:  

- Flutter SDK: 3.x  
- Dart SDK: 3.x  
- VS Code or Android Studio with Flutter plugins  

_For more information about the app’s features and development, please contact the development team._  
