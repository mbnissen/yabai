# Changelog

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- New config setting (*window_placement*) to specify whether newly created windows become the first or second child [#65](https://github.com/koekeishiya/yabai/issues/65)

### Changed
- Hide power indicator from the status-bar if a battery could not be found [#60](https://github.com/koekeishiya/yabai/issues/60)
- Disable focus follows mouse while the *mouse_modifier* key is held down [#62](https://github.com/koekeishiya/yabai/issues/62)
- Silence meaningless warning reported by the scripting-bridge framework [#55](https://github.com/koekeishiya/yabai/issues/55)
- Extend definition of *WINDOW_SEL* to include *mouse*, targetting the window below the cursor [#66](https://github.com/koekeishiya/yabai/issues/66)

## [1.0.1] - 2019-06-23
### Added
- First official release

[Unreleased]: https://github.com/koekeishiya/yabai/compare/v1.0.1...HEAD
[1.0.1]: https://github.com/koekeishiya/yabai/releases/tag/v1.0.1