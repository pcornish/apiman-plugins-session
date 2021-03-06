# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
- ...

## [1.2.0] - 2016-09-17
### Added
- Bumps apiman base version to 1.2.4.Final.
- Switches to Java 8 as a minimum.
- JWT support! Replaces expectation of a plain JSON response token with a signed JWT.
- Issuer plugin invalidates session on failure to parse API response.

## [1.1.4] - 2016-03-07
### Added
- Bumps apiman base version to 1.2.2.Final.
- Makes path matcher mandatory.

## [1.1.3] - 2016-03-05
### Added
- Project version is now independent of apiman core version.
- Changelog (this file!)

## [1.1.2] - 2016-03-05
### Added
- Tidies up message bundle initialisation and logging configuration.
- Tidies up unit tests. Improves message naming.

## [1.1.1] - 2016-03-01
### Added
- Added behaviour for forcing removal of cookie even if not sent by the browser.

## [1.1.0] - 2016-02-14
### Added
- Rebase plugins to standalone project.

## [1.0.0] - 2015-12-18
### Added
- Added Cookie Issuer Policy.
- Added Cookie Validator Policy.
- Added Cookie Removal Policy.
