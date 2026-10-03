# Changelog

## [0.5.2] - 2026-10-03

### Fixed
- **Trash** no longer claims to be empty when DeepClean can't read it (no Full Disk Access): it says so, links to the Full Disk Access settings, and Empty Trash still works.

### Added
- **Settings → General → App version** with a Check for Updates button.

## [0.5.1] - 2026-10-03

### Changed
- **Trash** redesigned like the other modules: ring chart of what's in the Trash by type (apps, folders, videos, archives…), hold-to-confirm **Empty Trash**, and a list of the Trash contents with size. Click a ring segment to filter.
- Emptying the Trash is now logged (Operations Log) and shows a Space Receipt with what was freed.

## [0.5.0] - 2026-10-03

### Added
- **Auto-update**: DeepClean checks for a new version on launch and installs it in place (Update & restart). Toggle in Settings → General, manual check in Settings → About.

### Fixed
- Applications: leftovers nested under a vendor folder (e.g. `McNeel/Rhinoceros/8.0`) are matched per app version, so uninstalling one version no longer claims files shared with another.
