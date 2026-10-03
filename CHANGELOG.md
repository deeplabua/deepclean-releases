# Changelog

## [0.5.5] - 2026-10-03

### Fixed
- **Update & restart** now actually reopens DeepClean after installing an update (it used to quit and stay closed).
- **Check for Updates** is more reliable: a second update feed is used if GitHub's release download is briefly unavailable, and the reason is shown when a check fails.

## [0.5.4] - 2026-10-03

### Added
- **Trash**: checkboxes on every item and a select-all. Uncheck what you want to keep and the button becomes **Delete N items** — only the checked items are removed. With everything checked it's still **Empty Trash**.

## [0.5.3] - 2026-10-03

### Changed
- **Trash** without Full Disk Access: the explanation now sits in the middle of the window, with a button that opens the Full Disk Access settings and the steps to turn it on.

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
