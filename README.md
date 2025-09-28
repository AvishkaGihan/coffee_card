# Coffee Card

A Flutter application that allows users to customize their coffee preferences by selecting the strength and amount of sugars.

## Features

- **Strength Selection**: Choose your coffee strength from 1 to 5 coffee beans.
- **Sugars Selection**: Select the number of sugar cubes from 0 to 5.
- **Interactive UI**: Simple and intuitive interface with buttons to adjust preferences.
- **Visual Feedback**: Displays coffee beans and sugar cubes based on selections.

## Screenshots

![Coffee Card App](assets/img/coffee_bg.jpg)

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install) (version 3.9.2 or higher)
- Dart SDK (included with Flutter)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/coffee_card.git
   cd coffee_card
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Run the app:
   ```bash
   flutter run
   ```

### Building for Production

To build an APK for Android:

```bash
flutter build apk --release
```

To build for iOS (on macOS):

```bash
flutter build ios --release
```

## Project Structure

- `lib/`: Contains the Dart source code
  - `main.dart`: Entry point of the application
  - `home.dart`: Main home screen widget
  - `coffee_prefs.dart`: Widget for coffee preferences selection
  - `styled_body_text.dart`: Custom styled text widget
  - `styled_button.dart`: Custom styled button widget
- `assets/img/`: Image assets (coffee beans, background, sugar cubes)
- `android/`, `ios/`, `web/`, `windows/`, `linux/`, `macos/`: Platform-specific code

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
