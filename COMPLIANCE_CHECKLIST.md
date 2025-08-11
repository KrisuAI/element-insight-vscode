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
- [ ] node-fetch copyright notice included (David Halls)
- [ ] open copyright notice included (Sindre Sorhus)
- [ ] TypeScript copyright notice included (Microsoft Corporation)
- [ ] ESLint copyright notice included (OpenJS Foundation)
- [ ] Webpack copyright notice included (webpack contributors)

### License Texts
- [ ] Apache 2.0 license text included for Firebase
- [ ] Apache 2.0 license text included for TypeScript
- [ ] MIT license text included for node-fetch
- [ ] MIT license text included for open
- [ ] MIT license text included for ESLint ecosystem
- [ ] MIT license text included for Webpack ecosystem

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

| Your License | MIT Libraries | Apache 2.0 Libraries | GPL Libraries |
|--------------|---------------|----------------------|---------------|
| MIT + Attribution | ✅ Compatible | ✅ Compatible | ❌ Incompatible |

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
