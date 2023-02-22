# Change Log

All notable changes to the "DevCalc" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

- Localization.

## [1.0.0] - 2022-08-08

- Initial release.

## [1.0.1] - 2022-08-12

### Fixed

- Fixed method of removing leading zero.

## [1.0.2] - 2022-08-17

### Added

- Added shortcut keys for updating screen width.
- Added configuration options for status bar appearance and position.

## [1.0.3] - 2022-10-09

### Added

- Added configuration options for line annotations:
  - Always-On display.
  - Color.

## [1.0.4] - 2022-10-11

### Added

- Added conversion options:
  - Convert between `px` and `rem`.
  - Convert between `px` and `%`.
  - Configuration of convert types (`vw` `px` `rem`).
  - Configuration of root font size for `rem`.

### Changed

- Renamed commands for better clarity.
- Updated decorations and hover methods to improve user experience.

## [1.1.0] - 2022-10-17

### Fixed

- Fixed method for removing leading zero.

### Added

- Added configuration for general screen widths.
- Added configuration for enabling general screen widths.
- Added ability to quickly switch between general screen widths.
- Enabling autocomplete conversion will disable `Suggest: Show Units` to improve user experience.

## [1.1.1] - 2022-11-25

### Changed

- Added support for 0 and negative numbers in line annotations.

## [1.1.2] - 2022-11-25

### Fixed

- Fixed support for 0 in line annotations.

### Changed

- Changed line annotations color.

## [1.1.3] - 2022-11-25

### Changed

- Updated method of adding 0 to line annotations.

## [1.1.4] - 2022-11-28

### Fixed

- Fixed method of adding 0 to line annotations.

## [1.1.5] - 2023-02-20

### Enhancement

- Optimized code structure.

### Added

- Added support for "auto" in line annotations.

## [1.1.6] - 2023-02-22

### Fixed

- Fixed method of converting `rem/%` to `px`.
- Fixed the update screen width method when `enableGeneralScreenWidths` is true and `generalScreenWidths` has only one value.

### Added

- When `convertType` is set to `rem`:
  - Added support for displaying the current root font size in status bar.
  - Added support for updating the root font size with shortcut keys.
