# License Compliance Checklist

This checklist ensures the Element Insight VS Code Extension maintains proper license compliance.

## ✅ Pre-Distribution Checklist

### License Files
- [ ] `LICENSE` file includes third-party library acknowledgment
- [ ] `THIRD_PARTY_LICENSES.md` contains all required license texts
- [ ] `ATTRIBUTION.md` provides proper attribution for all libraries
- [ ] All license files are copied to distribution via webpack

### Copyright Notices
- [ ] Firebase copyright notice included (Google LLC)
- [ ] Firebase ecosystem packages copyright notice included (Google LLC)
- [ ] node-fetch copyright notice included (David Halls)
- [ ] open copyright notice included (Sindre Sorhus)
- [ ] Playwright copyright notice included (Microsoft Corporation)
- [ ] Python copyright notice included (Python Software Foundation)
- [ ] lxml copyright notice included (Infrae and contributors)
- [ ] Node.js copyright notice included (Node.js contributors)
- [ ] npm copyright notice included (npm, Inc.)
- [ ] TypeScript copyright notice included (Microsoft Corporation)
- [ ] TypeScript ESLint packages copyright notice included
- [ ] ESLint ecosystem packages copyright notice included (OpenJS Foundation)
- [ ] Webpack ecosystem packages copyright notice included (webpack contributors)
- [ ] Protobuf ecosystem packages copyright notice included (Daniel Wirtz)
- [ ] gRPC copyright notice included (Google LLC)
- [ ] ISC license packages copyright notice included (Internet Systems Consortium, Inc.)
- [ ] Python-2.0 license packages copyright notice included (Python Software Foundation)
- [ ] BSD-2-Clause license packages copyright notice included (Various contributors)
- [ ] Various utility packages copyright notices included

### License Texts
- [ ] Apache 2.0 license text included for Firebase
- [ ] Apache 2.0 license text included for Firebase ecosystem packages
- [ ] Apache 2.0 license text included for TypeScript
- [ ] Apache 2.0 license text included for Playwright
- [ ] Apache 2.0 license text included for gRPC
- [ ] PSF license text included for Python
- [ ] BSD license text included for lxml
- [ ] BSD-3-Clause license text included for Protobuf ecosystem packages
- [ ] BSD-2-Clause license text included for JavaScript parsing utilities
- [ ] ISC license text included for various utilities
- [ ] Python-2.0 license text included for argparse
- [ ] MIT license text included for Node.js
- [ ] MIT license text included for npm
- [ ] MIT license text included for node-fetch
- [ ] MIT license text included for open
- [ ] MIT license text included for ESLint ecosystem packages
- [ ] MIT license text included for TypeScript ESLint packages
- [ ] MIT license text included for Webpack ecosystem packages
- [ ] MIT license text included for various utility packages

### Documentation
- [ ] README.md includes licensing section
- [ ] Links to all license files provided
- [ ] Third-party library list documented
- [ ] License compatibility explained

## 🔄 Maintenance Checklist

### When Adding New Dependencies
- [ ] Check license type and compatibility
- [ ] Add to `THIRD_PARTY_LICENSES.md`
- [ ] Add to `ATTRIBUTION.md`
- [ ] Update main `LICENSE` file
- [ ] Update `README.md`
- [ ] Update webpack config if needed

### When Updating Dependencies
- [ ] Verify license hasn't changed
- [ ] Update version numbers in documentation
- [ ] Check for new copyright holders
- [ ] Verify license compatibility

### Before Each Release
- [ ] Run `npm audit` for security
- [ ] Verify all license files are current
- [ ] Check that webpack copies all files
- [ ] Test distribution package contents

## 📋 Compliance Verification

### License Compatibility Matrix

| Your License | MIT Libraries | Apache 2.0 Libraries | PSF/BSD/BSD-2-Clause/BSD-3-Clause/ISC/Python-2.0/Artistic Libraries | GPL Libraries |
|--------------|---------------|----------------------|----------------------------------------------------------------------|---------------|
| MIT + Attribution | ✅ Compatible | ✅ Compatible | ✅ Compatible | ❌ Incompatible |

### Required Actions by License Type

#### MIT License
- ✅ Include copyright notice
- ✅ Include permission notice
- ✅ No additional restrictions

#### Apache 2.0 License
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### PSF License (Python)
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### BSD License (lxml)
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### BSD-3-Clause License (Protobuf ecosystem)
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### BSD-2-Clause License (JavaScript parsing utilities)
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### ISC License (Various utilities)
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### Python-2.0 License (argparse)
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### Artistic License 2.0 (npm)
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### GPL License
- ❌ **NOT COMPATIBLE** with MIT
- ❌ **DO NOT USE** in this extension
- ❌ Would require GPL licensing for entire extension

## 🚨 Compliance Issues to Watch

### High Risk
- **Missing License Texts**: Could result in license violation
- **Missing Copyright Notices**: Could result in copyright infringement
- **Incompatible Licenses**: Could require license change

### Medium Risk
- **Outdated License Information**: Could miss license changes
- **Missing Attribution**: Could appear unprofessional
- **Incomplete Documentation**: Could confuse users

### Low Risk
- **Formatting Issues**: Cosmetic, doesn't affect compliance
- **Missing Links**: Doesn't affect legal compliance

## 📚 Resources

### License Information
- [MIT License](https://opensource.org/licenses/MIT)
- [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0)
- [GPL License](https://www.gnu.org/licenses/gpl-3.0.en.html)

### Compliance Tools
- `npm audit` - Security vulnerability check
- `npm ls` - Dependency tree verification
- `npm outdated` - Check for updates

### Legal Resources
- [Open Source Initiative](https://opensource.org/)
- [Software Freedom Law Center](https://www.softwarefreedom.org/)
- [Creative Commons](https://creativecommons.org/)

## 📞 Support

For compliance questions or issues:

- **Email**: support@krisu.ai
- **Documentation**: https://krisu.ai/docs
- **Legal Team**: legal@krisu.ai

## 📝 Change Log

### Version 1.0 (January 2025)
- Initial compliance checklist created
- All required license files implemented
- Full attribution provided for all dependencies
- Compliance verified for distribution

---

**Last Updated**: January 2025  
**Version**: 1.0  
**Maintained By**: Krisu.ai Development Team
