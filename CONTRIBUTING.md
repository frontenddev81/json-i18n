# Contributing to JSON i18n Translator

Thank you for your interest in contributing to JSON i18n Translator! This document provides guidelines and instructions for contributing.

## 🤝 Code of Conduct

This project adheres to a code of conduct that all contributors must follow. Please be respectful, professional, and considerate in all interactions.

## 📋 Getting Started

1. **Fork the repository**
   - Click the "Fork" button on GitHub
   - Clone your fork: `git clone https://github.com/YOUR_USERNAME/json-i18n.git`

2. **Set up the development environment**
   ```bash
   cd json-i18n
   npm install
   ```

3. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make your changes and test them**
   ```bash
   npm start  # Run the development server
   npm test   # Run tests
   npm lint   # Check code quality
   ```

5. **Commit your changes**
   - Follow conventional commit messages
   - Example: `feat: add support for Russian language`
   - Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

6. **Push and create a Pull Request**
   ```bash
   git push origin feature/your-feature-name
   ```
   - Then create a PR on GitHub

## 🎯 Contribution Guidelines

### Adding New Languages

To add support for a new language:

1. Update `availableLanguages` array in `src/app/home/home.page.ts`
2. Add the language with proper name and code
3. Test the translation with a sample JSON file
4. Update the README.md with the new language

### Bug Fixes

- Provide a clear description of the bug
- Include steps to reproduce
- Add tests if possible
- Ensure all existing tests still pass

### Feature Development

- Discuss major features in an issue first
- Follow the existing code style
- Write tests for new features
- Update documentation as needed

## 📝 Code Style

- Use TypeScript best practices
- Follow Angular style guide
- Use ESLint for code quality
- Write self-documenting code with clear variable names

## ✅ Testing

- Write unit tests for new features
- Test translations with various JSON structures
- Test on different browsers and devices
- Ensure no console errors or warnings

## 📚 Documentation

- Update README.md for user-facing changes
- Add JSDoc comments for complex functions
- Update inline comments where necessary

## 🔍 Review Process

1. All PRs require at least one approval
2. CI/CD checks must pass
3. Code review feedback must be addressed
4. Maintainers will merge approved PRs

## 🙏 Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes
- GitHub contributors page

Thank you for contributing to JSON i18n Translator! 🎉

