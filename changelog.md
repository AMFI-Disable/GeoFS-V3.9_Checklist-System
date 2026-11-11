# Changelog

All notable changes, operational procedures, and version releases for GeoFS-V3.9 Checklist System are documented in this file.

---

## [3.9.0] - Unified Metadata

### Changed

- Standardize the userscript metadata and version across the V3.9 ecosystem.
- Match only the GeoFS main site and activate only when it reports V3.9.

---

## [Unreleased]

### Changed

- **HUD Tab Label**: Renamed registered HUD tab from `CHECKLIST` to `CHECKS` for compact alignment.
- **Theme Alignment**: Aligned aircraft title, scrollbar, and UI accent colors from amber to neutral styling (`#dddddd`).
- **Favicon Metadata**: Switched userscript icon reference to the official GeoFS favicon.

### Removed

- **Redundant Startup Toast**: Suppressed individual engine ready toast in favor of centralized ecosystem notifications.

---

## [2.0.6] - GeoFS V3.9 Compatibility

### Changed

- Start only after GeoFS reports V3.9; remain inactive on other or unrecognized versions.
- Update compatibility documentation and version metadata.

---

## [2.0.1] - Airframe Detection And HUD Integration

### Added

- **Dynamic Airframe Profile Loading**: Automatically reads current aircraft ID to load custom checklist procedures (Boeing 737, Airbus A320, Concorde, general aviation).
- **HUD [CHECKS] Tab Embedding**: Integrates directly into the central Information Display navigation pane.

### Fixed

- **Scroll Position Restoration**: Remembers completed procedure items and active scroll offset when switching tabs.
- **Visual Checkbox Feedback**: Enhanced completion styling with high-contrast amber checkmarks.

---

## [2.0.0] - Interactive Procedural Engine

### Added

- **Multi-Phase Procedures**: Standard operating procedure checklists covering Preflight, Before Start, After Takeoff, Approach, and Shutdown phases.
- **Glassmorphic Procedure Card**: High-contrast, translucent checklist card with non-blocking draggable capabilities.

---

## [1.0.0] - Initial Production Release

Initial release of the procedural checklist system for GeoFS.
