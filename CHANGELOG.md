# Changelog

## [0.5.0] - 2026-10-03

### Added
- **Auto-update**: DeepClean checks for a new version on launch and installs it in place (Update & restart). Toggle in Settings → General, manual check in Settings → About.

### Fixed
- Applications: leftovers nested under a vendor folder (e.g. `McNeel/Rhinoceros/8.0`) are matched per app version, so uninstalling one version no longer claims files shared with another.
