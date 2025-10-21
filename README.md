# Flutter Basics 🚀

Welcome to **Flutter Basics** - your complete guide to learning Flutter development from scratch! This repository contains beginner-friendly projects, step-by-step tutorials, and hands-on examples to get you started with Flutter.

## 📱 What You'll Learn

- Flutter fundamentals and architecture
- Dart programming basics
- Building responsive UIs with widgets
- State management concepts
- Navigation between screens
- Working with APIs and data
- Best practices for Flutter development

## 🎯 Target Audience

This repository is designed for:
- Complete beginners to Flutter
- Developers new to mobile app development
- Anyone wanting to learn cross-platform development
- Students and workshop participants

## 📋 Prerequisites

Before starting, make sure you have:
- Basic programming knowledge (any language)
- A computer with internet connection
- Enthusiasm to learn! 🎉

## 🛠️ Installation & Setup

### 1. Install Flutter SDK

**Windows:**
```bash
# Download Flutter from https://flutter.dev/docs/get-started/install/windows
# Extract to C:\flutter
# Add C:\flutter\bin to PATH
```

**macOS:**
```bash
# Using Homebrew
brew install --cask flutter

# Or download from https://flutter.dev/docs/get-started/install/macos
```

**Linux (Ubuntu/Fedora):**
```bash
# Download Flutter
wget https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.24.3-stable.tar.xz
tar xf flutter_linux_3.24.3-stable.tar.xz

# Add to PATH
export PATH="$PATH:`pwd`/flutter/bin"
echo 'export PATH="$PATH:$HOME/flutter/bin"' >> ~/.bashrc
```

### 2. Install Dependencies

```bash
# Install Android Studio (recommended) or VS Code
# For Android development, install Android SDK

# Verify installation
flutter doctor
```

### 3. Clone This Repository

```bash
git clone https://github.com/DevJude254/Flutter_basics.git
cd flutter-basics
```

## 📚 Repository Structure

```
flutter-basics/
├── 01-hello-world/              # Your first Flutter app
├── 02-widgets-basics/           # Understanding widgets
├── 03-layouts/                  # Creating layouts
├── 04-stateful-widgets/         # Managing state
├── 05-navigation/               # Screen navigation
├── 06-forms-input/              # Forms and user input
├── 07-lists-cards/              # Lists and cards
├── 08-networking/               # API calls and HTTP
├── 09-local-storage/            # Data persistence
├── 10-final-project/            # Complete app project
├── exercises/                   # Practice exercises
├── resources/                   # Additional learning materials
└── README.md                    # This file
```

## 🎓 Learning Path

### Week 1: Flutter Fundamentals
- **Day 1-2:** [Hello World App](./01-hello-world/) - Your first Flutter app
- **Day 3-4:** [Widget Basics](./02-widgets-basics/) - Text, Container, Column, Row
- **Day 5-7:** [Layouts](./03-layouts/) - Building beautiful UIs

### Week 2: Interactive Apps
- **Day 1-3:** [Stateful Widgets](./04-stateful-widgets/) - Managing app state
- **Day 4-5:** [Navigation](./05-navigation/) - Moving between screens
- **Day 6-7:** [Forms & Input](./06-forms-input/) - User interactions

### Week 3: Advanced Features
- **Day 1-3:** [Lists & Cards](./07-lists-cards/) - Displaying data beautifully
- **Day 4-5:** [Networking](./08-networking/) - Fetching data from APIs
- **Day 6-7:** [Local Storage](./09-local-storage/) - Saving user data

### Week 4: Final Project
- **Day 1-7:** [Complete App](./10-final-project/) - Build a full-featured app

## 🚀 Quick Start Guide

### 1. Create Your First App
```bash
flutter create my_first_app
cd my_first_app
flutter run
```

### 2. Key Concepts to Understand

**Everything is a Widget:**
```dart
class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Text('Hello, Flutter Dev!'),
    );
  }
}
```

