# Attribution and Acknowledgments

This file provides proper attribution and acknowledgment for all third-party libraries and components used in the Element Insight VS Code Extension.

## Third-Party Libraries

### Production Dependencies

#### open (^10.1.2)
- **Author**: Sindre Sorhus
- **License**: MIT
- **Homepage**: https://sindresorhus.com/open
- **Repository**: https://github.com/sindresorhus/open
- **Usage**: Opening browser URLs for sign-up links
- **Attribution**: This extension uses the open library to launch browser windows for user sign-up.

#### Playwright
- **Author**: Microsoft Corporation
- **License**: Apache 2.0
- **Homepage**: https://playwright.dev/
- **Repository**: https://github.com/microsoft/playwright
- **Usage**: Web page scanning, browser automation, code generation
- **Attribution**: This extension uses Playwright for web page scanning and generates Playwright code for users.

#### Python
- **Author**: Python Software Foundation
- **License**: PSF License
- **Homepage**: https://www.python.org/
- **Repository**: https://github.com/python/cpython
- **Usage**: XPath locator generation, enhanced accuracy
- **Attribution**: This extension recommends and supports Python for enhanced XPath locator generation.

#### lxml
- **Author**: Infrae and contributors
- **License**: BSD License
- **Homepage**: https://lxml.de/
- **Repository**: https://github.com/lxml/lxml
- **Usage**: XML/HTML parsing, XPath evaluation
- **Attribution**: This extension recommends lxml for improved XPath locator accuracy.

#### Node.js
- **Author**: Node.js contributors
- **License**: MIT
- **Homepage**: https://nodejs.org/
- **Repository**: https://github.com/nodejs/node
- **Usage**: Runtime environment, Playwright installation
- **Attribution**: This extension uses Node.js as the runtime environment and for installing Playwright.

#### npm
- **Author**: npm, Inc. and Contributors
- **License**: Artistic License 2.0
- **Homepage**: https://www.npmjs.com/
- **Repository**: https://github.com/npm/cli
- **Usage**: Package management, dependency installation
- **Attribution**: This extension uses npm to install and manage Playwright dependencies.

### Rust Binaries and Libraries

For a comprehensive list of all Rust crates and their licenses used in the `element-insight-binary` and `framework-export-binary` components, please refer to:

- [RUST_THIRD_PARTY_LICENSES.md](./RUST_THIRD_PARTY_LICENSES.md)

This document provides detailed attribution, license texts, and usage information for all Rust dependencies.

### Development Dependencies

#### TypeScript (^5.8.3)
- **Author**: Microsoft Corporation
- **License**: Apache 2.0
- **Homepage**: https://www.typescriptlang.org/
- **Repository**: https://github.com/microsoft/TypeScript
- **Usage**: Type checking, compilation, and development tooling
- **Attribution**: This extension is built using TypeScript for type safety and modern JavaScript development.

#### ESLint Ecosystem
- **Author**: OpenJS Foundation and contributors
- **License**: MIT
- **Homepage**: https://eslint.org/
- **Repository**: https://github.com/eslint/eslint
- **Usage**: Code linting, formatting, and quality assurance
- **Attribution**: This extension uses ESLint for maintaining code quality and consistency.

#### ESLint Ecosystem Dependencies
- **Author**: OpenJS Foundation and contributors
- **License**: MIT
- **Homepage**: https://eslint.org/
- **Repository**: https://github.com/eslint/eslint
- **Usage**: ESLint core engine, configuration, utilities, and plugins
- **Attribution**: This extension uses various ESLint ecosystem packages for comprehensive code analysis.

#### Webpack Ecosystem
- **Author**: webpack contributors
- **License**: MIT
- **Homepage**: https://webpack.js.org/
- **Repository**: https://github.com/webpack/webpack
- **Usage**: Build tool, bundling, and asset management
- **Attribution**: This extension uses Webpack for building and bundling the extension code.

#### Webpack Ecosystem Dependencies
- **Author**: webpack contributors
- **License**: MIT
- **Homepage**: https://webpack.js.org/
- **Repository**: https://github.com/webpack/webpack
- **Usage**: Webpack CLI, source maps, file watching, module resolution
- **Attribution**: This extension uses various Webpack ecosystem packages for comprehensive build tooling.

