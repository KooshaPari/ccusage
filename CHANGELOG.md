# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [18.0.10] - 2026-03-29

### Changed
- Integrated upstream ccusage changes via repository sync

### Features (from upstream)
- Added `@praha/byethrow-mcp` dependency
- Added `@hono/mcp` dependency
- Added `tsgo` MCP dependency

## [18.0.9] - 2026-03

### Added
- Support for Claude Code fast mode with separate tracking
- 6x pricing multiplier for fast mode operations

## [18.0.8] - 2026-02

### Fixed
- Windows path compatibility using os.homedir() and path.join()

## [18.0.7] - 2026-02

### Added
- pnpm upgrade to 10.30.1
- Node and Bun version updates
- Cache-nix-action integration

### Changed
- Removed devEngines from individual packages
- Enabled enableGlobalVirtualStore in pnpm
- Upgraded VitePress to 2.0.0-alpha.17

### Fixed
- Markdown-it type mismatch in VitePress config
- Vitest upgraded to v4.1 with workspace GitHub integration
- Resolve path compatibility across platforms

## [18.0.1] - 2025-11

### Added
- Initial ccusage tracking for Claude API usage
- Model pricing support
- Ampersand (AMP) integration for proxy pricing
- Release automation with version tracking
- CI/CD pipeline with GitHub Actions
- Pre-commit configuration
- Documentation and guides

### Features
- Cost tracking for various Claude models
- Direct model pricing with fallback to zero-cost
- Node.js and Bun runtime support
- GitHub integration

[Unreleased]: https://github.com/KooshaPari/ccusage/compare/v18.0.10...HEAD
[18.0.10]: https://github.com/KooshaPari/ccusage/compare/v18.0.9...v18.0.10
[18.0.9]: https://github.com/KooshaPari/ccusage/compare/v18.0.8...v18.0.9
[18.0.8]: https://github.com/KooshaPari/ccusage/compare/v18.0.7...v18.0.8
[18.0.7]: https://github.com/KooshaPari/ccusage/compare/v18.0.1...v18.0.7
[18.0.1]: https://github.com/KooshaPari/ccusage/releases/tag/v18.0.1
