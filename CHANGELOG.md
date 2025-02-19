# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Changed

## [0.1.13] - 2019-08-16
### Fixed
- Pages always created a new record when store code included in url

## [0.1.12] - 2019-08-16
### Fixed
- Don't include store code in logged paths

## [0.1.11] - 2019-04-08
### Added
- Console command header
- Option to dump run config in console
- Ability to set config options in admin

### Changed
- Path to config options to fit admin UI

### Fixed
- Initialize Guzzle client only when used
- Wrap page log in try/catch so that in the case of a failure it doesn't stop the page rendering

## [0.1.10] - 2019-04-04
### Fixed
- add guzzle dependancy

## [0.1.9] - 2019-02-18
### Changed
- Add ability to pass options into crawler console command 

## [0.1.8] - 2019-02-18
### Fixed
- Fixed issue where configured batch size wasn't used 

## [0.1.7] - 2019-02-15
### Changed
- Code standards refactoring 

### Added
- Move config to helper class
- Add and program too crawler interface
- Add config getters/setters to interface so that default config can be overridden by consuming code

## [0.1.6] - 2019-02-4
### Changed
- Added uptime robot to user agent blacklist
- Remove use of object manager in page repostory

### Added
- Added some basic unit tests
- Added a readme file
- Added a changelog file
- Added a license

## [0.1.5] - 2019-01-10
### Changed
- Improved efficiency of page flush 

### Changed
- Added google and facebook campaign parameters to url parameter blacklist

## [0.1.4] - 2019-01-10
### Added
- Pages under a given priority threshold will not be crawled

## [0.1.3] - 2019-01-09
### Added
- Added a max runtime to process task to avoid issues with long running processes

## [0.1.2] - 2018-11-11
### Fixed
- Fix issue with X-Magento-Vary handling in logger

## [0.1.1] - 2018-11-08
### Fixed
- Add config to run cron task as seperate process

## 0.1.0 - 2018-10-15
### Added
- Initial extension build
