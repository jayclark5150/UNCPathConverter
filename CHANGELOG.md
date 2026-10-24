# Changelog

## [1.1.0] - 2026-10-24
- Fixed: "Open UNC" now quotes the path so folders with spaces open correctly
- Fixed: drive letter replaced with plain string handling (prevents misreading $ in share names like admin shares)
- Fixed: Run and Compile commands in README now use the actual script file name
- Added: version number shown in the window title

## [1.0.0] - 2026-07-07
- Initial release: WinForms GUI for pasting mapped drive paths
- Automatically strips quotes from Explorer copy-as-path
- Converts mapped network drives to UNC using Win32_LogicalDisk
- Copies UNC path to clipboard automatically
- One-click "Open UNC" launches the target location in Explorer
- Enter-key support for fast conversion
