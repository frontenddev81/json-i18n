# JSON i18n Translator 🌍

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Angular](https://img.shields.io/badge/Angular-20.0.0-red.svg)](https://angular.io/)
[![Ionic](https://img.shields.io/badge/Ionic-8.0.0-blue.svg)](https://ionicframework.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8.0-blue.svg)](https://www.typescriptlang.org/)

A modern, open-source web application for translating JSON i18n files and plain text into multiple languages. Built with Angular and Ionic, this tool helps developers quickly internationalize their applications by translating language files across 22+ supported languages.

## ✨ Features

- **JSON File Translation**: Translate entire JSON i18n files while preserving structure
- **Plain Text Translation**: Translate individual text strings
- **Multi-Language Support**: Translate to 22+ languages including:
  - Arabic (ar), Bengali (bn), Chinese Simplified (zh-CN), Chinese Traditional (zh-TW)
  - English (en), French (fr), German (de), Hindi (hi), Indonesian (id)
  - Italian (it), Japanese (ja), Korean (ko), Malayalam (ml), Marathi (mr)
  - Portuguese (pt), Russian (ru), Spanish (es), Tamil (ta), Telugu (te)
  - Turkish (tr), Urdu (ur), Vietnamese (vi)
- **Batch Translation**: Translate multiple files/languages simultaneously
- **Download Translations**: Export translated JSON files for each language
- **Modern UI**: Beautiful, responsive interface built with Ionic components
- **Cross-Platform**: Web-ready, can be built for iOS, Android, and Desktop with Capacitor

## 🚀 Quick Start

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/frontenddev81/json-i18n.git
   cd json-i18n
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

4. **Open your browser**
   Navigate to `http://localhost:4200`

### Building for Production

```bash
npm run build
# or
yarn build
```

The production build will be in the `www/` directory.

## 📖 Usage

### Translating JSON i18n Files

1. **Upload or Paste JSON**
   - Click "Upload File" to select a JSON file
   - Or paste your JSON directly into the text area
   - Example JSON structure:
     ```json
     {
       "welcome": "Welcome to our app",
       "login": "Login",
       "logout": "Logout",
       "settings": "Settings"
     }
     ```

2. **Select Target Languages**
   - Click "Select Languages" button
   - Choose one or multiple target languages from the modal
   - Selected languages will appear as chips

3. **Translate**
   - Translations will automatically start when you select languages
   - Or click "Translate" if you need to re-translate

4. **Download Results**
   - Expand each language accordion to preview translations
   - Click the download icon to save individual language files
   - Files will be named using the language code (e.g., `fr.json`, `es.json`)

### Translating Plain Text

1. Switch to "Text" mode using the segment buttons
2. Enter your English text
3. Select target languages
4. View and download translations

## 🏗️ Project Structure

```
json-i18n/
├── src/
│   ├── app/
│   │   ├── home/
│   │   │   ├── home.page.ts          # Main translation logic
│   │   │   ├── home.page.html        # Main UI
│   │   │   └── home.page.scss        # Styles
│   │   ├── language-select/
│   │   │   ├── language-select.component.ts
│   │   │   ├── language-select.component.html
│   │   │   └── language-select.component.scss
│   │   ├── app-routing.module.ts
│   │   └── app.module.ts
│   ├── assets/
│   ├── environments/
│   ├── theme/
│   └── index.html
├── angular.json
├── package.json
├── capacitor.config.ts
├── ionic.config.json
└── README.md
```

## 🛠️ Technology Stack

- **Frontend Framework**: Angular 20.0.0
- **UI Library**: Ionic 8.0.0
- **Language**: TypeScript 5.8.0
- **Build Tool**: Angular CLI
- **Mobile Framework**: Capacitor 7.4.2
- **Translation API**: MyMemory Translation API
- **Styling**: SCSS
- **Testing**: Jasmine & Karma

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. Here are some ways you can contribute:

- 🌐 Add support for additional languages
- 🐛 Report and fix bugs
- ✨ Suggest and implement new features
- 📝 Improve documentation
- 🎨 Enhance the UI/UX
- ⚡ Optimize performance

Please read our [Contributing Guidelines](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Angular](https://angular.io/) - Frontend framework
- [Ionic](https://ionicframework.com/) - UI component library
- [MyMemory Translation API](https://mymemory.translated.net/) - Translation service
- [Capacitor](https://capacitorjs.com/) - Cross-platform app framework

## 📧 Support

If you have any questions, issues, or feature requests, please:
- Open an issue on GitHub
- Contact the maintainers

## 🌟 Star History

If you find this project useful, please consider giving it a ⭐ on GitHub!

## 📊 Roadmap

- [ ] Support for nested JSON objects
- [ ] Batch file upload
- [ ] Translation history
- [ ] Custom API key support
- [ ] Offline translation support
- [ ] Translation quality indicators
- [ ] Integration with popular i18n libraries
- [ ] Progressive Web App (PWA) support

## 🔒 Privacy

This application uses the MyMemory Translation API. All translations are processed through their service. Please review their privacy policy if you have concerns about data handling.

---

Made with ❤️ by frontenddev81
