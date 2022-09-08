# Change Log
All notable changes to this project will be documented in this file.

## [1.6.3] - 2022-09-08

* d6e2ed5 - Added mime type detection for AVIF images

## [1.6.2] - 2021-11-06

- 4f5d6f6 - Proper mime type detection of a jar file (application/java-archive)
- 9f97cd0 - Proper mime type detection of an apk file (application/vnd.android.package-archive)
- 21602d1 - Better SVG files recognition

## [1.6.1] - 2021-03-04

- Method Files::GetImageSize() fixed for PHP8

## [1.6] - 2021-03-04

- Added method Files::GetImageSizeByContent()
- Method Files::GetImageSize() accepts filename as the first parameter, but the obsolete usage is preserved - It gonna be BC BREAK!

## [1.5] - 2021-02-06

- Added methods Files::TouchFile() and Files::EmptyFile()

## [1.4.2] - 2020-03-09

- Constants FILES_DEFAULT_FILE_PERMS and FILES_DEFAULT_DIR_PERMS are not defined to the default values when they are not defined

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
