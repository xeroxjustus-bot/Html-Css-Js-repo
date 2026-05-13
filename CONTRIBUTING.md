# Contributing to Html-Css-Js-repo

Thank you for your interest in contributing! We welcome contributions of all kinds - bug fixes, new features, improvements, and documentation updates.

## 🚀 Getting Started

### Prerequisites
- Git installed on your machine
- A GitHub account
- Basic knowledge of HTML, CSS, and/or JavaScript

### Fork & Clone
1. **Fork** this repository (click the fork button)
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Html-Css-Js-repo.git
   cd Html-Css-Js-repo
   ```
3. **Add upstream** remote:
   ```bash
   git remote add upstream https://github.com/xeroxjustus-bot/Html-Css-Js-repo.git
   ```

## 💻 Making Changes

### Create a Feature Branch
```bash
git checkout -b feature/YourFeatureName
# or for bug fixes:
git checkout -b bugfix/BugName
```

### Code Style Guidelines

#### **HTML**
- Use semantic HTML5 tags
- Use proper indentation (2 spaces)
- Add comments for complex sections
- Ensure accessibility (alt text for images, proper heading hierarchy)

#### **CSS**
- Use meaningful class names (e.g., `.btn-primary` not `.b1`)
- Follow BEM naming convention when possible
- Comment complex selectors
- Keep CSS organized and DRY
- Use consistent indentation (2 spaces)

#### **JavaScript**
- Use `const` and `let` instead of `var`
- Use meaningful variable names
- Add comments for complex logic
- Follow ES6+ standards
- Keep functions small and focused
- Use `camelCase` for variables and functions
- Use `PascalCase` for classes

### Example:
```javascript
// ✅ Good
const calculateTotal = (items) => {
  return items.reduce((sum, item) => sum + item.price, 0);
};

// ❌ Avoid
var calc=(i)=>{return i.reduce((s,x)=>s+x.price,0)};
```

## 📋 Testing Your Changes

Before submitting a PR:
- [ ] Test in multiple browsers (Chrome, Firefox, Safari, Edge)
- [ ] Test on mobile devices (use browser DevTools)
- [ ] Verify all interactive features work correctly
- [ ] Check console for errors or warnings
- [ ] Ensure responsive design works

### Local Testing
```bash
# Option 1: Open directly in browser
open Chatbot.html  # macOS
start Chatbot.html # Windows
# or double-click the HTML file

# Option 2: Use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📝 Commit Messages

Use descriptive commit messages with emoji prefixes:

- ✨ **`:sparkles:`** - New feature
- 🐛 **`:bug:`** - Bug fix
- 📚 **`:books:`** - Documentation
- 🎨 **`:art:`** - Code style/formatting
- ⚡ **`:zap:`** - Performance improvement
- ♻️ **`:recycle:`** - Refactoring
- 🔧 **`:wrench:`** - Configuration changes
- ✅ **`:heavy_check_mark:`** - Tests

### Example Commits
```bash
git commit -m "✨ Add dark mode toggle to chatbot"
git commit -m "🐛 Fix responsive layout on mobile"
git commit -m "📚 Update README with new features"
```

## 🔄 Submitting a Pull Request

1. **Keep it focused** - One feature or bug fix per PR
2. **Update your branch**:
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```
3. **Push your changes**:
   ```bash
   git push origin feature/YourFeatureName
   ```
4. **Create a Pull Request** on GitHub with:
   - Clear title describing the change
   - Description of what was changed and why
   - Reference any related issues (e.g., `Fixes #123`)
   - Screenshots for UI changes

### PR Title Format
```
[TYPE] Brief description

Examples:
- [Feature] Add dark mode to chatbot
- [Fix] Correct mobile responsive layout
- [Docs] Update installation instructions
```

## 📋 PR Checklist

Before submitting, ensure:
- [ ] Code follows style guidelines
- [ ] Changes are tested
- [ ] New features have comments
- [ ] README updated if needed
- [ ] Commit messages are clear
- [ ] No merge conflicts
- [ ] Code works on multiple browsers

## 🐛 Reporting Bugs

Found a bug? [Open an issue](https://github.com/xeroxjustus-bot/Html-Css-Js-repo/issues) with:
- Clear title and description
- Steps to reproduce
- Expected vs actual behavior
- Browser and OS information
- Screenshots if applicable

## 💡 Suggesting Features

Have an idea? [Start a discussion](https://github.com/xeroxjustus-bot/Html-Css-Js-repo/discussions) or open an issue with:
- Clear description of the feature
- Why it would be useful
- Examples or mockups if possible

## 📖 Documentation

Help us improve documentation by:
- Fixing typos in README or code comments
- Adding examples to existing documentation
- Clarifying confusing sections
- Adding new guides or tutorials

## 🤝 Community Guidelines

- Be respectful and inclusive
- Provide constructive feedback
- Help others learn and grow
- Follow our [Code of Conduct](CODE_OF_CONDUCT.md)

## ❓ Questions?

- 📌 Check existing [Issues](https://github.com/xeroxjustus-bot/Html-Css-Js-repo/issues)
- 💬 Start a [Discussion](https://github.com/xeroxjustus-bot/Html-Css-Js-repo/discussions)
- 📖 Read the [Wiki](https://github.com/xeroxjustus-bot/Html-Css-Js-repo/wiki)

## 🙏 Thank You!

Your contributions make this project better for everyone. We appreciate your effort and look forward to working with you!

---

**Happy Contributing! 🎉**

*Made with ❤️ by the Html-Css-Js-repo community*
