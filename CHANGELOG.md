# Change Log

All notable changes to the "ElementInsight" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [0.0.1] - 2025-01-XX

### Added
- Initial release of ElementInsight VS Code extension
- **Element Insight feature** with Rust binary integration for web page scanning
- **Framework Export functionality** for Playwright and Selenium with multiple languages
- **Google OAuth authentication** integration with Firebase
- **Comprehensive tag selection system** with 9 categories and 100+ HTML elements
- **Modern sidebar UI** with VS Code theme integration
- **Keyboard shortcuts** (`Ctrl+Alt+E`) for quick access
- **Activity Bar integration** with dedicated sidebar panel
- **Automatic dependency management** for Playwright, Python, and lxml
- **Binary integrity verification** with SHA-256 hashing
- **Error handling and sanitization** for secure operation
- **Session management** with automatic token refresh and logout

### Framework Support
- **Playwright**: Python, JavaScript, TypeScript, Java, C#
- **Selenium**: Java (FindBy/By), Python, C# (FindsBy/By)

### Tag Categories
- **Form Elements**: input, button, form, select, textarea, label, option, fieldset, legend, datalist, output, progress, meter, optgroup
- **Interactive Elements**: a, area, map, details, summary, dialog, menu, menuitem
- **Navigation Elements**: nav, header, footer, main, aside, section, article
- **Table Elements**: table, tr, td, th, thead, tbody, tfoot, caption, col, colgroup
- **List Elements**: ul, ol, li, dl, dt, dd
- **Content Elements**: p, span, div, h1-h6, pre, code, blockquote, q, cite, em, strong, small, mark, time, abbr, ins, del, s, u, i, b, sub, sup
- **Media Elements**: audio, video, source, track, canvas, picture, img, svg
- **Embedded Content**: iframe, embed, object, param
- **Utility Elements**: br, hr, wbr, bdi, bdo, ruby, rt, rp, kbd, samp, var, dfn, data

### Locator Strategies
- **Best Locator**: Automatically selects most reliable locator
- **ID**: Uses ID selectors only
- **XPath**: Uses XPath selectors only
- **CSS**: Uses CSS selectors only

### Export Options
- **JSON Export**: Raw element data in JSON format
- **CSV Export**: Element data in CSV format
- **Framework Code**: Generated test automation code

### Commands
- **Open Synkit ElementInsight**: Opens main extension panel
- **Element Insight: Install Dependencies**: Install Python and lxml
- **Element Insight: Install Playwright in Workspace**: Install Playwright in current workspace
- **Element Insight: Install Playwright Browsers**: Install Playwright browsers
- **Element Insight: Run Diagnostics**: Run system diagnostics
- **Element Insight: Show License Agreement**: Display license terms

### System Requirements
- **VS Code 1.97.0 or higher** (January 2025 onwards)
- **Windows, macOS, or Linux** operating system
- **Internet connection** for authentication and updates
- **Workspace installation** for Playwright (not global)
- **Python 3.7+ and lxml** (optional, for enhanced accuracy)

### Technical Details
- **Built with TypeScript** and Rust binaries for performance
- **Uses Playwright** for web page scanning
- **Integrates with Synkit SaaS platform** for quota management
- **Local processing** for element analysis and code generation
- **Secure error handling** with information disclosure prevention
- **Comprehensive logging** with development/production modes
- **Binary integrity verification** for security
- **OAuth 2.0 authentication** with Google
- **Session persistence** across VS Code sessions

### Security Features
- **Binary integrity verification** using SHA-256 hashes
- **Error sanitization** to prevent information disclosure
- **Secure token storage** using VS Code secrets API
- **Input validation** for all user inputs
- **Contextual logging** with different detail levels

### Performance Features
- **Local processing** for faster results
- **Tag filtering** to reduce unnecessary processing
- **Parallel element analysis** for improved speed
- **Memory optimization** for large pages
- **Caching** for repeated operations