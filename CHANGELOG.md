# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic
Versioning](http://semver.org/spec/v2.0.0.html).

## Unreleased

## [0.4.0] - 2020-12-03

### Breaking change
- Changed annotation keyspace from "sensu.io/plugins/ec2deregistration/config"to
  "sensu.io/plugins/sensu-ec2-handler/config" for consistency

### Changed
- Update Sensu Go and SDK dependencies with the correct modules
- README updates
- Add Secret: true to appropriate options
- Changed PluginConfig to be more consistent with new name
- Changed auth to support instance roles, shared credentials
- Added auth support for assuming a role
- Added deprecation warnings about using key arguments

## [0.2.1] - 2020-02-10

### Fixed
- Removed 32-bit builds in Bonsai

## [0.2.0] - 2020-02-10

### Changed
- Renamed the project to sensu-ec2-handler

## [0.1.0] - 2020-02-07

### Changed
- Refactoring to use sensu-plugin-sdk

## [0.0.1] - 2020-01-14

### Added
- Initial release
