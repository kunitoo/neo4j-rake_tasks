# Change Log
All notable changes to this project will be documented in this file.
This file should follow the standards specified on [http://keepachangelog.com/]
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased][unreleased]

## [0.4.2] - 02-17-2016

### Fixed

- Matching variables / values in `properties` (see #21, thanks to bobmazanec)
- Default port in config task to 7474

## [0.4.0] - 01-13-2016

### Added

- In addition to ability to `community-latest`, added ability to install `community-(stable|rc|release-candidate|milestone)` as defined in config
- Ability to give an argument to `ServerManager#stop` with a timeout to force shutdown

## [0.3.0] - 09-27-2015

### Added
- Add `shell` rake task.  Start Neo4j if it is not already started (and stop afterward)

## [0.2.0] - 09-27-2015

### Added
- Added `console` task (thanks to darrin-wortlehock via #13)

## [0.1.0] - 09-24-2015

### Changed
- Use rubyzip rather than zip

### Fixed
- Fix `rake neo4j:reset_yes_i_am_sure` not actually resetting the db

## [0.0.8] - 08-17-2015

### Fixed

- Lack of an explicit `require 'rake'` could cause errors in projects using this gem.

## [0.0.1]-[0.0.7]
- Early releases. Moved tasks from `neo4j-core` gem, refactored.
