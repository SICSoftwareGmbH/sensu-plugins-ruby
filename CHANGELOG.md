# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Changed
- change ruby-version regex to match "[ruby-]3[.0.0]"
- change filter logic to support 3.0.0

## [0.2.0] - 2020-01-13
### Changed
- use RVM master branch to validate current ruby versions

## [0.1.3] - 2019-07-30
### Fixed
- error output if updating the advisory-db failed

## [0.1.2] - 2019-07-27

## [0.1.1] - 2019-07-26

## [0.1.0] - 2019-07-26
### Added
- check if ruby version is current
- check for security advisories using bundler-audit
