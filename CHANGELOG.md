# Changelog

All notable changes to this project will be documented in this file.

## [1.1.0] - 2025-11-18

### Changed
- **API Modernization**: Fully migrated to modern WoW APIs (The War Within / 11.0+).
- Replaced deprecated `GetSpellInfo` and `GetSpellCooldown` with `C_Spell` equivalents.
- Replaced legacy `InterfaceOptions_AddCategory` with `Settings` API.
- Removed all backward compatibility code for pre-11.0 clients.

## [1.0.0] - 2025-01-XX

### Added
- Initial stable release

### Changed
- Updated addon interface version to 110205 (WoW 11.2.5 - The War Within)
- Cleaned up codebase by removing all debugging chat messages
- Improved silent operation - addon now works quietly in the background

### Fixed
- Removed debug spam from normal gameplay operation
- Addon now only shows meaningful user-facing messages

---

## Previous Versions

### [0.1.3]
- Various bug fixes and improvements

### [0.1.2]
- Initial release with TWW Season 3 dungeon support




