# Flutter Web App

A Flutter web application with automated GitHub Actions deployment.

## Features

- 🚀 Flutter web application
- 🔄 Automated GitHub Actions CI/CD
- 🌐 GitHub Pages deployment
- 📱 Responsive design
- 🎨 Material Design 3

## Getting Started

### Prerequisites

- Flutter SDK (3.24.0 or later)
- Web browser

### Installation

1. Clone this repository:
```bash
git clone https://github.com/anernahi20-rgb/flutter-web-app.git
cd flutter-web-app
```

2. Get dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run -d chrome
```

### Building for Web

```bash
flutter build web --release
```

## Deployment

This project is automatically deployed to GitHub Pages when you push to the main branch. The GitHub Action workflow:

1. Sets up Flutter environment
2. Gets dependencies
3. Runs code analysis
4. Runs tests
5. Builds the web app
6. Deploys to GitHub Pages

## Live Demo

Once deployed, your app will be available at:
https://anernahi20-rgb.github.io/flutter-web-app/

## Project Structure

```
flutter-web-app/
├── lib/
│   └── main.dart          # Main application code
├── web/
│   ├── index.html         # Web entry point
│   └── manifest.json      # Web app manifest
├── .github/
│   └── workflows/
│       └── flutter-web.yml # GitHub Actions workflow
├── pubspec.yaml           # Flutter dependencies
└── README.md             # This file
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).