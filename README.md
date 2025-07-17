<div align="center">
<h1>Flutter Internship Test Application</h1>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart">
  <img src="https://img.shields.io/badge/API-REST-green?style=for-the-badge" alt="REST API">
</div>

<br>
This project was developed as part of an internship test for the Mobile Developer role at PT Suitmedia Kreasi Indonesia, specifically for the "Magang Berdampak" program. It demonstrates my ability to understand and implement the given requirements into mobile application development code.

## 🔗 Links

<table>
  <tr>
    <td><strong>Demo Video</strong></td>
    <td><a href="https://drive.google.com/drive/folders/1uWlhgxti2qlCo3AdH7p2zKBXRgMP4lvx">Application Demo</a></td>
  </tr>
</table>

## ⚡ Features

<details>
<summary><strong>First Screen</strong></summary>

- **User Input**: Two input fields for entering Name and Sentence
- **Palindrome Checker**: Real-time validation with "Check" button
- **Smart Validation**: Displays "isPalindrome" or "not palindrome" via AlertDialog
- **Navigation Guard**: Requires Name field to be filled before proceeding
- **Profile Image**: Gallery image selection functionality

</details>

<details>
<summary><strong>Second Screen</strong></summary>

- **Welcome Interface**: Clean welcome message display
- **Dynamic User Management**: 
  - Shows name from First Screen
  - Updates "Selected User Name" dynamically

</details>

<details>
<summary><strong>Third Screen</strong></summary>

- **User Directory**: Complete user list from reqres.in API
- **Rich User Cards**: Avatar, full name, and email display
- **Infinite Scrolling**: Automatic pagination on scroll
- **Pull-to-Refresh**: Intuitive refresh mechanism
- **Error Handling**: Empty state with retry functionality
- **User Selection**: Tap-to-select with data passing

</details>

## Project Structure

```
lib/
├── constants/
│   └── app_routes.dart       # Named routes configuration
├── models/
│   └── user.dart             # User data model
├── screens/
│   ├── first_screen.dart     # Input & palindrome checker
│   ├── second_screen.dart    # Welcome & user display
│   └── third_screen.dart     # User list & selection
├── services/
│   └── api_services.dart     # API communication layer
└── main.dart                 # Application entry point
```

## 🚀 Getting Started

> **Prerequisites**
> - Flutter SDK (latest stable version)
> - Dart SDK
> - IDE: VS Code or Android Studio
> - Device/Emulator for testing

### Installation

**Step 1:** Clone the repository
```bash
git clone <repository_url>
cd <repository_name>
```

**Step 2:** Install dependencies
```bash
flutter pub get
```

**Step 3:** Run the application
```bash
flutter run
```

## 🌐 API Integration

> **Base URL:** `https://reqres.in/api`

| Endpoint | Description | Parameters |
|----------|-------------|------------|
| `/users` | User data retrieval | `page`, `per_page` |

## 🛠️ Technical Implementation

### Core Components

| Component | Responsibility |
|-----------|---------------|
| `main.dart` | Application setup and routing configuration |
| `first_screen.dart` | Input validation, palindrome logic, image selection |
| `second_screen.dart` | State management and user data display |
| `third_screen.dart` | API integration, infinite scroll, pull-to-refresh |
| `api_services.dart` | HTTP request handling and error management |
| `user.dart` | Data modeling with JSON serialization |
| `app_routes.dart` | Centralized navigation management |

### Key Dependencies

```yaml
dependencies:
  assets: ^0.0.2
  cupertino_icons: ^1.0.8
  flutter:
    sdk: flutter
  path_provider: ^2.0.10
  sqflite: ^2.0.0+4
  keyboard_avoider: ^0.2.0
  shared_preferences: ^2.5.3
  path: ^1.9.1
  image_picker: ^1.1.2
```
<hr style="border: 0.1px solid #ddd;">

<div align="center">
    <br><br>
  
  <strong>Next Mobile Developer</strong><br>
  Created as part of Mobile Developer internship assessment by PT Suitmedia Kreasi Indonesia.
  
  <br><br>
  
  <em>For more projects and detailed information, visit my <a href="https://spectrum-resolution-3e6.notion.site/Digital-Portfolio-21fd805f6a4a806697b8fa3f1b17b39b">Digital Portfolio</a></em>
</div>
