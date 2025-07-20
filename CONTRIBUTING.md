# Contributing to RecurDate

Thank you for your interest in contributing to RecurDate! This document provides guidelines and information for contributors.

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn
- Git

### Setup

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/your-username/recurdate.git
   cd recurdate
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Run tests to ensure everything works:
   ```bash
   npm test
   ```

## 🔧 Development Workflow

### Code Style

- **TypeScript**: All code must be properly typed
- **ESLint**: Follow existing linting rules
- **Prettier**: Code is automatically formatted
- **Naming**: Use descriptive, camelCase variable names

### Testing

- Write tests for new features
- Ensure all existing tests pass
- Aim for good test coverage
- Use descriptive test names

```bash
# Run tests
npm test

# Run tests in watch mode
npm run test:watch

# Run specific test file
npm test recurring-dates.test.ts
```

### Commit Messages

Use conventional commit format:

```
feat: add new recurring pattern support
fix: resolve calendar navigation bug
docs: update API documentation
test: add integration tests for date picker
```

## 📝 Pull Request Process

1. Create a feature branch from `main`
2. Make your changes
3. Add/update tests
4. Ensure all tests pass
5. Update documentation if needed
6. Submit a pull request

### PR Requirements

- [ ] Tests pass (`npm test`)
- [ ] TypeScript compiles without errors (`npm run typecheck`)
- [ ] Code follows style guidelines
- [ ] Documentation updated (if needed)
- [ ] Descriptive PR title and description

## 🐛 Bug Reports

Please use the GitHub issue template and include:

- Description of the bug
- Steps to reproduce
- Expected behavior
- Screenshots (if applicable)
- Environment details

## 💡 Feature Requests

For new features:

- Check existing issues first
- Provide clear use case
- Consider implementation complexity
- Discuss with maintainers

## 📁 Project Structure

```
recurdate/
├── client/                 # React frontend
│   ├── components/         # React components
│   ├── lib/               # Utilities and stores
│   └── pages/             # Page components
├── shared/                # Shared logic
├── server/                # Express backend
└── tests/                 # Test files
```

## 🔍 Areas for Contribution

- **New Recurrence Patterns**: Add support for complex patterns
- **UI/UX Improvements**: Enhance animations and interactions
- **Performance**: Optimize rendering and calculations
- **Accessibility**: Improve keyboard navigation and screen readers
- **Documentation**: Improve guides and examples
- **Testing**: Add more comprehensive tests

## 📞 Questions?

- Open a GitHub Discussion
- Join our Discord (link)
- Email: contribute@recurdate.com

Thank you for contributing! 🎉
