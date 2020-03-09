# Change Log
All notable changes to this project will be documented in this file.

## [1.4.1] - 2020-03-09

- Added constants FILES_DEFAULT_FILE_PERMS and FILES_DEFAULT_DIR_PERMS

## [1.4] - 2020-02-26

- Added methods for setting and getting default file and directory permissions
  - Files::SetDefaultFilePerms()
  - Files::GetDefaultFilePerms()
  - Files::SetDefaultDirPerms()
  - Files::GetDefaultDirPerms()
- Added method Files::NormalizeFilePerms() (works for a file or directory)
- Method Files::GetFileContent() fixed

## [1.3.1] - 2019-07-03

- Files::GetTempFilename() fixed (filename prefix was not considered)

## [1.3] - 2018-05-29

### Added
- Added new method Files::MkdirForFile()

## [1.2] - 2018-04-19

### Added
- Option "maxdepth" added to Files::FindFiles()
- Added new method Files::GetTempDir()

## [1.1] - 2017-05-02

### Added
- New method added: Files::FindFiles()

### Fixed
- Files::DetermineFileType() uses function mime_content_type()
- Files::RecursiveUnlinkDir fixed

## [1.0] - 2017-01-23

Library "Files" was extracted from the ATK14 Framework.
