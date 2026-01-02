# Changelog

## [Unreleased]

### Fixed
- Improved event handling robustness in session cleanup
- Removed unsafe type casting in favor of proper optional chaining
- Added session ID validation before cleanup operations
- Added error handling for cleanup failures to prevent plugin crashes

### Changed
- Event handler now validates session ID type and format
- Cleanup errors are logged instead of causing silent failures