**Hot Reload:**
- Save your file (Ctrl+S / Cmd+S)
- See changes instantly in your app!

**Widget Tree:**
```
MaterialApp
└── Scaffold
    └── AppBar
    └── Body
        └── Column
            ├── Text
            └── Button
```

## 💡 Learning Tips

### For Beginners:
1. **Start Small:** Don't try to build complex apps immediately
2. **Experiment:** Change colors, text, and see what happens
3. **Use Hot Reload:** It's Flutter's superpower!
4. **Read Error Messages:** They're usually helpful
5. **Practice Daily:** Even 30 minutes makes a difference

### Debugging Tips:
```dart
// Use print statements to debug
print('Debug: Button pressed');

// Use debugPrint for better console output
debugPrint('Value of counter: $counter');

// Use assert for development-time checks
assert(counter >= 0, 'Counter should not be negative');
```

## 🛠️ Common Commands

```bash
# Create new Flutter project
flutter create project_name

# Run the app
flutter run

# Run on specific device
flutter run -d device_id

# Get list of connected devices
flutter devices

# Check for issues
flutter doctor

# Clean build files
flutter clean

# Get dependencies
flutter pub get

# Upgrade Flutter
flutter upgrade
```

## 🎯 Practice Exercises

Each folder contains:
- **README.md** - Step-by-step tutorial
- **starter/** - Starting code template  
- **solution/** - Complete working solution

### Beginner Challenges:
1. Change app colors and fonts
2. Add your photo to the app
3. Create a simple calculator
4. Build a personal profile page

### Intermediate Challenges:
1. Todo list app
2. Weather app with API
3. Image gallery
4. Shopping list with local storage

## 🌟 Project Showcase

If you complete the course you will build:

### 📱 Final Project: Personal Expense Tracker
- Add/delete expenses
- Categorize spending
- View spending charts
- Data persistence
- Beautiful, responsive UI

**Features you'll implement:**
- ✅ Custom widgets and themes
- ✅ Form validation
- ✅ Local data storage
- ✅ Charts and graphs
- ✅ Navigation drawer
- ✅ Dark/light mode toggle

## 📖 Additional Resources

### Official Documentation:
- [Flutter.dev](https://flutter.dev/) - Official website
- [Flutter Documentation](https://flutter.dev/docs)
- [Dart Language Guide](https://dart.dev/guides/language)

### Recommended Learning:
- [Flutter Widget Catalog](https://flutter.dev/docs/development/ui/widgets)
- [Flutter Codelabs](https://flutter.dev/docs/codelabs)
- [Flutter YouTube Channel](https://www.youtube.com/flutterdev)

### Community:
- [Flutter Community](https://flutter.dev/community)
- [Stack Overflow - Flutter](https://stackoverflow.com/questions/tagged/flutter)
- [Reddit - FlutterDev](https://www.reddit.com/r/FlutterDev/)

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch:** `git checkout -b feature/new-lesson`
3. **Commit changes:** `git commit -m 'Add new lesson on animations'`
4. **Push to branch:** `git push origin feature/new-lesson`
5. **Submit a Pull Request**

### Contribution Guidelines:
- Keep examples simple and well-commented
- Include step-by-step explanations
- Test all code before submitting
- Follow Flutter/Dart style guidelines

## 🐛 Issues & Support

Found a bug or have a question?
1. Check existing [Issues](https://github.com/DevJude254/Flutter-basics/issues)
2. Create a new issue with:
   - Clear description
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots (if applicable)



## 🎊 Getting Started Now!

Ready to dive in? Start with:
1. [Hello World App](./01-hello-world/) - Get your development environment working
2. Join our community discussions
3. Follow along with the weekly learning path

**Happy Flutter Learning! 🚀📱**

---

⭐ **Star this repository** if you find it helpful!
🍴 **Fork it** to customize for your learning journey!
📢 **Share it** with friends who want to learn Flutter!

*Made with ❤️ by Jude for the Flutter community*
