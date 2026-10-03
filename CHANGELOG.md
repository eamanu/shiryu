# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## v0.1.0 (2026-10-03)

### Added

- **releaser**: add branch option to release
- **releaser**: add push command
- **releaser**: Add release command
- use static project version
- update dagger.io to v1.0.0-beta.15
- add release command and release workflow
- add linter vcs
- replace mypy for ty
- add documenter auditor that runs with llm
- change to zensical
- add auditor
- Add python SDK
- Initial commit

### Changed

- **releaser**: remove unnused code
- **dagger**: remove shiryu registry

### Fixed

- minor issue in template generator
- after init --is-update
- improve releaser release and test chore: update docstrings
- secrets handling
- check that uv.lock is consistent with pyproject.toml
- secrets handling
- git depth for lint-vcs
- dagger function to scm conversion and refactor case module
- documentation zensical.toml parse and improve minimal version definitions
- ty.toml.jinja2
- fix tests
- fix checker
- remove zensical in shiryu branch versions
