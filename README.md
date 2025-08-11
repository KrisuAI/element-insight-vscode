# Element Insight VS Code Extension

**AI-powered web element inspector and test code generator for Playwright, Selenium, and more. Instantly scan web pages, extract robust locators, and export ready-to-use automation code.**

[![VS Code Marketplace](https://img.shields.io/badge/VS%20Code-Marketplace-blue?logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=krisu.element-insight)
[![License](https://img.shields.io/badge/License-MIT%20with%20Attribution-green.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-0.0.1-blue.svg)](CHANGELOG.md)

---

## 🚀 Features

- **One-click web page scanning**: Instantly analyze any web page for actionable elements
- **Robust locator generation**: Get the most stable, unique locators (id, data-* attributes, text, XPath, CSS, and more)
- **Framework-aware**: Export code for Playwright, Selenium, Cypress, Robot Framework, and more
- **AI-powered suggestions**: Self-healing and dynamic locator strategies for resilient test automation
- **Export to code**: Generate ready-to-use test code in multiple languages (Python, Java, C#, JS, TS)
- **VS Code integration**: Seamless sidebar UI, keyboard shortcuts, and quick access

---

## 🧑‍💻 Getting Started

### 1. **Sign up on the website**:  
   [Create your account here](https://krisu.ai/auth) before using the extension.

### 2. **Install the extension**:  
   Find "Element Insight" in the VS Code Marketplace or [click here](https://marketplace.visualstudio.com/items?itemName=krisu.element-insight).

### 3. **Sign in with Google**:  
   Use the same account you registered with.

### 4. **Scan and export**:  
   Enter a URL, select tags, and generate locators or export code.

---

## 🏆 Why Element Insight?

- **No more manual locator hunting**: Let AI do the heavy lifting
- **Unique, stable locators**: Reduce test flakiness and maintenance
- **Supports all major frameworks**: Playwright, Selenium, Cypress, Robot Framework
- **Fast onboarding**: Get started in minutes

---

## 📸 Screenshots

> *(Add screenshots or GIFs here showing the extension in action!)*

---

## 🔧 Usage Examples

### Element Locator Output
```json
{
  "element": {
    "tag": "input",
    "type": "text",
    "id": "username",
    "locators": {
      "id": "#username",
      "name": "[name='username']",
      "xpath": "//input[@id='username']",
      "css": "input#username",
      "best_locator": "#username"
    }
  }
}
```

### Generated Playwright Code (Python)
```python
from playwright.sync_api import Page

class LoginPage:
    def __init__(self, page: Page):
        self.page = page
    
    def fill_username(self, username: str):
        self.page.fill("#username", username)
    
    def fill_password(self, password: str):
        self.page.fill("#password", password)
    
    def click_login(self):
        self.page.click("#login-button")
```

---

## ❓ FAQ & Troubleshooting

- **Why do I need to sign up first?**  
  To ensure your account is registered in our backend for secure access.

- **What if I see "You need to sign up first"?**  
  Go to the website and complete the sign-up process, then try again.

- **How do I report issues or request features?**  
  Contact us at support@krisu.ai for issues or feature requests.

- **If you are logged out immediately after signing in, it means your account does not exist in our backend. Please sign up first.**

---

## 🔒 Privacy & Security

- No sensitive data is collected
- See our [privacy policy](https://krisu.ai/privacy) for details

---

## 📝 Changelog

See [CHANGELOG.md](CHANGELOG.md) for release notes.

---

## 💡 Pro Tips

- Use keyboard shortcut `Ctrl+Alt+E` (or `Cmd+Alt+E` on Mac) to open the extension quickly
- Try different frameworks and locator strategies for best results

---

## 📄 Licensing

This extension is licensed under **MIT License with Krisu.ai Attribution**.

### Third-Party Libraries

This extension includes third-party libraries that are subject to their respective licenses:

- **Firebase** - Apache 2.0 License (Google LLC)
- **node-fetch** - MIT License (David Halls)
- **open** - MIT License (Sindre Sorhus)
- **TypeScript** - Apache 2.0 License (Microsoft Corporation)
- **ESLint** - MIT License (OpenJS Foundation)
- **Webpack** - MIT License (webpack contributors)

For complete license information and attribution, see:
- [LICENSE](LICENSE) - Main license file
- [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md) - Complete third-party licenses
- [ATTRIBUTION.md](ATTRIBUTION.md) - Detailed attribution information

All third-party libraries are compatible with our license and properly attributed.

---

## 🌟 Support & Community

- **Website**: [https://krisu.ai](https://krisu.ai)
- **Documentation**: [https://krisu.ai/docs](https://krisu.ai/docs)
- **Support**: [support@krisu.ai](mailto:support@krisu.ai)
- **Issues**: Report bugs and feature requests via our support portal

---

**Ready to supercharge your web test automation? Install Element Insight today!**

*Built with ❤️ by the Krisu.ai team*