#### VS Code Extension API Types
- **Author**: Microsoft Corporation
- **License**: MIT
- **Homepage**: https://code.visualstudio.com/api
- **Repository**: https://github.com/microsoft/vscode
- **Usage**: VS Code extension development and API integration
- **Attribution**: This extension uses the official VS Code extension API types for proper integration.

#### TypeScript ESLint Dependencies
- **Author**: TypeScript ESLint contributors
- **License**: MIT
- **Homepage**: https://typescript-eslint.io/
- **Repository**: https://github.com/typescript-eslint/typescript-eslint
- **Usage**: TypeScript-specific ESLint rules and parsing
- **Attribution**: This extension uses TypeScript ESLint packages for TypeScript code analysis.

## Built-in Node.js Modules

The following Node.js built-in modules are used in this extension:

- **crypto** - Cryptographic functionality for binary integrity verification
- **child_process** - Process spawning and management for binary execution
- **path** - File path utilities for cross-platform compatibility
- **fs** - File system operations for binary management
- **os** - Operating system utilities for platform detection
- **util** - Utility functions for promise handling

These modules are part of Node.js and are licensed under the MIT License (see Node.js attribution above).

## Additional Dependencies

#### Utility Dependencies
- **@humanfs/* packages** - **Author**: Human contributors - **License**: MIT - **Usage**: Human-friendly file system utilities
- **@jridgewell/* packages** - **Author**: Justin Ridgewell - **License**: MIT - **Usage**: Source map and trace utilities
- **@nodelib/* packages** - **Author**: Denis Malinochkin - **License**: MIT - **Usage**: File system utilities
- **Various utility packages** - **Author**: Various contributors - **License**: MIT - **Usage**: Development and build utilities
- **Attribution**: These packages provide essential utilities for development, building, and runtime operations.

## Additional Acknowledgments

### Open Source Community
- **Contributors**: All contributors to the open source libraries used in this extension
- **Maintainers**: The dedicated maintainers who keep these libraries updated and secure
- **Documentation**: Community members who contribute to documentation and examples

### Development Tools
- **Node.js**: Runtime environment for the extension
- **npm**: Package manager for dependency management
- **Git**: Version control system

## License Compatibility

All third-party libraries used in this extension are compatible with the extension's MIT License with Krisu.ai Attribution:

- **MIT Licenses**: Fully compatible with your custom license
- **Apache 2.0 Licenses**: More permissive than MIT, fully compatible
- **PSF License (Python)**: Compatible with MIT, allows commercial use
- **BSD License (lxml)**: Compatible with MIT, allows commercial use
- **Artistic License 2.0 (npm)**: Compatible with MIT, allows commercial use

## Compliance Verification

This attribution file ensures compliance with:

- ✅ **MIT License Requirements**: Proper attribution for MIT-licensed libraries
- ✅ **Apache 2.0 Requirements**: Full license text and copyright notices
- ✅ **Copyright Requirements**: All copyright holders properly acknowledged
- ✅ **Usage Documentation**: Clear description of how each library is used
- ✅ **Repository Links**: Direct links to source code and documentation

## How to Use This Information

### For Users
- **Transparency**: Users can see exactly what third-party code is included
- **Licensing**: Users understand the licensing terms of all components
- **Attribution**: Proper credit given to all library authors

### For Developers
- **Compliance**: Ensures legal compliance with all licenses
- **Maintenance**: Helps track dependencies and their requirements
- **Updates**: Guides dependency updates and license compliance

### For Distribution
- **Marketplace**: Meets VS Code Marketplace requirements
- **Legal**: Provides legal protection and compliance
- **Professional**: Demonstrates professional development practices

## Maintenance

This file should be updated when:

- New dependencies are added
- Dependencies are updated
- License information changes
- New usage patterns are implemented

## Contact

For questions about third-party library usage or licensing:

- **Email**: support@krisu.ai
- **Website**: https://krisu.ai
- **Documentation**: https://krisu.ai/docs

---

**Last Updated**: January 2025  
**Version**: 1.0  
**Maintained By**: Krisu.ai Development Team
