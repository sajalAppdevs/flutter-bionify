# Bionify - Enhanced Reading Experience

[![Flutter](https://img.shields.io/badge/Flutter-3.0+-02569B?logo=flutter)](https://flutter.dev)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/Solido/flutter-bionify)

Bionify is an innovative Flutter package that enhances reading comfort by adding bold prefixes to text, making fast reading more comfortable and efficient. By strategically emphasizing the beginning of words, it helps guide your eyes naturally through the text.

## Features

- **Enhanced Reading Experience**: Automatically adds bold prefixes to text for better readability
- **Eye Guidance Optimization**: Makes fast reading more comfortable by providing visual anchors
- **Cross-Platform Support**: Works seamlessly across multiple platforms:
  - Android
  - iOS
  - Linux
  - macOS
  - Web
  - Windows

## Installation

Add Bionify to your project by including it in your `pubspec.yaml`:

```yaml
dependencies:
  bionify: ^0.0.1
```

Or install via command line:

```bash
flutter pub add bionify
```

## Usage

Implement Bionify in your Flutter application to enhance text readability:

```dart
import 'package:bionify/bionify.dart';

// Example usage in a widget
Text(
  'Your text here',
  style: BionifyTextStyle(),
)
```

## Screenshots

Check out the visual comparison between regular text and Bionify-enhanced text in the [example screenshots](example/screenshots/comparaison.png).

## Requirements

- Flutter SDK: >=3.0.0 <4.0.0
- Material Design enabled in your Flutter project

## Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

Please ensure you follow the project's contribution guidelines when submitting changes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## About

Bionify is maintained by the Flutter community. For more information, visit our [GitHub repository](https://github.com/Solido/flutter-bionify).