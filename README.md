# Namer App

A Flutter application that demonstrates basic app functionality using English words and state management.

## Prerequisites

Before you begin, ensure you have the following installed:

- **Flutter SDK** (version 3.1.1 or later)
- **Dart SDK** (comes with Flutter)
- **Android Studio** or **VS Code** with Flutter extensions
- **Xcode** (for iOS development, macOS only)

## Project Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/namer_app.git
cd namer_app
```

### 2. Install Dependencies

```bash
flutter pub get
```

### 3. Running the Project

#### For iOS (macOS only):
```bash
flutter run -d ios
```

#### For Android:
```bash
flutter run -d android
```

#### For Web:
```bash
flutter run -d chrome
```

## Project Configuration

This project uses the following key dependencies:

- **english_words**: For generating random word pairs
- **provider**: For state management

## Development

### Adding New Dependencies

To add new dependencies:

1. Edit `pubspec.yaml` to include the new dependency.
2. Run:
   ```bash
   flutter pub get
   ```

## Troubleshooting

If you encounter any issues, try the following steps:

1. Ensure Flutter SDK is up to date:
   ```bash
   flutter upgrade
   ```
2. Resolve dependencies:
   ```bash
   flutter pub get
   ```
3. Check for any configuration issues:
   ```bash
   flutter doctor
   ```

