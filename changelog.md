# Changelog
<!--Track all additions (+), changes (~), deprications (.),
removals (-), fixes (*), and security (!)-->

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) starting with v1.0.0.

## Unreleased
## v0.5.0
### Changed
- File structure no longer includes duplicates between src and include
### Added
- CMake file for building
### Removed
- Built libraries and their folder
- Old hui header
## v0.4.1
### Changed
- <b>Changed name from HUI (Humble UI) to LUI (Low-Level UI).</b>
- <b>Changed namespace from ***hui*** to ***lui***.</b>
### Added
- DestRectChanged event which can be bound to on any element.
- Macro for converting the hui:: namespace to the new lui:: namepsace.
## v0.4.0
### Added
- Text Field
## v0.3.1
### Fixed
- Items no longer attach to a holder when losing focus and not being dragged.
- Sets now update their focused element when their render area changes.
- Scroll bar now uses rotationally correct math to check for grip focus.
- Scroll bar will no longer fire MouseDown functions on the wrong component (Track vs Grip).
- Scroll bar now uses rotationally correct math for moving the grip when the track is clicked.
- Scroll bar now updates grip focus when grip jumps position.
## v0.3.0
### Added
- Scroll Bar
### Changes
- Sets can now be nested, allowing them to be used as a viewport for a set of other elements (such as options in a scrolling menu).
## v0.2.0
### Added
- Item Element
- Item Holder Element
## v0.1.0
### Added
- Base Element
- Button Element
- Set
