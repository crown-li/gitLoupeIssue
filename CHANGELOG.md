# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/2.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.2] - 2026-05-11

### Added
- Initial release of Git Loupe! 🎉
- Inline Git blame annotations for the active line.
- Rich hover card showing author, commit message, date, and commit hash.
- Smart contextual diff snippets using Git `histogram` algorithm.
- Support for viewing uncommitted workspace changes.

## [1.0.3] - 2026-05-13

### Changed
- Compatible with lower versions of VSCode `1.93.1`.

## [1.0.4] - 2026-06-10

### Fixed
- Fixes known issues.

## [1.0.5] - 2026-06-11

### Security
- Resolve some security issues.
- Optimize code to improve performance.

## [1.0.6] - 2026-06-12

### Changed
- Modify project description.
- Improve version records.

## [1.0.7] - 2026-06-15

### Added
- Adds clickable commit hash in hover card.
- Implemented **Diff Editor** view when clicking commit hash, showing before/after changes.

## [1.1.0] - 2026-06-16

### Added
- Newly adds version navigation
- Support for comparing workspace content with latest commit.
- Navigation buttons now always visible in editor title bar.

### Changed
- Updated Diff Editor title format to clearly show version comparison.

### Fixed
- Fixes click event not working on commit hash link.
- Fixes module resolution errors in diff view.

## [1.1.1] - 2026-06-17

### Added
- Adds status bar tooltip for better user guidance.
- Adds copying hash value to clipboard.

### Changed
- Refactored codebase for improved maintainability and performance.
- Optimize the display effect before submission.

## [1.1.2] - 2026-06-18

### Fixed
- Fix some issues with DIff View attempting to switch.

## [1.1.3] - 2026-06-22

### Fixed
- Fixes known issues.

## [1.1.4] - 2026-07-31

### Added
- Full Emoji Support: Expanded built-in emoji library fully aligned with the open-source standards of Gitmoji and Conventional Commits, adding over 30 common scenarios including hot updates, Docker operations, dependency upgrades, WIP and more.
- Commit Spec & English Hints: Added English descriptions and commit specification suffixes (e.g. feat, fix, chore) in the emoji picker for a more professional UI and clearer semantics.
- Quick Pinyin & English Search: Enabled matchOnDetail matching. You can now directly type English abbreviations in the search box (e.g. enter hotfix to quickly locate 🚑, perf to find ⚡), greatly boosting input efficiency.
- Multi-root Workspace Smart Support: When multiple Git subprojects exist in the workspace, triggering via the command palette will automatically pop up a repository selector for you to specify the target for insertion.

## [1.1.5] - 2026-08-07

### Added
- **Visual Emoji Picker**: A new grid-based webview panel to visually browse, preview, and insert emojis directly into the SCM commit box.
- **Expanded Library & Smart Search**: Added over 200 curated emojis aligned with Gitmoji. Features bilingual descriptions (English/zh-CN) and supports keyword searching (e.g., typing "feat", "fix", or "hotfix" instantly finds the right emoji).
- **Multi-Repo Support**: When working in multi-root workspaces, you can now select the target repository before inserting an emoji.

### Changed
- **Improved Insertion Flow**: Emojis are now automatically prepended to your existing commit message, and the input box auto-focuses for a smoother typing experience.
- Refactored the underlying emoji data structure for better localization (i18n) and maintainability.

### Fixed
- Resolved an issue where emoji insertion failed in multi-repository workspaces.
- Fixed UI styling inconsistencies between the QuickPick and Webview panels.