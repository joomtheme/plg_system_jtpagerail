# Changelog

All notable changes to JT Page Rail will be documented in this file.

## [0.2.4] - 2026-06-09

### Added
- Added a right-side rail interface for the Joomla core Page Break Article Index.
- Added support for hover or click opening behavior.
- Added Joomla Web Asset Manager based frontend asset loading.
- Added Joomla 5 and Joomla 6 update server compatibility metadata.

### Changed
- Improved the plugin parameter UI for the hover label option.
- The `Show hover label` option is now only shown when `Open mode` is set to `Click`.
- Clarified English and Turkish language strings for the hover label behavior.
- Updated frontend asset filenames to `site-v024.css` and `site-v024.js` to reduce browser and Joomla cache conflicts.

### Fixed
- Fixed cases where the original Joomla core Article Index box could remain visible instead of being moved into the right-side rail.
- Fixed confusing behavior where the `Show hover label` option appeared inactive in hover-open mode.
- Kept the install manifest JED-compatible by not using unsupported `<php_minimum>` in the extension manifest.

### Compatibility
- Joomla 5.x
- Joomla 6.x
- PHP 8.1+
