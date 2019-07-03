# Change Log
All notable changes to this project will be documented in this file.

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
