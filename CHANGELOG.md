# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)

<!--
## [<exact release including patch>](<github compare url>) - <release date in YYYY-MM-DD>
### Added
  - <summary of new features>

### Changed
  - <for changes in existing functionality>

### Deprecated
  - <for soon-to-be removed features>

### Removed
  - <for now removed features>

### Fixed
  - <for any bug fixes>

### Security
  - <in case of vulnerabilities>
-->

## [Unreleased](https://github.com/cyverse/django-cyverse-auth/compare/1.1.5...HEAD) - YYYY-MM-DD
## [1.1.5](https://github.com/cyverse/django-cyverse-auth/compare/1.1.4...1.1.5) - 2018-08-31
### Fixed
  - Fix unnecessary session and token creation
    ([#20](https://github.com/cyverse/django-cyverse-auth/pull/20))
  - Prevent expired tokens from granting api access
    ([#21](https://github.com/cyverse/django-cyverse-auth/pull/21))