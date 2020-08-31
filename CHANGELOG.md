# Changelog

All notable changes to this project will be documented in this file.

Note: this project forked `omniauth-identity` at v1.1.1. This project's *first* version is v2.0.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0] - 2020-08-31

### Added 
- CHANGELOG to maintain a history of changes.
- Include mongoid-rspec gem.

### Changed
- Updated README to include information about the reasoning and aims of the fork.
- Updated all references of the gem name to `omniauth-identity2`.
- Updated copyright information.
- Updated spec syntax from RSpec v2 -> v3.
- Updated mongoid_spec.rb to leverage mongoid-rspec features.
- Fix security warning about missing secret in session cookie.

### Removed
- Gemfile.lock file
- Dependency version limits so that the most up-to-date gem dependencies are used.
- MongoMapper support; unable to satisfy dependencies of both MongoMapper and Mongoig now that MongoMapper is no longer actively maintained.