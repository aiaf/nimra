# Nimra نمرة
## Release Notes

### v1.02 - 2018-3-14
- A better hack to fix issue from v1.0 (font not working in Firefox). This relies on ccmp mapping a zero-ar to itself without the addition of an extra glyph.

### v1.01 - 2018-3-12
- Fixed a bug where if the font doesn't have at least 1 entry in the `init` table it won't render Eastern Arabic numerals in Firefox. Creating zero-ar.init and making a substitution based on it fixes this issue.
### v1.0 - 2018-3-11
- Initial public release.