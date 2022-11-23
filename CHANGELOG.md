<!-- Keep a Changelog guide -> https://keepachangelog.com -->

# SwiftLint Changelog

## 1.14.0
### Fixed
 - Fixed autocorrect action

## 1.13.8
### Fixed
 - Removed a warning

## 1.13.7
### Changed
 - Documentation updated (thanks to https://github.com/mleonhard)
### Fixed
 - Restored work in CLion 2021

## 1.13.6
### Fixed
 - Fixed comments autocompletion (again)
 - Fixed problem when SwiftLint did not run if other errors are present in the file.

## 1.13.4, 1.13.5
### Fixed
 - Fixed comments autocompletion
 - Fixed problem with configuration file searching in projects with Swift Package Manager and with multiple projects opened.

## 1.13.3
### Fixed
 - Fixed problem with not using configuration file right after it was added (file change needed previously).

## 1.13.2
### Fixed
 - Fixed problem with inspection enabling/disabling.
 - Fixed problem with configuration reloading.

## 1.13.1
### Fixed
 - Fixed problem with configuration file search.

## 1.13.0
### Changed
 - Removed config file specification from command line arguments. This will allow using nested configurations and other SwiftLint configuration options.
 - Switched to Kotlin.
 - Added basic completion for SwiftLint comments. Thanks to https://github.com/MontakOleg.
 - Updated per-project configuration.

## 1.12.0
### Added
 - Added per-project swiftlint path configuration. Thanks to https://github.com/MontakOleg.

## 1.11.0
### Added
 - Added ability to use separate configuration files in different project directories.

## 1.10.6
### Changed
 - Minor fixes.

## 1.10.5
### Added
 - CLion support.
