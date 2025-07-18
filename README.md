

# HealthIcons: Your Go-To Package for Open Source Health-Related Icons

[Pub.dev](https://pub.dev/packages/health_icons)
[Github](https://github.com/devnoaman/health_icons)

**HealthIcons** is a Flutter package that provides easy access to a comprehensive set of open-source health-related icons from [healthicons.org](https://healthicons.org/). Whether you're building a health application, a medical platform, or any project that needs clear and intuitive health-themed visuals, HealthIcons has you covered.

## ✨ Features

  * **Extensive Icon Set:** Access hundreds of carefully designed health icons covering various medical fields, conditions, and concepts.
  * **Easy Integration:** Seamlessly integrate icons into your Flutter application with a simple `Icon` widget.
  * **Customizable:** Just like standard Flutter `Icon` widgets, you can easily customize the size, color, and other properties of HealthIcons.
  * **Open Source:** Built upon the high-quality, openly licensed icons from healthicons.org, ensuring freedom of use and community support.

## 🚀 Getting Started

### Installation

Add `health_icons` to your `pubspec.yaml` file:

```yaml
dependencies:
  health_icons: ^latest_version # Replace with the latest version from pub.dev
```


Then, run `flutter pub get` in your terminal.

Or directly add latest version using terminal:
```sh
 flutter pub add health_icons
```
### Usage

Using HealthIcons is straightforward. Simply import the package and use the `HealthIcons` class to access the available icons:

```dart
import 'package:flutter/material.dart';
import 'package:health_icons/health_icons.dart'; // Import the package

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text('HealthIcons Demo'),
        ),
        body: Center(
          child: Column(
            mainAxisAlignment: MainAxisAlignment.center,
            children: [
              // Example 1: Basic Heart Icon
              Icon(
                HealthIcons.heart, //Pass IconData to Icon widget
                size: 60.0,
                color: Colors.red,
              ),
              SizedBox(height: 20),

              // Example 2: Medical Advice Icon
              Icon(
                HealthIcons.medicalAdvice, 
                size: 50.0,
                color: Colors.blue,
              ),
              SizedBox(height: 20),

               // Example 2: Blood type A+  Icon
              Icon(
                HealthIcons.bloodAP, 
                size: 50.0,
                color: Colors.blue,
              ),
              SizedBox(height: 20),


              // Example 4: Rx (Prescription) Icon
              Icon(
                HealthIcons.rx, 
                size: 45.0,
                color: Colors.green,
              ),
              SizedBox(height: 20),

              // You can find a comprehensive list of all available icons
              // by Browse the `lib/health_icons.dart` file in the package,
              // or by referring to the healthicons.org website for icon names.
              Text('Explore more health icons!'),
            ],
          ),
        ),
      ),
    );
  }
}
```

### Finding Icons

The best way to find the specific icon you need is to visit [healthicons.org](https://healthicons.org/). Each icon on their website corresponds directly to an icon in this package. For example, if you see an icon named "heart" on their site, you'll likely find it as `HealthIcons.heart` in this package. Many icons also have `_fill` and `_outline` variants. (currently this package only support filled)

## 🤝 Contributing

Contributions are welcome\! If you find a bug or have a suggestion for an improvement, please open an issue or submit a pull request on the [GitHub repository](https://www.google.com/search?q=https://github.com/YOUR_GITHUB_USERNAME/health_icons).

When contributing, please ensure your changes align with the project's goals and maintain code quality.

## 📄 License

This package is released under the [MIT License](https://opensource.org/licenses/MIT).
The icons themselves are sourced from [healthicons.org](https://healthicons.org/) and are licensed under the [CC0 License](https://creativecommons.org/publicdomain/zero/1.0/).

## 🙏 Acknowledgements

A huge thank you to the creators and contributors of [healthicons.org](https://healthicons.org/) for providing such a valuable resource of open-source health icons\!

-----